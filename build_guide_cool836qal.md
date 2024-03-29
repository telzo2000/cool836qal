## Build guide


## Firmware


###  QMK_FIRMWARE


参考<br>

https://github.com/telzo2000/Hello_keyboard/blob/main/readme_about_firmware.md

[Here](https://github.com/telzo2000/cool836qal/tree/main/firmware)

<br>

[remap](https://remap-keys.app/catalog/FEmXx8GyuKYuJ5JSfcQG)

<br>

## Build 1

### 1 Diode soldering


Solder the diodes to the back of PCB.
<br>
PCBの裏面にダイオードのハンダ付けをします。
<br>
![](img/img00002.jpg)
There are lead type and SMD diodes.
<br>
ダイオードはリードタイプか、SMDがあります。
<br>
Here, we will explain the lead type soldering.
<br>
ここでは、リードタイプのハンダ付けの説明をします。
<br>


Use a lead bender to bend the legs of the diode.
<br>
リードベンダーを使い、ダイオードの足を曲げます。
<br>
![](img/img00003.jpg)
![](img/img00004.jpg)

Insert the diode into the board.
<br>
ダイオードを基板に挿しこみます。
<br>

Please pay attention to the orientation of the diode.
<br>
ダイオードの向きに注意してください。
<br>


Secure the diode with masking tape, then face up.
<br>
マスキングテープでダイオードを固定してから、表面を上にします。
<br>
Solder the protruding legs.
<br>
はみ出ている足部分に、ハンダ付けをします。
![](img/img00005.jpg)
<br>
After soldering, use nippers to cut off the protruding legs.
<br>
はんだ付けが終わったら、はみ出ている足をニッパーで切り取ってください。
<br>
![](img/img00006.jpg)
![](img/img00007.jpg)

[８倍速　Diodeハンダ付け動画](https://youtu.be/Yaodh2-XxV4)

<br>
<br>

### 2 Soldering switch sockets


Solder the switch sockets on the back side.
<br>
裏面にスイッチソケットのハンダ付けをします。
<br>
![](img/img00008.jpg)
![](img/img00009.jpg)
![](img/img00010.jpg)

[８倍速　Switch socketハンダ付け動画](https://youtu.be/E__mHvmIXQo)

<br><br>

### 3　Soldering RP-2040Zero  

The side on which the RP-2040Zero components are mounted is the front side, and the opposite side is the back side.
<br>
RP-2040Zeroの部品実装されている面を表面とし、反対側を裏面とします。
<br>
Place the back side of the PCB and the back side of the RP-2040Zero facing each other and solder the respective terminals.
<br>
PCBの裏面とRP-2040Zeroの裏面が向かい合うようにして置き、それぞれの端子をハンダ付けします。
<br>
![](img/img00013.jpg)
![](img/img00014.jpg)
![](img/img00015.jpg)
<br>

### 4 Instorlling QMK＿Firmware

Install QMK_Firmware from your PC to RP-2040Zero.
<br>
QMK_FirmwareをPCからRP-2040Zeroにインストールしてください。
<br>
<br>
① Download https://github.com/telzo2000/cool836qal/blob/main/firmware/cool836qal_via.uf2 to your PC.
<br>
①https://github.com/telzo2000/cool836qal/blob/main/firmware/cool836qal_via.uf2 をPCにダウンロードしておく。

<br><br>
② Connect the PC and RP-2040Zero with a USB cable.
<br>
②PCとRP-2040ZeroをUSBケーブルで繋ぐ。
<br><br>
③Press the reset button while pressing the boost button on the RP-2040Zero.
<br>
③RP-2040Zeroのboostボタン押しながら、resetボタンを押す。
<br><br>
④Since there is a folder of RP-2040Zero on the PC screen, drag and drop the downloaded cool836qal.uf2 there.
<br>
④PC画面にはRP-2040Zeroのフォルダがあるので、そこに、ダウンロードしたcool836qal.uf2をドラッグアンドドロップする。
<br><br>

⑤Check if it is recognized by connecting to remap. Edit the keymap accordingly.
<br>
⑤remapに繋いで認識するかどうか確認する。合わせてキーマップの編集をする。

### Build 2(case)

### 1 Case


I will explain using a case printed by stereolithography of black resin ordered from JLCPCB. The procedure is basically the same for cases printed with Ankemake M5 for home use.
<br>
JLCPCBに発注したブラックレジンの光造形で印刷されたケースを使って説明します。家庭用AnkemakeM5で印刷したケースでも作業の手順は、基本的に同じです。
<br>
<br>
Fix the [magnets](https://www.amazon.co.jp/gp/product/B09BC46FQX/ref=ppx_yo_dt_b_asin_title_o00_s00?ie=UTF8&th=1) to the five dents inside the case with an adhesive or the like. There are 5 in the top case and 5 in the bottom case for a total of 10.Please pay attention to the polarity of the magnet. Make sure the top case and bottom case are magnetically attached.
<br>
ケースの内側にある５つの凹みに[磁石](https://www.amazon.co.jp/gp/product/B09BC46FQX/ref=ppx_yo_dt_b_asin_title_o00_s00?ie=UTF8&th=1)を接着剤などで固定します。トップケースに５箇所、ボトムケースに５箇所の合計10箇所です。
極性に注意してください。トップケースとボトムケースが磁力で着くようにしてください。
<br>
![](img/img00019.jpg)


As shown in the image below, attach rubber O-rings to the four protrusions on the bottom case. This makes it a gasket mount. You can do without the O-ring, but the PCB may move up and down inside the case.
<br>
下の画像のように、ボトムケースに4箇所の凸部にゴムのO-ringを装着します。これによりガスケットマウントとなります。O-ringはなくても大丈夫ですが、ケース内で、PCBが上下に動く可能性があります。
<br>
![](img/img00018.jpg)

The O-ring in the image is [this product](https://www.amazon.co.jp/gp/product/B07G4SM5SM/ref=ppx_yo_dt_b_asin_title_o03_s00?ie=UTF8&psc=1).
<br>
画像のO-ringは[この商品](https://www.amazon.co.jp/gp/product/B07G4SM5SM/ref=ppx_yo_dt_b_asin_title_o03_s00?ie=UTF8&psc=1)です。
<br>
<br>
Place the hole in the switch plate on the O-ring. And it is completed by covering the top case.
<br>
スイッチプレートの穴をO-ringに載せます。そして、トップケースを被せて完成です。
<br>
![](img/img00017.jpg)
![](img/img00016.jpg)

Welcome to the world of 36 keys.
<br>
36キーの世界へようこそ。
<br>
