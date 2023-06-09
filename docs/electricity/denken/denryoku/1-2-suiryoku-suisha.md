# 水力発電所の水車の種類・付帯設備

## 水車の種類 

![水車の種類](./assets/01_suiryoku2_suisha.png "水車の種類")

出典:資源エネルギー庁 https://www.enecho.meti.go.jp/category/electricity_and_gas/electric/hydroelectric/mechanism/waterwheel/


主な水車の種類は以下のとおり。

- *衝動水車*
    - 水をノズルから噴出させ、水の位置エネルギーを**運動エネルギー**に変換し、流水を**ランナ**に作用させ、その反動力により水車が回転。
    - **速度水頭を利用**。
    - (例)**ペ*ルトン水車**、**クロスフロー水車**など
- *反動水車*
    - 水の位置エネルギーを**圧力エネルギー**に変換し、流水を**ランナ**に作用させる構造。
    - **圧力水頭**を利用して発電。
    - (例)**フランシス水車**、**プロペラ水車**、斜流水車など
- *ペルトン水車*(衝動水車の1つ)	
    - 水をノズルから噴出させ、その勢いで水車の先端についたバケットを回転させる。
    - ノズルから噴出する水の量を調節して、出力を簡単に調整できる。
    - **高落差(200m以上)**で**流量の比較的少ない**地点に用いられ、**比速度は小さい**。
    - 水圧管路に導かれた流水が、ノズルから噴射されてランナバケットに当たり、このときの衝動力でランナが回転する水車である。
- *フランシス水車*(反動水車の1つ)
    - 水を取り込むケーシング(渦形室)の中に羽根車（ランナー）を設置し、そこを流れる水の圧力により回転させる(ランナに流入した水がランナを出るときに軸方向に向きを変える)。最も一般的な水車。
    - **中高落差用(40m～500m)**に使われている。
    - 同一出力のフランシス水車を比較すると、**落差が高い地点**に適用する水車の方が低い地点に適用するものより**比速度が小さく**、**ランナの形状が扁平**になる。
- *プロペラ水車*
    - ランナを通過する流水が**軸方向**で、ランナには扇風機のような羽根がついている。**流量が多く低落差**の発電所で使用される。近年の地球温暖化防止策として、農業用水・上下水道・工業用水など少水量と低落差での発電が注目されており，代表的なものに**クロスフロー水車**がある。
- *カプラン水車*
    - プロペラ水車の**羽根を可動**できるようにしたもの。**流量の変化**に応じて**羽根の角度**を変えて効率がよい運転ができる。

## 水車の付帯設備

- *調速機(ガバナー)*
    - 水車(電動機)の**回転速度(周波数)を一定**に調整。
    - 調速機で**周波数を一定**に保つ運転を「**ガバナフリー運転**」といい、周波数が上昇したら水量を減らして周波数を一定に保つ(減少したら水量を増やす)。
    - 発電機が系統に並列するまでは**水車の回転速度を制御**し、**並列後は出力を調整**し、事故時には**回転速度の異常な上昇を防止**する。
    - 調速機は回転速度を検出し、既定値を保つようにペルトン水車は**ニードル弁**、フランシス水車は**ガイドベーンの開度**を調整する。
- *自動電圧調整器*
    - 水車発電機の出力電圧の大きさを一定に保持する装置。
- *ガイドベーン(案内羽根)*
    - 開度でランナに流入する水の流量を変化させ、水車の出力を調整する。
- *吸出し管*
    - **フランシス水車**で用いられ、水車ランナと放水面までの落差を有効に利用し、**水車の出力を増加**する効果がある(衝動水車である**ペルトン水車には吸出し管がない**)。
- 水車発電機
    - 突極形で回転界磁形の三相同期発電機が主に用いられている。落差を有効に利用するために、水車を発電機の下方に直結した立軸形にすることも多い。
- 速度調定率(暗記不要)
    - $R=\frac{\frac{N_2-N_1}{N_n}}{\frac{P_2-P_1}{P_n}\times 100}$ 
    - 回転速度(変化前) $N_1[min-1]$ 、回転速度(変化後) $N_2[min-1]$、回転速度(定格) $N_n[min-1]$、出力(変化前) $P_1[kW]$、出力(変化後) $P_2[kW]$、出力(定格) $P_n[kW]$
    - 速度調定率の計算式は過去の出題では事前に提示されている(暗記不要)
- *比速度*
    - 水車の形状と運転状態(水車内の流れの状態)を**相似に保って**大きさを小さくし、**単位落差(1m)で単位出力(1kW)を発生させるときの回転速度**。
    - 水車では、ランナの形状や特性を表すものとして「比速度」が指標に用いられる。
    - 水車の**種類**に応じた適切な比速度の範囲と、その比速度に適した有効落差が存在する。
    - 一般的に、ペルトン水車の比速度は、フランシス水車の比速度より小さい。
    - 比速度の大きな水車を大きな落差で使用し、吸出し管を用いると、放水速度が大きくなって、キャビテーションが生じやすくなる。
    - 比速度が大きいほど、**発電機や水車を小型化することが可能**となるが、**流水とランナの相対速度が増大**し、効率低下やキャビテーション発生、振動・騒音などの問題が生じる可能性がある。水車の特性を推測する指標として用いられる。
    - 水車の定格回転数 $n[min^{−1}]$、出力$P[kW]$ 、有効落差 $H[m]$ のとき、比速度 $ns[m\cdot kW]$ は以下の式で計算される。
        - $n_s = n\frac{P^{\frac{1}{2}}}{H^{\frac{5}{4}}}$ 
- *キャビテーション*
    - 運転中の水車の流水経路中のある点で**圧力が低下**し、そのときの**最低流速以下**になると、その部分の水は**蒸発**して流水中に**微細な気泡**が発生する。その気泡が**圧力の高い箇所**に到達すると押し潰され**消滅**する現象。
    - 水車にキャビテーションが発生すると、ランナやガイドベーンの壊食、効率の低下、振動や騒音の増大など水車に有害な現象が現れる。
    - キャビテーションの防止対策としては、「吸出し管の高さを高くする」「ランナの形状を見直す」「水車の比速度を下げる」「壊食に対し、強い材料を使用する」などがある。
- *突極機・鉄機械(水力)*
    - 水車発電機の回転速度は約 $100[min^{−1}]$ ～ $1200[min^{−1}]$ とタービン発電機より**低速で**あるため、商用周波数 $50/60[Hz]$ を発生させるために磁極を多くとれる「**突極機**」を用いる。
    - **大形機**では据付面積が小さく、落差を有効に使用できる**立軸形**が用いられることが多い。
    - タービン発電機に比べ、**直径が大きく軸方向の長さが短い**。
    - 電力系統の安定度の面及び負荷遮断時の速度変動を抑える点から、発電機の経済設計以上の**はずみ車効果**を要求される場合が多く、回転子直径がより大きくなり、**鉄心の鉄量が多い**(鉄機械となる)。
    - 体積と重量が重く**高価**になるが、①**短絡比が大きい** ②**同期インピーダンスが小さい**(電圧変動率が小さく、安定度が高)、③**線路充電容量が大きい** といった利点がある。
- *円筒機・銅機械(火力)*
    - 火力発電所に用いられるタービン発電機は回転速度が水車に比べ非常に高速なため、2極機や4極機が用いられ、大きな遠心力に耐えるよう、**直径が小さく軸方向に長い横軸形**の「円筒機」が用いられる。
    - 界磁巻線を施す場所が制約され，大きな出力を得るためには**電機子巻線の導体数が多い**ために銅量が多い(銅機械となる)。
- 汽力発電との比較
    - 水車発電機は、汽力発電よりも**回転速度が小さく**、**発電機の磁極数は多い**。
        - 極数p、系統の周波数fのとき、同期発電機の同期速度$N_s$ は、$ N_s=\frac{120f}{p} $となるので、回転速度が小さくなるほど極数が大きくなる。よって、水車発電機は汽力発電よりも回転数が小さいため、極数は大きくなる。




 ##  揚水発電所

- *ポンプ水車式*
    - 発電電動機とポンプと水車を兼用できるポンプ水車を利用したもの。
    - 国内で最も主流な方式。ポンプ水車式は
- *タンデム式*
    - **発電機と電動機を共用**し、同一軸に水車とポンプをそれぞれ直結した方式。

## 参考動画

[![](https://img.youtube.com/vi/kEA3AwFf-OY/0.jpg)](https://www.youtube.com/watch?v=kEA3AwFf-OY)

[![](https://img.youtube.com/vi/hxoSf7sEJFg/0.jpg)](https://www.youtube.com/watch?v=hxoSf7sEJFg)

特に圧力水車(フランシス水車など)や、衝撃水車と比べて文章だけでは仕組みがわかりにくいため、動画などを見てイメージを掴むのがおすすめです。

## 関連リンク

- [電験3種試験対策トップページ](../index.md)
- [トップページ](../../../index.md)