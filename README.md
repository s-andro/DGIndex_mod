﻿# DGIndex_mod
a fork from maki's MPEG2DecPlus 0.1.1


mod by 299792458m
190309
速度調整
(SSE2でも300MB/s位になった)

190308
GUIで落ちることがあるエンバグ修正

190303
インデックス生成処理に必要以上に時間がかかってるんじゃね？と思ったので、
不必要と思われるd2v生成処理の無駄を省いて速度向上
(自分の環境ではAVX2時150MB/s→300MB/s、SSE2で150→240位にUP)



・コマンドラインからのd2v生成以外のデバッグをしていない
  (AAC抽出処理もいくつかのバイナリが一致することを確認しただけ)
・その他の影響確認をちゃんとしてない
・あまりする気もない
のでexperimental

