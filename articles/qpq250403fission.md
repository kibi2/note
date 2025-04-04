---
title: "【物理クイズ】核分裂のエネルギー源はなんですか"
emoji: "🦔"
type: "tech" # tech: 技術記事 / idea: アイデア
topics: [物理]
published: false
---
## 問題 

**【問】核分裂のエネルギー源はなんですか**

今の原子力発電所はウラニウムなどを核分裂させて発電しています。ウラニウムがもともと持っていたエネルギーが核分裂によって熱エネルギーなどになるのです。それではこのウラニウムがもともと持っていたエネルギーの種類はなんでしょうか。位置エネルギーでしょうか、運動エネルギーでしょうか。位置エネルギーだとすると四種類の力（重力、電磁気力、強い力、弱い力）のどれに関係した位置エネルギーでしょうか。それとも位置エネルギーとも運動エネルギーともちがうものでしょうか。

皆さんはどう考えますか？

## ヒント 

次のような答えが予想されます。皆さんの考えに近いものはありますか。

- 核反応なので強い力（核力）の位置エネルギー
- 原子核はプラスの電荷をもつので電磁気力の位置エネルギー
- 強い力と電磁気力の両方の位置エネルギー
- 核子（陽子・中性子）の運動エネルギー
- 位置、運動エネルギーではあらわせない核エネルギー
- なんのことやらさっぱりわかりません

## イラスト 

## 私の答え 

**【答】電磁気力の位置エネルギー**

でも私は物理の素人なので私の答えは間違っているかもしれません。 私の考えを解説する前にAIにきいてみましょう。

## AIにきいてみた 

> 核分裂エネルギーの元になっているのは、核子（陽子・中性子）が原子核内で持っている結合エネルギーです。この結合エネルギーは、強い力（核力）による位置エネルギーとみなせます。

私の答えとはちがいました。

## 解説 

AIがいうように核分裂エネルギー源は、核子（陽子・中性子）が原子核内で持っている結合エネルギーです。ここは正しいです。問題は結合エネルギーの内訳がどうなっているか、です。


### 核分裂反応とはなんでしょうか 

原子炉では核分裂が起きています。普通に原子炉で起きている現象をざっくりみてみます。原子炉の燃料はウラン235です。ウランが中性子を吸収すると不安定になってより軽い原子核といくつかの中性子に分裂します。この分裂するときに熱エネルギーなどが発生し、この熱エネルギーで発電します。これが原子炉で起きている核分裂です。Wkipediaの[核分裂反応](https://ja.wikipedia.org/wiki/%E6%A0%B8%E5%88%86%E8%A3%82%E5%8F%8D%E5%BF%9C)の具体例を引用しておきます。

$$
{\displaystyle {}^{235}{\rm {U}}+{\rm {n}}\rightarrow {}^{95}{\rm {Y}}+{}^{139}{\rm {I}}+2{\rm {n}}}
$$

ウラン($${U}$$)が中性子($${n}$$)を吸収して二つの原子核と2個の中性子になります。原子核はイットリウム($${Y}$$)とヨウ素($${I}$$)です。分裂の仕方は何種類もありますが、これはその1例です。1個の中性子を吸収して複数の中性子ができます。反応で中性子が増えるのです。増えた中性子が他のウラン235とぶつかって核分裂をおこせば連鎖反応でウランが燃え続けます。

### 核子どうしは核力で引き合います（引力） 

陽子と中性子のことを核子と呼ぶことにします。核子間に働く強い力のことを核力と呼ぶことにします。 核力は核子の間に働く引力です。核子どうしをくっつけようとする力です。ですので原子核を二つに分けるためには核力にさからって引き離さなければいけません。つまりエネルギーが必要です。核分裂で核力はエネルギーを吸収するようにはたらきます。

### 陽子どうしは電磁気力で反発します（斥力） 

原子核にはプラスの電荷をもった陽子がつまっています。プラスの電荷とプラスの電荷は反発しあいます。くっついているより離れていた方が安定します。核分裂で電磁気力はエネルギーを放出するようにはたらきます。

### 数字でかんがえる 

原子核の結合エネルギーを計算する式があります。結合エネルギーの核力、電磁気力の内訳もだいたいわかります。[ベーテ・ヴァイツゼッカーの公式](https://ja.wikipedia.org/wiki/%E3%83%99%E3%83%BC%E3%83%86%E3%83%BB%E3%83%B4%E3%82%A1%E3%82%A4%E3%83%84%E3%82%BC%E3%83%83%E3%82%AB%E3%83%BC%E3%81%AE%E5%85%AC%E5%BC%8F)です。Wikipediaへのリンクをはっておきました。公式の詳細はWikipediaをご覧ください。

結合エネルギーとは原子核を作っている陽子と中性子を1個1個ばらばらにするのに必要なエネルギーです。結合エネルギーが大きいほど安定しています。

核分裂の具体例ではウラン(U235)がイットリウム($${Y}$$)とヨウ素($${I}$$)に分裂しました。中性子($${n}$$)の結合エネルギーは0です。なのでおおよそ次の式がなりたちます。

$$
E_F=(E_Y+E_I)-E_U
$$

ここで
$${E_F}$$:核分裂で発生するエネルギー
$${E_Y}$$:イットリウムの結合エネルギー
$${E_I}$$:ヨウ素の結合エネルギー
$${E_U}$$:ウラン235の結合エネルギー

ベーテ・ヴァイツゼッカーの公式で計算すると結合エネルギーはこうなりました。

![](/images/250403fission_table.png)

ウラニウムの結合エネルギーは1,800MeVです。イットリウムとヨウ素を合わせた結合エネルギーは1,981MeVです。核分裂を起こすとその差181MeVのエネルギーが放出されます。結合エネルギーの内訳をみてください。核力は引力なので結合エネルギーは正の値です。電磁気力は反発力なので負の値です。核分裂をおこすと電磁気力で357MeVのエネルギーが放出されます。核力は176MeVのエネルギーを吸収します。あわせて181MeVです。

## まとめ 

核分裂のときは核力は引力なのでエネルギーを吸収します。電磁気力は斥力なのでエネルギーを放出します。電磁気力のエネルギーの方が大きいので合計すると放出するエネルギーのほうが大きくなります。つまり核分裂エネルギーの源は電磁気力による位置エネルギーです。

----

## 結合エネルギーとはなんでしょうか 

つまりウラン原子核1個より、より軽い原子核2個になった方がエネルギーが低いのです。そのエネルギー差が熱エネルギーなどになるのです。核融合の真逆です。核融合は陽子と中性子が分かれているときより陽子と中性子が合体して重水素核1個になったほうがエネルギーが低いのです。
