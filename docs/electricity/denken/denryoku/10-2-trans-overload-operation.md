# 【電験3種・電力】変圧器の過負荷運転の試験問題対策

## 変圧器の過負荷運転

変圧器の過負荷運転とは、変圧器の定格容量(kVA)を上回る負荷をかけて運転すること。
他の変圧器が故障したときに、不足分を一時的に補う場合などやむを得ないときに用いられる。
過負荷状態になると、鉄損や銅損が増え、変圧器の温度が上昇し、絶縁物や絶縁油等、変圧器の構成部品の劣化を進行させます。
そのため、変圧器の寿命が短縮します。

## 【例題1】過負荷運転率の計算


【*問題*】

以下の仕様の「三相変圧器」が3台ある配電用変電所(総負荷55MW)がある。
変圧器1台が故障し、残り2台の変圧器で定格容量の120％の過負荷運転を行い、不足分を他の変電所に切り換えて故障発生前と同じ電力を供給したい。
このとき、他の変電所に故障発生前の負荷の何％を直ちに切り換える必要があるか。

残りの健全な変圧器は，変圧器故障時に過負荷運転をすることとし，

(三相変圧器の仕様)
定格容量:20[MV⋅A]
力率:常に95％ （遅れで変化しないものとする)

【*解答*】

- 残り2台の過負荷運転時の容量Sは

$S=20\times 1.2 \times 2=48$[MV⋅A]

- 負荷の皮相電力$S_L$[MV⋅A] は力率が95％（遅れ）より

$S_L=\frac{55}{0.95}=57.89$[MV⋅A]

※P=Scosθ

P:有効電力[kW]、S:皮相電力[kVA]、cosθ:力率[%]

- よって、他の変電所で負担する容量の割合は

$\frac{57.89-48}{57.89}=17.1[％]$

## 【例題2】変圧器の並行運転時の過負荷容量

【*問題*】

一次側定格電圧と二次側定格電圧がそれぞれ等しい、以下仕様の変圧器AとBを並行運転し、 6000 kV⋅Aの負荷に供給する場合、過負荷となる変圧器とその変圧器の過負荷運転状態[％] (当該変圧器が負担する負荷の大きさをその定格容量に対する百分率で表した値) を計算せよ。

[電源]---[変圧器A]---[負荷]
            |                   |
            --[変圧器B]--


(変圧器Aの仕様)
定格容量:$S_A=5000$[kV⋅A]
パーセントインピーダンス:％Zta=9.0％(自己容量ベース)

(変圧器Bの仕様)
定格容量:$S_A=1500$[kV⋅A]
パーセントインピーダンス:％Ztb=7.5％(自己容量ベース)

【*解答*】

- 変圧器Bの％ZBを変圧器Aと同じ5000kV⋅Aベースの％′Bに変換する。

$\% Z'B=\frac{S_A}{S_B}\% Z = \frac{5000}{1500}7.5=25$

- よって、変圧器Aが負担する容量$P_A$と、変圧器Bが負担する容量$P_B$は以下のようになる。

$P_A=6000\cdot \frac{\% Z'_B}{\%Z_A+\%Z'_B}=6000\cdot \frac{25}{9+25}=4412 [kVA]$

$P_B=6000\cdot \frac{\% Z_A}{\%Z_A+\%Z'_B}=6000\cdot \frac{9}{9+25}=1588 [kVA]$

- よって、変圧器Bが過負荷となることがわかる。その過負荷運転状態[％] は「1588/1500=1.059」より105.9%となる。

## 【例題3】過負荷運転時の無効電力と、過負荷運転回避に必要な電力用コンデンサ容量

【*問題*】

定格容量 750 [kV⋅A] の三相変圧器に遅れ力率 0.9 の三相負荷 500 [kW] が接続されている。
この三相変圧器に新たに遅れ力率 0.8 の三相負荷 200 [kW] を接続する。
このとき、
①負荷を追加した後の無効電力 [kvar] 
② この変圧器の過負荷運転を回避するために、変圧器の二次側に必要な最小の電力用コンデンサ容量 [kvar] の値 
を求めよ。

【*解答①*】

- 元々接続されていた負荷1(力率0.9)のsinθ1、新たに接続した負荷2(力率0.8)のsinθ2を計算する。

$sin\theta_1=\sqrt{1-cos^2\theta_1}=\sqrt{1-0.9^2}=0.4359$

$sin\theta_1=\sqrt{1-cos^2\theta_1}=\sqrt{1-0.8^2}=0.6$

- よって、負荷1、2の無効電力の大きさQ1、Q2を計算できる。

$Q_1=\frac{P_1}{cos\theta_1}sin\theta_1=242.2[kvar]$

$Q_2=\frac{P_1}{cos\theta_2}sin\theta_2=150[kvar]$

$Q_1+Q_2=242.2+150=392.2[kvar]$


【*解答②*】

- 負荷2接続後、変圧器が過負荷とならない最大無効電力Qdは以下のとおり。

$Q_d=\sqrt{S^2-(P_1+P_2)^2}=296.3$[kvar]


- 過負荷を回避するために必要な電力用コンデンサ容量の最小値Qcは

$Q_c=Q_1+Q_2-Q_d=122.9$[kvar]


## 参考動画

*初心者向け電験三種・電力・23・変圧器の負荷分担【超簡単に学ぶ！】第三種電気主任技術者*
 [![](https://img.youtube.com/vi/-CJ1sk7Zuds/0.jpg)](https://www.youtube.com/watch?v=-CJ1sk7Zuds)


## 関連リンク

- [電験3種試験対策トップページ](../index.md)
- [トップページ](../../../index.md)