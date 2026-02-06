---
title: 【マインクラフト】１スタックの上限を64以上にする便利MOD「Stacker」
tags:
  - MOD
  - マインクラフト
  - マインクラフトMOD
  - 便利MOD
category:
  - games/minecraft
date: 2023-02-20 20:10:31
---

![](https://dorasuzublog.com/wp-content/uploads/2023/02/2023-02-22_01.19.43.png)

どうも、どらすずです。

皆さんは

**1スタックがたった64個って不便！**

って思ったことありませんか？

案外洞窟探索とか整地とかしているとあっという間に1スタックって埋まってしまいますよね…

今回は、その1スタックをなんと**64以上**にすることができるMODを紹介します！

この記事はこんな人におすすめです

*   **1スタックの量をもっと増やしたい！**
*   **もっとたくさんのアイテムを収納したい！**

## 前提として

この記事に掲載しているMODを導入したことにより発生してしまった損害について私は**一切責任を負いかねます**。

**※MODは有志の方が作ってくださった非公式のコンテンツです。プレイする際にはすべて自己責任となります。**

### MODの導入方法

MinecraftForgeや、MODの導入方法についてはこちらをご覧ください

https://dorasuzublog.com/game/minecraft-mod/03/mod-introduction/

## Stackerとは？

冒頭でも説明したとおり、1スタックの数を64上限ではなく、いわゆる機械のオーバーフロー値になっている約10億個までを自由に上限にすることが可能になるMODです。

配布は[CurseForge](http://curseforge.com/minecraft/mc-mods/stacker)から

基本となっているのはfabricバージョンですが、個人的にはForgeバージョンの方が使い勝手が良いと感じました。

対応バージョンはfabricバージョンが、**1.15.2 1.16.5 1.17.1 1.18.x 1.19.x** となっていて、比較的最近のMODですね。

ただ、比較的古い2つの **1.15.2 1.16.5** バージョンに関しては、このStackerMODの前身となる**[staccMOD](https://curseforge.com/minecraft/mc-mods/stacc)**をダウンロードしなければなりません。

しかし、MODの内容的にはどちらも同じですので、そこまで気にする必要はないかと思います。

まあ、操作性だったり設定方法だったりは異なると思いますが…

そして、Forgeバージョンの方は、名前が少々異なっていて、**[bigger stacks](https://curseforge.com/minecraft/mc-mods/bigger-stacks)**という名前ですが、**1.12.2 1.13.x 1.18.2 1.19.x** で対応していて、

こちらも先ほどと同じく、古い2つの **1.12.2 1.13.x** バージョンに関しては、bigger stackMODの前身となるMOD、**[stack upMOD](https://curseforge.com/minecraft/mc-mods/stackup)**をダウンロードする必要があります。

## 使い方

ここでは、この４種類のMODについて使い方を簡単に説明します。

詳しい説明については配布ページなどをご参照ください。

### Stacker

こちらでは、[Cloth Config API](https://www.curseforge.com/minecraft/mc-mods/cloth-config)というものを使用して、マインクラフト内の設定でスタック数の変更ができます。

メニューはこんな感じになっていて、かなり使いやすいです。

![](https://dorasuzublog.com/wp-content/uploads/2023/03/image-25-1024x596.png)

https://www.curseforge.com/minecraft/mc-mods/stackerより引用

### stacc

使用方法についてはよくわかりませんでした…申し訳ないです。

### bigger stacks

このMODが適用された世界に入ると最初にこのような表示が出てきます。

この青いhereという場所を押すと初期設定が開始され、

![](https://dorasuzublog.com/wp-content/uploads/2023/03/image-26-1024x290.png)

https://www.curseforge.com/minecraft/mc-mods/bigger-stacksより引用

![](https://dorasuzublog.com/wp-content/uploads/2023/03/2023-03-17_17.11.15-1024x576.jpg)

このような感じに、普通のアイテム、エンチャントされた本、ポーションのスタック数をそれぞれ変更できます。

**/biggerstacks quicksetup** を入力するといつでもこのメニューを呼び出せます。

### stackup

MODをインストールするとconfigフォルダに**stackup.cfg**というファイルが作られるので、その中の

![](https://dorasuzublog.com/wp-content/uploads/2023/03/image-27.png)

という文字列の**maxStackSize**を変更することでスタックの上限を変更できます。

## 最後に

スタックの上限を変更するということは、マインクラフトのゲーム性に大きく関わることになりますので、他のMODとの競合も十分に考えられます。

また、ゲームが簡単になりバランスの崩壊も考えられますので十分に気をつけて利用してくださいね。

スタック上限が変更されたアイテムを持ったままこれらのMODを抜くと予期しない事態がおこる場合もあるので十分ご注意ください。
