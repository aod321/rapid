# Hardware Building Guide

## Bill of Materials

### Base System (~$52)

| Component                           | Unit Cost | Qty   | Subtotal | Taobao (China) | Overseas (Untested) |
| ----------------------------------- | --------- | ----- | -------- | -------------- | ------------------- |
| DM3510 Motor (w/ USB2CAN & adapter) | ~$50      | 1     | $50      | [Link](https://item.taobao.com/item.htm?abbucket=9&id=871173947758&mi_id=0000NAx0q0xiNRqF_TbheAbI67kkDka6Hol3ZWPM4v9qshg&ns=1&skuId=5872003791070&spm=a21n57.1.hoverItem.2&utparam=%7B%22aplus_abtest%22%3A%223fa9cacb64c2fe1854a7486219b6950b%22%7D&xxc=taobaoSearch) | [Link](https://store.foxtech.com/damiao-dm-h3510-brushless-dc-motor/?srsltid=AfmBOoqAyWZtjCbbcZu9fjn--7SYctox4C7mT0rjzLTaNX_nbw-g5XHS) |
| M3 Screws                           | ~$0.1     | 3     | $0.3     | — | — |
| M2 Screws (vertical lock)           | ~$0.1     | 2     | $0.2     | — | — |
| PLA Filament                        | ~$1.5     | —     | $1.5     | [Link](https://detail.tmall.com/item.htm?abbucket=9&fpChannel=101&fpChannelSig=ba66adbe72ecf0516ee61c361cf9ad1b6e97b3fb&id=925814115885&mi_id=00006NbByqIdYku8hFmvXajuJUKncFtnyDhUiJp24J4wq0A&ns=1&skuId=5974825507492&spm=a21n57.1.hoverItem.3&utparam=%7B%22aplus_abtest%22%3A%223f186b53b6e33a7f21bc911bf78c7a81%22%7D&xxc=taobaoSearch) | [Link](https://us.store.bambulab.com/products/pla-basic-beginner-s-filament-pack) |

### Optional Add-ons

| Component                           | Unit Cost | Qty   | Subtotal | Taobao (China) | Overseas (Untested) |
| ----------------------------------- | --------- | ----- | -------- | -------------- | ------------------- |
| **Tactile Module** *(based on [GET design](https://github.com/GelSight-lab/GraspEveryThing/))* |  |  | **~$15** |  |  |
| ↳ Silicone (gel)                   | ~$5       | 1     | $5       | [Link](https://item.taobao.com/item.htm?id=613385506355&mi_id=0000a-zPKmCEEIIAXoLoSCAPhHLDQGsKz9Qu52megcVbHH8&spm=tbpc.boughtlist.suborder_itemtitle.1.67152e8dsXBH7k&sku_properties=1627207%3A40667043409) | — |
| ↳ USB Webcam (60Hz)                | ~$9       | 1     | $9       | [Link](https://item.taobao.com/item.htm?ali_refid=a3_430582_1006%3A1123564932%3AH%3AFM5oiNoxVYdxh%2FF9v4%2FouqfwV7TwkF%2Fa%3A4f9a122bf93e826cd4eeabb3de2afbbc&ali_trackid=282_4f9a122bf93e826cd4eeabb3de2afbbc&id=889230929588&mi_id=0000h2fMgvey2lxwczoOpVW59TUU6ysBLu5MHS258iAEdow&mm_sceneid=1_0_53373828_0&skuId=5900744426896&spm=a21n57.1.item.1&utparam=%7B%22aplus_abtest%22%3A%22b14fb1d1bb92b9e4e00b89c11a87f85f%22%7D&xxc=ad_ztc) | — |
| ↳ COB LED Strips (R/G/B)           | ~$0.3     | 1 set | $0.3     | [Link](https://item.taobao.com/item.htm?spm=tbpc.boughtlist.suborder_itemtitle.1.519d2e8dXKNGxh&id=656444201278&mi_id=000060V_wzGN9Fk3qiNdZFEDdfZEXt37d3BgYZ5DgYsmq3w) | — |
| GoPro Hero13                        | —         | 1     | —        | — | — |



## Assembly Steps

### Step 1: 3D Print Main Body

<table align="center">
<tr>
<td align="center" width="320">
<img src="./images/image1.jpeg" width="300"/><br/>
<b>3D Print Main Body</b><br/>
Top view
</td>
<td align="center" width="320">
<img src="./images/image2.jpeg" width="300"/><br/>
<b>3D Print Main Body</b><br/>
Back view
</td>
</tr>
</table>

### Step 2: Install Motor

<table align="center">
<tr>
<td align="center" width="320">
<img src="./images/image3.jpeg" width="300"/><br/>
<b>Install Motor</b><br/>
DM3510 + M3×16 screws ×4
</td>
<td align="center" width="320">
<img src="./images/image4.jpeg" width="300"/><br/>
<b>Install Motor</b><br/>
⚠️ Configure CAN ID before mounting
</td>
</tr>
</table>

### Step 3: Install Gear

<table align="center">
<tr>
<td align="center" width="320">
<img src="./images/image5.jpeg" width="300"/><br/>
<b>Install Gear</b><br/>
Attach gear with M3×4 screws ×3
</td>
<td align="center" width="320">
<img src="./images/image6.jpeg" width="300"/><br/>
<b>Install Gear</b><br/>
Gear mounted
</td>
</tr>
</table>

### Step 4: Install Rack

<table align="center">
<tr>
<td align="center" width="320">
<img src="./images/image7.jpeg" width="300"/><br/>
<b>Install Rack</b><br/>
3D printed rack parts
</td>
<td align="center" width="320">
<img src="./images/image8.jpeg" width="300"/><br/>
<b>Install Rack</b><br/>
Slide to mesh with gear
</td>
</tr>
</table>
<table align="center">
<tr>
<td align="center" width="320">
<img src="./images/image10.jpeg" width="300"/><br/>
<b>Module Gallery</b><br/>
Various configurations: tactile sensor, GoPro mount, different fingertips
</td>
</tr>
</table>
### Step 5: Attach Fingertip(GET Tactile for example)

<table align="center">
<tr>
<td align="center" width="320">
<img src="./images/image9.jpeg" width="300"/><br/>
<b>Attach Fingertip</b><br/>
  Also compatible with ALOHA/UMI fingertips. <br/>M2×6 screws ×2
</td>
<td align="center" width="320">
<img src="./images/image11.jpeg" width="300"/><br/>
<b>Install LED Strips</b><br/>
RGB COB LED strips powered on
</td>
</tr>
</table>

### Step 6: Install Camera

<table align="center">
<tr>
<td align="center" width="320">
<img src="./images/image12.jpeg" width="300"/><br/>
<b>Install Camera</b><br/>
Mount USB camera with M2×8 screws ×4
</td>
<td align="center" width="320">
<img src="./images/image13.jpeg" width="300"/><br/>
<b>Install Camera</b><br/>
Camera dock
</td>
</tr>
</table>

<table align="center">
<tr>
<td align="center" width="320">
<img src="./images/image14.jpeg" width="300"/><br/>
<b>Install Camera</b><br/>
Camera secured
</td>
</tr>
</table>

### Step 8: Complete Tactile Assembly

<table align="center">
<tr>
<td align="center" width="320">
<img src="./images/image15.jpeg" width="300"/><br/>
<b>Tactile Assembly Complete</b><br/>
Side view
</td>
<td align="center" width="320">
<img src="./images/image16.jpeg" width="300"/><br/>
<b>Tactile Assembly Complete</b><br/>
Front view
</td>
</tr>
</table>

---

## Mounting Options

### Glove Mount

<table align="center">
<tr>
<td align="center" width="320">
<img src="./images/image17.jpeg" width="300"/><br/>
<b>Glove Mount</b><br/>
Attach to glove
</td>
<td align="center" width="320">
<img src="./images/image18.jpeg" width="300"/><br/>
<b>Glove Mount</b><br/>
In use
</td>
</tr>
</table>

### Alternative Fingertips

<table align="center">
<tr>
<td align="center" width="320">
<img src="./images/image19.jpeg" width="300"/><br/>
<b>Alternative Fingertips</b><br/>
75% scale UMI finray option
</td>
<td align="center" width="320">
<img src="./images/image20.jpeg" width="300"/><br/>
<b>Alternative Fingertips</b><br/>
Installed view
</td>
</tr>
</table>

### Robot End-Effector Mount

<table align="center">
<tr>
<td align="center" width="320">
<img src="./images/image21.jpeg" width="300"/><br/>
<b>Robot Integration</b><br/>
Mount to robot end-effector
</td>
<td align="center" width="320">
<img src="./images/image22.jpeg" width="300"/><br/>
<b>Robot Integration</b><br/>
Mounted view
</td>
</tr>
</table>
