# 【電験3種・電力】フェランチ効果の試験問題対策

## フェランチ効果とは

フェランチ効果とは、負荷が軽い深夜帯などに、受電端電圧が送電端電圧より上昇する現象です。

## 【例題1】三相3線式1回線送電線のフェランチ効果

【問題】

三相3線式1回線送電線の一相が図のπ形等価回路で表される。
送電線路のインピーダンスjX=j200[Ω]、アドミタンスjB=j0.800 [mS] 、送電端の線間電圧が66.0[kV]、受電端が無負荷のとき ①受電端の線間電圧の値[kV] ②1線当たりの送電端電流の値[A]を計算せよ。

【①の解答】

送電端電圧(相電圧)を$\dot{E_s}$、受電端電圧(相電圧)を$\dot{E_r}、$送電端側のアドミタンスに流れる電流を$\dot{I_1}$とすると、受電端側のアドミタンスに流れる電流$\dot{I_2}$は以下のとおり。

$\dot{I_2}=\frac{jB}{2}\dot{E_r}$

送電端電圧$\dot{E_s}$は、受電端は無負荷なので以下のようになる。

$\dot{E_s}=\dot{E_r}+jX\dot{I_2}=\dot{E_r}+jX\frac{jB}{2}\dot{E_r}=(1-\frac{XB}{2})\dot{E_r}$

上式から$\dot{E_s}$と$\dot{E_r}$は同相なので、$\dot{E_r}$が求まる。

$dot{E_r}=\frac{1}{1-\frac{XB}{2}}E_s=\frac{1}{1-\frac{200 \cdot 0.8 \times 10^{-3}}{2}}\cdot\frac{66}{\sqrt{3}}=41.42[kV]$

よって、受電端の線間電圧$V_r$は以下のとおり。

$V_r= \sqrt{3}E_r=71.7[kV]$

【②の解答】

$\dot{I_1}=\frac{jB}{2}\dot{E_s}$

$\dot{I_2}=\frac{jB}{2}\dot{E_r}$

より、送電端電流$\dot{I_s}$は以下のとおり。

$\dot{I_s}=\frac{jB(\dot{E_s}+\dot{E_r})}{2}$


上式から$\dot{E_s}$と$\dot{E_r}$は同相なので、Isが求まる。

$I_s=\frac{B(E_s+E_r)}{2}=\frac{0.8\times 10^{-3}}{2}(\frac{66}{\sqrt{3}}\times10^3+41.42\times 10^3)=31.8[A]$


## 参考動画

*初心者向け電験三種・電力・23・変圧器の負荷分担【超簡単に学ぶ！】第三種電気主任技術者*
 [![](https://img.youtube.com/vi/-CJ1sk7Zuds/0.jpg)](https://www.youtube.com/watch?v=-CJ1sk7Zuds)


## 関連リンク

- [電験3種試験対策トップページ](../index.md)
- [トップページ](../../../index.md)