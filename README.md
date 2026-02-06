# RAPID: Reconfigurable, Adaptive Platform for Iterative Design
[[Project page]](https://rapid-kit.github.io/)
[[Paper]](https://rapid-kit.github.io//#paper)

<img width="90%" src="assets/rapid_teaser.png">
[authors_place_holder](https://rapid-kit.github.io//)<sup>1,2</sup>,
<sup>1</sup> University,

## HardWare Guide

3D Print: [https://makerworld.com/en]  Markerworld device direct print link, tested on Bambu A1 and Bambu P1s, Bambu PLA Basic

Opensoure 3D Model: Step github link

Assembly tutorial:
BOM: 

## Handheld Data Collection Pipeline

UMI-style Go Pro pipeline: https://github.com/aod321/zumi_pipeline

iPhone pipeline: 



## LeRobot Data Collection Pipeline

Hardware:

- [Dummy Robot v2](https://www.bilibili.com/video/BV18x421Q7Td/?spm_id_from=333.337.search-card.all.click&vd_source=37a31ba08a1cea640252b9baeef296ea) 

- Ref Controller Firmware: https://github.com/aod321/50_arm_dummy-ref-core-fw

  - Set DM3510 ID before integrate RAPID into this robot: 

    ```
    SLAVE_ID = 0x37
    MASTER_ID = 0x47
    ```
  

- Main Camera and Gripper Camera: logitech c922 pro

SoftWare:

https://github.com/aod321/lerobot

- Install:

```
  git clone https://github.com/aod321/lerobot.git
  cd ./lerobot
  uv venv
  uv sync
```

- Teleop Data Collection

```
python scripts/record_dummy.py --resume --camera-index 2 --wrist-camera-index 0 -n 50 --dataset [HUGGINGFACE_DATASET_ID] --camera-width 320 --camera-height 240
```

- Training

```
CUDA_VISIBLE_DEVICES=1 lerobot-train --policy.type=diffusion --dataset.repo_id=[HUGGINGFACE_DATASET_ID] --output_dir=outputs/RAPID_dummy_pick_place_green_cube_GET_0127 --policy.repo_id=[HUGGINGFACE_POLICY_ID]
```

- Inference:

```
lerobot-teleoperate --robot.type=dummy_follower --robot.serial_number=396636713233 --robot.cameras='{"top":{"type": "opencv", "index_or_path": 0, "width": 320, "height": 240, "fps": 30}, "wrist": {"type": "opencv","index_or_path": 2, "width": 320, "height": 240, "fps": 30}}' --policy.path=[HUGGINGFACE_POLICY_ID]
```

