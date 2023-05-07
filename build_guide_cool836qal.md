## Build guide

## Firmware

###  QMK_FIRMWARE
[Here](https://github.com/telzo2000/cool536/tree/main/firmware)

<br>
[remap](https://remap-keys.app/)

<br>

## Build 1(PCB only)

### 1 Parts check

The cool536 is a PCB that uses both the front and back sides for left and right PCBs.
<br>
The part where the corner is cut diagonally will be the outside of the left and right.
<br>
<br>
cool536は左右のPCBに対して、表裏両面を使用するPCBです。
<br>
角が斜めにカットされている箇所が、左右の外側になります。
<br>

### 2 Diode soldering


Solder the diodes to the back of each of the left and right.
<br>
左右それぞれの裏面にダイオードのハンダ付けをします。
<br>

There are lead type and SMD diodes.
<br>
ダイオードはリードタイプか、SMDがあります。
<br>
Here, we will explain the lead type soldering.
<br>
ここでは、リードタイプのハンダ付けの説明をします。
<br>
However, those who adopt the choc switch should use SMD diodes.
<br>
ただし、chocスイッチを採用する人は、SMDのダイオードを使用してください。
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

### 3 Soldering switch sockets


Solder the switch sockets on the back side.
<br>
裏面にスイッチソケットのハンダ付けをします。
<br>
cool536 is compatible with both choc and cherry MX switches.
<br>
cool536はchocスイッチとcherryMXスイッチの両方に対応しています。
<br>
Both can be installed.
<br>
両方を取り付けることが可能です。
<br>
Here, solder the cherryMX switch.
<br>
ここでは、cherryMXスイッチのハンダ付けを行います。
<br>
Place the switch socket so that the letters MX are hidden.
<br>
MXという文字が隠れるように、スイッチソケットを乗せてください。
<br>
That is the correct switch socket orientation.
<br>
それが正しいスイッチソケットの向きになります。
<br>
When using a choc switch, place the switch socket so that the letters choc are hidden.
<br>
chocスイッチの時は、chocという文字が隠れるように、スイッチソケットを乗せてください。
<br>

Apply solder to both pads.
<br>
両方のパッドにハンダを盛ります。
<br>
Place the switch socket and fix it with a warm soldering iron while melting the solder.
<br>
スイッチソケットを乗せて、温めたハンダゴテで、ハンダを溶かしながら、固定します。
<br>
You can make it easier by working while holding it with tweezers.
<br>
ピンセットで押さえながら、作業をすると楽にできます。
<br>

[８倍速　Switch socketハンダ付け動画](https://youtu.be/E__mHvmIXQo)

<br><br>

### 4 Soldering reset switch & TRRS jack 

Insert the reset switch on the surface.
<br>
表面にリセットスイッチを挿しこみます。
<br>
Solder the legs of the reset switch from the back.
<br>
裏面からリセットスイッチの足をハンダ付けします。
<br>
Solder the TRRS jack in the same way near the reset switch.
<br>
TRRSジャックは、リセットスイッチの近くに同じようにハンダ付けします。
<br>
Insert the left and right TRRS jacks from the front side and solder from the back side.
<br>
TRRSジャックは左右１箇所ずつ、表面から差し込み、裏面からはんだ付けをしてください。
<br>

[８倍速　Reset switch,TRRS jackハンダ付け動画](https://youtu.be/3gEbExaOAv4)

<br><br>


### 5　Pro micro 

cool536 requires pro micro on each side.
<br>
cool536は左右それぞれにpro microが必要となります。
<br>

Use the conthrough to fix the pro micro with the side with the parts facing down.
<br>
pro microの部品のある面を下向きに、コンスルーを使い、固定してください。
<br>


Pay attention to the orientation of the conthrough.
<br>
コンスルーの向きに注意してください。
<br>




<br>

