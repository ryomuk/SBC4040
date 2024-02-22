# SBC4040
Single Board Computer using Intel 4040

This document is written mostly in Japanese.
If necessary, please use a translation service such as DeepL (I recommend this) or Google.

![](images/title.jpg)

## 概要
CPUにIntel 4040を採用したシングルボードコンピュータです．4004実験用ボードをベースにして作りました．4004版と完全上位互換なはず．4040の代わりに4004も載せられるようにしてあります．(絶対に同時には搭載しないこと!)

4040にすることによって追加された機能は下記の通りです．

- ROM領域が4KBから8KBに増加
- サブルーチンコールが3段から7段に増加
- PMR命令により，プログラム領域のRAMを直接読めるようになったはず(未確認)
- 割り込み機能
- ステップ実行は使い道が無さそうなので端子だけ出して未実装

## ToDo
- 割り込み機能の動作確認
- 拡張ROM領域(CMROM1)の動作確認
- PMR命令の動作確認
- モニタプログラム，VTL, 8080エミュレータ等を4040用にリライト

## ブログ
関連する情報が書いてあるかも．
- [Intel 4004 関連記事の目次@ブログの練習](https://blog.goo.ne.jp/tk-80/e/3fa1e2972737c7b7d1b83f4e7bd648a2)

## 動画
Youtubeで関連動画を公開しています．
- https://www.youtube.com/@ryomukai/videos

## 参考にした文献，サイト
### データシート
- http://www.bitsavers.org/components/intel/
- https://www.intel-vintage.info/intelmcs.htm

### ソフトウェア開発環境
- [The Macroassembler AS](http://john.ccac.rwth-aachen.de:8000/as/)

## 更新履歴
- 2024/2/22: 初版公開
