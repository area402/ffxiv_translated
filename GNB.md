## 開幕
```
【キーンエッジ】
【ブルータルシェル】
【ソリッドバレル】
【キーンエッジ】《ノー・マーシー》
【ブルータルシェル】
【ビートファング】《ジャギュラーリップ》《ブラッドソイル》
【ソニックブレイク】《ブラスティングゾーン》《バウショック》
【サベッジクロウ】《ラフディバイド》《アブドメンテアー》
【ウィケッドタロン】《ラフディバイド》《アイガウジ》
【バーストストライク】
【ソリッドバレル】
【バーストストライク】
【バーストストライク】
【キーンエッジ】
……
```

MTの場合は【サンダーバレット】を使うのでGCDが一個遅れるが、【ブルータルシェル】をスキップして《ノー・マーシー》直後に【ビートファング】に入ればバーストタイミングは同じになる。

基本的な考え方として、**だましの直後に【ビートファング】が入るようにすると、【ビートファング】系コンボと【バーストストライク】全てにだましが乗る**ことを念頭においておく。

もしかしたら5.xでは以前のような9s～11sだましが一般的ではなくなるかもしれないので、その際は上記のスキル回しも調整してほしい。

## 《ノー･マーシー》

60sリキャストながら20sの長いバフである《ノー・マーシー》は、原則として9GCDに乗る。

ただしSSが低いようであればGCD後半で使わないと最後が抜けるので注意。

9GCDの内訳は、【キーンエッジ】系コンボ3段、【ビートファング】系コンボ3段、【バーストストライク】2回、【ソニックブレイク】がベスト。

つまりこの中で3つのソイルを消費できなければならず、**《ノー・マーシー》前にソイル2**の状態を作ることが必須になる。

《ノー･マーシー》前にはソイルの使用量を調整すること。

アビリティは《ラフディバイド》2回、《バウショック》、《ブラスティングゾーン》。

リキャストは自然に合うので特に気にする必要はない。

## 《ブラッドソイル》+《ノー・マーシー》

《ブラッドソイル》が入ってくるので3回ごとに《ノー・マーシー》中のソイル管理を少し変える必要が出てくる。

ソイル0の状態でなければ《ブラッドソイル》を使ってはいけない (当たり前)。

つまり
```
（ソイル1）
【キーンエッジ】《ノー・マーシー》
【ビートファング】《ブラッドソイル》《ジャギュラーリップ》
【ソニックブレイク】《ブラスティングゾーン》《バウショック》
【サベッジクロウ】《ラフディバイド》《アブドメンテアー》
【ウィケッドタロン】《ラフディバイド》《アイガウジ》
【バーストストライク】
【ブルータルシェル】
【バーストストライク】
【ソリッドバレル】
【バーストストライク】
……
```
この形を理想として調整する必要がある。

普段と比較すると《ノー・マーシー》中の【キーンエッジ】が【バーストストライク】に置き換わっていて、結果的に威力60分の得が見込める。

## 1分間レベルの最適化

60sという括りでスキル回しを最適化することを考える。

SSを一切積まない2.5sの状態で考えれば、60sの間に実行できるGCDスキルは24個。

その内最も優先度が高い【ビートファング】系コンボは2回あるので6個を占有する。

次に【ソニックブレイク】が1個。

さらに【キーンエッジ】系コンボを【ビートファング】のために2回実行する必要がありこれが6個。

余りは【キーンエッジ】系コンボ + 【バーストストライク】で埋めるのが最適として、残り11個のGCDのうち8個が自然とこれで埋まることになった。

この時点で残りはというと3個のGCDだが、これを単独で消費可能な【キーンエッジ】系コンボで埋めるとしたとき1分に1つずつソイルが余ってしまう。

従って、ガンブレイカーにおいては**1分間のGCDが25個になるだけのSSを積む**のは理にかなった選択と言える。

この状態では【ビートファング】は28.8s、【ソニックブレイク】は57.6sのリキャスト時間になり、1分に1回のGCD遅れを自然に取り戻せる状態になる (GCD中にリキャスト明けになった場合の損失がなくなる)。

まとめると1分間のGCD内訳は以下の通りになる。

```
5 * 【キーンエッジ】>【ブルータルシェル】>【ソリッドバレル】
2 * 【ビートファング】>【サベッジクロウ】>【ウィケッドタロン】
3 * 【バーストストライク】
1 * 【ソニックブレイク】
```

しかしこれは《ブラッドソイル》のことを考慮していないので、更に踏み込んだ考察をしていく。

## 3分間レベルの最適化

《ブラッドソイル》は90sアビリティであるため、上述したように3回に1度《ノー・マーシー》と併用されることになる。

この最大バーストの周期、3分間を区切りとして考える。

3分間で《ブラッドソイル》によってソイル4つが生成される。

先ほどのセクションで1分間のスキル回しをガチガチに固めてしまったわけだが、どのGCDを【バーストストライク】に置き換えればよいだろうか？

結論から言うと簡単なことで、【キーンエッジ】系コンボを1回減らすだけである。

1分間でソイルの生成/消費が同数になるようスキル回しを組んでいるから、コンボが1回減るとソイルも1つ足りなくなる。

4つ生成される追加のソイルは、結果的にこの不足分を補いつつコンボと同じ3個のGCDを消費することで帳尻が合うというわけだ。

まとめると、3分間のGCD内訳は以下のようになる。
```
14 * 【キーンエッジ】>【ブルータルシェル】>【ソリッドバレル】
 6 * 【ビートファング】>【サベッジクロウ】>【ウィケッドタロン】
12 * 【バーストストライク】
 3 * 【ソニックブレイク】
```