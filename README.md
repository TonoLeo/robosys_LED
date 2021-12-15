# robosys_LED
2020 robot system homework 1

---
このリポジトリは2021年度ロボットシステム学課題1のデバイスドライバーです。
<br>
1の入力時に点灯し、0の入力時に消灯することができます。

---
## 動作環境

### OS : ubuntu 20.04 server
### Raspberry Pi 4 Model B
---
## 使用したもの

・Raspberry Pi4 model B x1

・LED x1

・ブレッドボード x1

・ジャンパワイヤ x4

・抵抗 x1

---

## 回路の配置

![image](https://user-images.githubusercontent.com/91268353/146122171-1f3777f0-fbb3-4e24-9212-8780cbea8ef8.png)

---
## インストール方法

使用したいディレクトリ内で以下のコマンドを実行してください。

```sh
$ git clone https://github.com/TonoLeo/robosys_LED.git
$ cd robosys_LED
$ make
```
実行後の後処理（ディレクトリ内のファイル）

```sh
$ make clean
```
---
## ライセンス
[GNU General Public License v3.0](https://github.com/TonoLeo/robosys_LED/blob/main/COPYING)

