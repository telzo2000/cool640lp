# Build guide

## Build 1

### 1 Diode soldering

Solder the diodes to the back of PCB.
<br>
PCBの裏面にダイオードのハンダ付けをします。
<br>
The diode is compatible with SMD.
<br>
ダイオードは、SMDに対応しています。
<br>
Diodes have polarity, so be careful about the direction in which they are installed.
<br>
ダイオードには極性がありますので、取り付ける向きに注意してください。
<br>

[ダイオード（SMD)のはんだ付けの動画](https://youtu.be/ODk16bd4XkA)


### 2 Switch socket soldering

Solder the switch sockets on the back side.
<br>
裏面にスイッチソケットのハンダ付けをします。
<br>

[８倍速　Switch socketハンダ付け動画](https://youtu.be/E__mHvmIXQo)


### 3 Reset switch soldering

Insert the reset switch from the back of the PCB and solder the exposed part.
<br>
リセットスイッチをPCBの裏面から差し込んで、表面に出た部分をはんだ付けしてください。
<br>


[リセットスイッチのはんだ付けの作業動画](https://youtu.be/Pl24Exfh8b8)


### 4 Battery parts soldering(Bluetooth option)

Solder the slide switch first.
<br>
最初にスライドスッチをはんだ付けします。
<br>

Insert the switch from the back of the PCB with the switch knob facing outward.
<br>
スイッチのつまみが外側に向くようにして、PCBの裏面から差し込みます。

After temporarily fixing it with masking tape, etc., solder the exposed part of the PCB.
<br>
マスキングテープなどで仮固定をしてから、PCBの表面に出た部分をはんだ付けします。
<br>

[スライドスイッチのはんだ付けの作業動画](https://youtu.be/5nkRklibay4)

<br>
Next, solder the capacitor.
<br>
次に、コンデンサをはんだ付けします。
<br>
<br>
First, apply solder to only one side of the two pads.
<br>
最初に、２つあるパッドの片側だけに、はんだを盛り付けます。
<br>
Place the capacitor and fix it by melting the solder.
<br>
コンデンサを置き、もったはんだを溶かしながら、固定します。
<br>
Solder the capacitor, applying solder to the remaining pads.
<br>
残りのパッドにはんだを盛りながら、コンデンサをはんだ付けします。
Finally, attach the battery holder.
<br>

[コンデンサのはんだ付け作業の動画](https://youtu.be/8CFiDMtg21s)

最後に、電池ホルダを取り付けます。
<br>
Insert it from the back side of the PCB and solder the front side. Using masking tape for temporary fixation will make the work easier.
<br>
PCBの裏面から差し込んで、表面をはんだ付けします。仮固定にマスキングテープを使うと作業が簡単になります。
<br>

[電池ホルダのはんだ付けの作業動画](https://youtu.be/ltA8kcLqso4)



### 5a BLE MIcro Pro
Please prepare two con-through (12 pin 3.5mm) instead of the pin header included with BLE Micro Pro.
<br>
ブレマイクロプロ付属のピンヘッダではなく、コンスルー（12ピン 3.5mm）を２つ用意してください。

![](img/img00028.jpg)

There is a small hole in the side of the conthru. Insert it into the PCB, being careful to orient the holes the same way.
<br>
コンスルーの側面に小さい穴が開いています。穴を同じ向きになるよう注意して、PCBに差し込んでください。

![](img/img00027.jpg)

![](img/img00026.jpg)
Insert the BLE Micro Pro into the con-through so that the side with the parts on it faces the PCB. If the BLE Micro Pro easily comes off from the con-through, we recommend soldering. However, due to the structure of the bottom plate of the 3D printer, I think it will be difficult to remove, so no soldering is necessary.
<br>
 BLE Micro Proの部品が載っている方がPCBに面するように、コンスルーに差し込んでください。もし、 BLE Micro Proがコンスルーから外れやすいときははんだ付けをお勧めします。ただし、3Dプリンタのボトムプレートの構造上、外れにくいと思うので、はんだ付け不要です。
<br>
When using a 12-pin con-through, insert it into the 12 holes counting from the USB side of the BLE Micro Pro.
<br>
コンスルー12ピンを使用するとき、BLE Micro ProのUSB側から数えて12箇所分の穴に差し込んでください。
<br>


### 5b Pro Micro
If you are not interested in wireless connectivity, you can keep the price low by using the pro micro.
<br>
もしあなたが無線接続に興味がないのであれば、pro microを使用することで価格を低くすることができます。
<br><br>
Please prepare two con-through (12 pin 3.5mm) instead of the pin header included with pro micro.
<br>
pro micro付属のピンヘッダではなく、コンスルー（12ピン 3.5mm）を２つ用意してください。
<br>


There is a small hole in the side of the conthru. Insert it into the PCB, being careful to orient the holes the same way.
<br>
コンスルーの側面に小さい穴が開いています。穴を同じ向きになるよう注意して、PCBに差し込んでください。

Insert the pro micro into the con-through so that the side with the parts on it faces the PCB. If the pro micro easily comes off from the console, we recommend soldering. However, due to the structure of the bottom plate of the 3D printer, I think it will be difficult to remove, so no soldering is necessary.
<br>
pro microの部品が載っている方がPCBに面するように、コンスルーに差し込んでください。もし、pro microがコンスルーから外れやすいときははんだ付けをお勧めします。ただし、3Dプリンタのボトムプレートの構造上、外れにくいと思うので、はんだ付け不要です。
<br>

Note
<br>
Regarding the PCB of ver.1.0, please correct the part in the image below.
<br>
ver.1.0のPCBについて、次の画像の部分を修正してください。
<br>

![](img/img00006.jpg)

### 6a Install firmware （BLE Micro Pro）


Here is an [article](https://sizu.me/m_ki/posts/01s8uea4u7x8) on how to do it.
<br>
ここにやり方の[記事](https://sizu.me/m_ki/posts/01s8uea4u7x8)があります。
<br>


### 6bInstall firmware （pro micro）

There is a hex file [here](https://github.com/telzo2000/cool640lp/tree/main/firmware). Please install it using QMK ToolBox.
<br>

[ここ](https://github.com/telzo2000/cool640lp/tree/main/firmware)にhexファイルがあります。それを、QMK ToolBoxを使って、インストールしてください。


[QMK ToolBox](https://qmk.fm/toolbox)

キーマップ編集サイト
[Vial](https://get.vial.today/)

### 7 Fix the switch plate 

![](img/img00002.jpg)

Insert the M2 screws (4mm) into the 3D printed switch plate and the PCB in that order, and secure them with M2 spacers (3mm) from the bottom of the PCB.
<br>
3Dプリントのスイッチプレート、PCBの順でM2ネジ（4mm）の順で差し込み、PCB下面からM2スペーサー3mm）で固定します。

<br><br>


### 8 Insert the key switch

Insert the key switch from the switch plate side.
<br>
スイッチプレート側からキースイッチを差し込んでいきます。
<br>

![](img/img00005.jpg)

<br>


### 9 Fix the bottom case with screws

Secure the spacer fixed to the bottom plate and PCB with four M2 screws (4mm).
<br>
ボトムプレートとPCBに固定したスペーサーをM2ネジ（4mm）４本で固定します。


### 11 Complete

Attach your favorite keycaps and you're done.
<br>
お気に入りのキーキャップをつけて完成です。
<br>
![](img/img00004.jpg)


<br>
Welcome to the world of the best keyboards.
<br>
最高のキーボードの世界にようこそ。
<br>

![](img/img00003.jpg)