# Build guide (ビルドガイド)

![20250131_IMGP8951](https://github.com/user-attachments/assets/80553024-3cb0-407f-add8-c392bd1af162)

## The kit includes (キット内容)

|no|name|qty|description|
|:--|:--|:--|:--|
|-|Numatray PCB|1|Macropad PCB|
|-|Numatray Plate|1|FR4 Switch Plate|
|-|Numatray Case|1||
|-|M2 4mm|4||
|-|Rubber Feet|4||
|-|MX Switches|4|As you like|
|-|RP2040 zero|1||
|-|MAC 8 Conthrough 2.5mm (コンスルー)|2|9pin|

## Installation

1. 本体
    1. プレートにスイッチを差し込みます。
    1. スイッチのピンが曲がっていないか、向きが間違っていないか注意して、スイッチのピンをPCBに差し込んでください。
    1. スイッチをPCBにはんだ付けしてください。

1. RP2040
    1. MAC 8 Conthrough 2.5mmのピンの向きに注意して、RP2040 zeroと、MAC 8 Conthrough 2.5mmをはんだ付けしてください。リセットボタンとブートボタンの反対側に取り付けてください。（写真参照）
    1. 本体ユニットにRP2040ユニットを差し込んでください。
    1. PCと接続し、認識されることを確認してください（標準添付のRP2040にはファームウェアは書き込み済みです）

1. 組み立てた基板をケースにビス止めしてください。3Dプリントケースは少し固いですが、ネジを押し込みながら回してください。
1. ラバーの足をケースにとりつけてください。

### photos

コンスルーにはピンの取り付け向きがあります。  
写真の赤枠ようにピンの窓が両方こちらに向くようにしてとりつけてください。
![20250131_IMGP8942](https://github.com/user-attachments/assets/617ca130-ae88-441d-81e0-91b44d70db2b)  

赤枠の各ピンをはんだ付けしてください。  
![20250131_IMGP8954](https://github.com/user-attachments/assets/735e2e16-0843-4ca2-9f01-b70e3b033f78)

写真のようにスイッチと基板を取り付けてください。スイッチの脚と基板穴の関係上少しキツメに作ってあるのでグッと押し込んでください。  
基板に露出したピンがある赤丸部をはんだづけしてください。  
![20250131_IMGP8957](https://github.com/user-attachments/assets/901b7a4d-226c-4799-8519-bcd31a74295b)

コンスルーをはんだ付けしたRP2040と基板は写真ような方向で取り付けてください。  
基板とコンスルーははんだ付けしなくても良いです。  
![20250131_IMGP8944](https://github.com/user-attachments/assets/29240d6c-6221-449c-b78f-6bee6bfcbcd6)  

EC11/EC10シリーズのロータリーエンコーダーも取り付け可能です
![20250131_IMGP8948](https://github.com/user-attachments/assets/3a4d7a38-4644-4fd5-996a-e47d97bcc194)  

ケースのネジ穴と基板のネジ穴に注意してねじ止めしてください。  
![20250131_IMGP8953](https://github.com/user-attachments/assets/f7bf930a-1057-4b6b-9930-ffc9466ca67a)

---

## Edit the keymap

Remap-compatible firmware has already been written to this PCB.  
You can change the keymap by accessing the following URL.  

以下のURLにアクセスし、キーマップを変更出来ます。  

[remap](https://remap-keys.app/)

## Firmware binary file

You can update the firmware by accessing the following URL.  
Usually it will not be necessary to do so.  

以下のURLにアクセスし、最新のファームウェアをアップデート出来ます。通常はそれを行う必要はないでしょう。  

[firmware](https://github.com/marksard/qmk_firmware_hex/releases)

## Bootloader Mode

### Method 1 (方法その1)

一番左のキーを押下しながら、PCと接続します。  


### Method 2 (方法その2)

Connect the keyboard to the PC and operate the tact switch attached to the keyboard in the following order:

1. Hold down the BOOT button and press the RESET button.  
2. Release the RESET button, then release the BOOT button.  

ＰＣにキーボードを接続し、キーボードに取り付けたタクトスイッチを以下の順に操作します。

1. BOOTボタンを押したまま、RESETボタンを押します。
2. RESETボタンを離してから、BOOTボタンを離します。

## If you need help

Twitter: @marksard
Discord: marksard
