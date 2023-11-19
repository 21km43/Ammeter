# Ammeter
[INA226](https://datasheet.lcsc.com/lcsc/1809192224_Texas-Instruments-INA226AIDGSR_C49851.pdf)を利用した電流計。主にマイコンの消費電流の測定に利用する。  
特徴は以下の通り。
* 入力電圧: 0~36V
* シャント抵抗値: 100mΩ
* 分解能: 25µA
* 電流上限: 819.2mA

ヒューズは入れていないので過電流には注意すること。  
基板CADは[KiCAD](kicad.org)。また、ガーバーファイルはproduction以下に配置した。JLCPCBにアップロードすればすぐに発注可能。

## LICENSE
[MIT LICENSE](/LICENSE)
