## Build guide


## Firmware


###  QMK_FIRMWARE

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
<br>
After soldering, use nippers to cut off the protruding legs.
<br>
はんだ付けが終わったら、はみ出ている足をニッパーで切り取ってください。
<br>

[８倍速　Diodeハンダ付け動画](https://youtu.be/Yaodh2-XxV4)

<br>
<br>

### 2 Soldering switch sockets


Solder the switch sockets on the back side.
<br>
裏面にスイッチソケットのハンダ付けをします。
<br>

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


<br>

<br>

