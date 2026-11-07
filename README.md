# Pico2_RP2035_Kodera2t_TinyBasicPlus
Kodera2t TinyBasicPlusシリーズの中で、
これ↓だけが上手く【Pico2】に入る【Pico】には入らない
https://github.com/kodera2t/tinyBASIC_OLED/blob/master/ATMega328P%2BColorLCD/Ada_ATMega328_LCD.ino
まず先にボードマネージャで追加ボードで【Raspberry Pi】を選びインストール
【File】→【Preference】でRaspberryのJSONファイルをインストール
その後くらいに
【一回目】はuf2接続(BootSelボタンを押しながらWindowsパソコンとUSB接続)で書込み→必ず失敗する
【二回目】はCOM接続で再び書込み→そうすると成功する
<img width="946" height="697" alt="IMG_8358" src="https://github.com/user-attachments/assets/d385f05d-b1ab-422e-be0f-a9ce1f7c1624" />
