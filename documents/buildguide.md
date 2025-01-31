# Build guide (ビルドガイド)

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
|-|MAC 8 Conthrough 2.5mm |2|9pin|

## Installation

1. 本体
    1. プレートにスイッチを差し込みます。
    1. スイッチのピンが曲がっていないか、向きが間違っていないか注意して、スイッチのピンをPCBに差し込んでください。
    1. スイッチをPCBにはんだ付けしてください。

1. RP2040
    1. MAC 8 Conthrough 2.5mmのピンの向きに注意して、RP2040 zeroと、MAC 8 Conthrough 2.5mmをはんだ付けしてください。
    1. 本体ユニットにRP2040ユニットを差し込んでください。
    1. PCと接続し、認識されることを確認してください（標準添付のRP2040にはファームウェアは書き込み済みです）

1. 組み立てた基板をケースにビス止めしてください。3Dプリントケースは少し固いですが、ネジを押し込みながら回してください。
1. ラバーの足をケースにとりつけてください。

---

![]()

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
