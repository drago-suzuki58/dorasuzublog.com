---
title: マインクラフトMODの導入方法 Forge/Fabric
tags:
  - MOD
  - マインクラフト
  - マインクラフトMOD
  - Forge
  - Fabric
categories:
  - games/minecraft
date: 2023-03-01 08:00:00
thumbnail: /images/posts/games/minecraft/mod-introduction/mod-introduction-01.jpg
---

![工業Modをプレイしている様子](/images/posts/games/minecraft/mod-introduction/mod-introduction-01.jpg)

**どうも、どらすずです！**

マインクラフトMODって本当に色々なものがありますよね。遊んでも遊んでもどんどん新しいものが出てきて無限に遊べちゃいます！

ちなみにどらすずは**Galacticraft**とか**Mekanism**が好きです。

でも、マインクラフトMODって**導入が少し複雑**でわかりにくいですよね。最初は僕も挫折しました。

そんなわかりにくい導入方法を今回は解説していきます。

MODパックについては少し導入方法が異なりますので、ここでは解説しません。ご了承ください。

また、Mac版は筆者が把握していないため、ここでは扱いません。

## MODとは？

MODとは、英語で「Modification」の略称で、 **「改造」** という意味で、ゲームのコードを変更(改造)して新しい機能を追加することができます。

例えば、マインクラフトに電気の要素を追加したり、新しいアイテムを追加したり、様々なものが存在しています。

MODはゲーム性をカスタマイズすることができるのでマインクラフトをもっと快適にプレイしたり、新しい要素を追加して、**新しい目標を作ったりする**ことができるようになります。

一つひとつ挙げていったら**キリがない**です。

そんな感じで、何でもできるようになっちゃいます。

新しい要素を追加する以外にも、今あるマインクラフトの要素をより快適にする**便利系MOD**もあり、

例えば、マインクラフトをよりサクサク動かせるようにするいわゆる**軽量化MOD**や、木の葉っぱがより早く落ちるようになるMODなんかもあります。

マインクラフトの世界に影を追加してリアルにするMODもあるので、ぜひこの記事を読んで色々導入してみて欲しいです！

## 1. Minecraft ForgeとFabricのインストール

Minecraft ForgeやFabricは、マインクラフトでMODを使用する場合に必ずと言っていいほど**インストールする必要がある**ものです。

私が紹介しているMODのほぼ100%がこの**Forge**や**Fabric**を必要としています。

わかりやすいように言うと、実際は異なりますがMODを導入するために必要なスペースを作るものだと考えておけば基本は問題ないかと思います。

### Forge

Fabricの導入については次項で解説していますので、[Fabricの項目](#fabric)をご覧ください。

**Minecraft Forge** は公式サイトでダウンロードする必要があります。

左のMinecraft Versionから必要なバージョンを選択してください。

![Minecraft Forgeのバージョン選択画面](/images/posts/games/minecraft/mod-introduction/mod-introduction-02.png)

画像はバージョン1.7.10

しかし、かなりの頻度で更新されていて、 **Latest(最新版)** は常に最新のバージョンを利用できますが、不安定で、あまり利用することは推奨されていません。

なので、基本的には **Recommended(安定版)** をダウンロードすれば間違いないでしょう。

マインクラフトのリリースされたばかりの最新バージョンでは安定版がまだできていない場合もあります。その場合は最新版をダウンロードするか、安定版が出るまで待ちましょう。
(そもそもMODができあがっているかは謎ですが)

稀に、Forgeのバージョンが細かく指定されているMODがありますが、

その場合は下のShow all versionsをクリックすればリリースされたすべてのバージョンが閲覧できますので、そこから指定のバージョンをダウンロードしてください。

ダウンロードは、Installerと書いてある場所をクリックし、5秒ほど待ち右上の**SKIPが出るまで**待ってください。

![Forgeダウンロード前の広告待機画面](/images/posts/games/minecraft/mod-introduction/mod-introduction-03.png)

この画面はいわゆる広告なので、もしDownloadなどと書いていてもそれは**詐欺**ですので、クリックしてはいけません。

この画面のときは何もせずに気長に待ちましょう。

そして、SKIPをクリックするとようやくMinecraft Forgeのjarファイルがダウンロードされます。

![Forgeダウンロード前の広告スキップボタン](/images/posts/games/minecraft/mod-introduction/mod-introduction-04.png)

このとき、ブラウザがjarファイルを警告する場合があります。必ず公式サイトからダウンロードしていることを確認したうえで、問題なければ保存してください。

次に、そのファイルをクリックして実行してください。

すると次のような画面が出てくるので、**Install client**になっているのを確認して、OKをクリックしてください。

![ForgeインストーラーのInstall client画面](/images/posts/games/minecraft/mod-introduction/mod-introduction-05.png)

ファイルのパスは変更する必要はありません。

そうしたらOKをクリックします。

![Forgeのインストール完了画面](/images/posts/games/minecraft/mod-introduction/mod-introduction-06.png)

すこし待ち、**Complete**と表示されたら無事インストール完了です。

### Fabric

**Fabric**についても、公式サイトでダウンロードすることが必要です。

公式サイトに行くと、このような画面になるので、**Download here**というボタンをクリックしてください。

そうすると、次のような画面になるので、どちらかをクリックしてください。

ちなみにどちらをクリックしても結果は同じですので気にする必要はありません。

ダウンロードしてクリックして実行をすると、次のようなポップアップが出てきます。

![Fabricインストーラーの設定画面](/images/posts/games/minecraft/mod-introduction/mod-introduction-07.png)

ここで、マインクラフトバージョンを指定して、インストールをクリックして成功すると

![Fabricのインストール成功画面](/images/posts/games/minecraft/mod-introduction/mod-introduction-08.png)

という表示が出てくると思います。

これで無事にインストール完了です。

Fabricの場合は、上の表示のとおり**Fabric API**が必要になる場合が多いです。こちらから[**Fabric API**](https://www.curseforge.com/minecraft/mc-mods/fabric-api/)をダウンロードしておいて、後に説明する方法で導入してくださいね。

## 2. MODのダウンロードと導入

MODのダウンロードは多くの場合CurseForgeというサイトからできます。

他にも、**[Minecraft Mods](https://www.minecraftmods.com/)　[Planet Minecraft](https://www.planetminecraft.com/)　[Minecraft Forum](https://www.minecraftforum.net/)**　などがありますが、今回に関してはCurseForgeでのMODの探し方や例として、Just Enough Items というMODの導入を行いたいと思います。

探し方はもう知っていて導入方法だけ見たい方は、[MODの導入](#modの導入)から読んでください。

### MODの探し方

![CurseForgeのトップページ](/images/posts/games/minecraft/mod-introduction/mod-introduction-09.jpg)

CurseForgeにアクセスしたら、トップページとしてこのような画面が表示されます。

このトップページにはマインクラフトの他にも**様々なゲームのMODが配布**されていて、それぞれダウンロードすることができます。今回は左に見えるマインクラフトをクリックします。

![CurseForgeのMinecraftカテゴリ画面](/images/posts/games/minecraft/mod-introduction/mod-introduction-10.jpg)

クリックするとこのような画面が表示されるのですが、上に表示されているタブのようなものを見てみると、
Bukkit Plugins(サーバープラグイン?) Modpacks(MODパック) Customization(シェーダーや便利系) Addons(アドオン) Mods(MOD) Resource Packs(リソースパック) Worlds(配布ワールド)

と表示されています。これらは、その名のとおりMOD以外のものもありますが、このCurseForgeで**同じく配布**されているものです。機会があったらこれらもダウンロードして遊んでみるのも面白いかも知れません。

MODのダウンロードや検索は**Mods**というところからできるので、それをクリックしてください。

![CurseForgeのMods一覧画面](/images/posts/games/minecraft/mod-introduction/mod-introduction-11.jpg)

するとたくさんのMODが出てきます。が、このままではお目当てのMODにありつけないので、左にあるMagicやTechnologyなどの**ジャンルから選んだ**り、上部にある虫メガネマークで**名前から検索**することができます。

また、上部の Sort by というところから、名前順、最新順、人気順、ダウンロード回数順などから選ぶことができます。

MODは本当にたくさんあるのでぜひ自分のお気に入りのMODを見つけてみてくださいね！

### MODのダウンロード

ここでは、 **JEI(Just Enough Items)** を例にダウンロードを解説していきます。

配布場所は[**こちら**](https://www.curseforge.com/minecraft/mc-mods/jei)

JEIは、アイテムの作成方法や、MODで追加されたアイテムの複雑な作成方法などがわかりやすくなるようなとても便利で多くのクラフターに愛されているMODで、CurseForge内では一番人気のあるMODです。

![Just Enough ItemsのCurseForgeページ](/images/posts/games/minecraft/mod-introduction/mod-introduction-12.jpg)

ダウンロードページを見ると、早速右上にDownloadとありますがここからダウンロードすることは基本的にありません。お目当てのファイルとは別のファイルがダウンロードされてしまう可能性がありますので…

![CurseForgeのFilesタブ](/images/posts/games/minecraft/mod-introduction/mod-introduction-13.png)

ダウンロードにはこのFilesというところをクリックします。

![CurseForgeのファイル一覧](/images/posts/games/minecraft/mod-introduction/mod-introduction-14.png)

そうするとこんな感じにファイルがたくさん出てきますが、お目当てのファイル(今回は1.16.5を例とします)をダウンロードするのに手っ取り早いのは、右上の**View all** をクリックしてバージョン別で探すのがいいです。

View Allをクリックすると次に同じ場所に**All Versions**というのが出てくるのでそれもクリックするとこのようなポップアップが出てきますので、お目当てのバージョンをクリックします。

![CurseForgeのバージョン選択メニュー](/images/posts/games/minecraft/mod-introduction/mod-introduction-15.png)

![CurseForgeのダウンロード待機画面](/images/posts/games/minecraft/mod-introduction/mod-introduction-16.png)

するとこのような画面になるかと思います。必ずしも最新版をダウンロードすればいいというわけではなく、左のType(タイプ)に緑のRが付いているものが**Release(リリース)**、つまり安定版です。

それ以外は **Beta(ベータ)** なので予期せぬ不具合が生まれてしまう場合もあります。

これ以外に **Alpha(アルファ)** もありますが基本的に安定版をダウンロードすれば問題ないかと思います。

ちなみにFabricだとバージョンのところをFabricにしたり、Fabric用のJEIがあったりするので探してみてください。

![CurseForgeのダウンロード待機画面](/images/posts/games/minecraft/mod-introduction/mod-introduction-17.png)

ダウンロードするとこのように5秒待ってくださいとあるのでここも気長に待ちましょう。

５秒待てば自動的にMODのファイルがダウンロードされます。

**これでMODのダウンロードは以上です！**

### MODの導入

MOD導入にあたってまず最初にマインクラフトを起動する必要があります。

とはいっても、普通に起動するわけではなく、先程説明したForge Fabric導入済みのマインクラフトを起動します。

![Minecraftランチャーのメイン画面](/images/posts/games/minecraft/mod-introduction/mod-introduction-18.jpg)

右上の起動構成という場所から、

![Minecraftランチャーの新規作成ボタン](/images/posts/games/minecraft/mod-introduction/mod-introduction-19.png)

新規作成をクリックして

![Minecraftランチャーのバージョン選択欄](/images/posts/games/minecraft/mod-introduction/mod-introduction-20.png)

バージョンを見てみると…なんと！Forgeが追加されています。

このバージョンは先程ダウンロードしたバージョンごとに違いますが、そのバージョンを選択してください。

なかなか見つからない場合はforge や fabric などと検索するのも手かもしれません。

![Minecraftランチャーのゲームディレクトリ設定](/images/posts/games/minecraft/mod-introduction/mod-introduction-21.png)

ゲームのプロファイルは、バニラの何もMODの入っていないバージョンとそれ以外や、ゲームバージョンごとに分けるために新しいフォルダを作成して、その中で管理することをおすすめします。

別にどこでも構いません。CドライブでもDドライブでも全然動作に問題はないので、**一番管理し易い場所を選ぶ**のが最適です。

↓例

```
.minecraft
├─Forge 1.16.5
└─Mekanism 1.18.2
```

これはあくまで一例なのでファイル名をわかりやすいものにするのがよいと思います。

全部設定し終わったら**プレイ**ボタンをクリックします。

![Minecraftランチャーのプレイボタン](/images/posts/games/minecraft/mod-introduction/mod-introduction-22.png)

すると見慣れないポップアップが出てきますがMODを入れることへの注意を促しているだけなので無視してもらってかまいません。

これで、マインクラフトのタイトル画面まで行ったら、すぐに**ゲームを閉じてもらって構いません**。

すると先程作ったフォルダの中にこのようなフォルダが生成されていると思いますので、この**modsフォルダ**に先程ダウンロードしたMODファイルを入れます。

では、もう一度マインクラフトを起動してみましょう！

![JEIを導入したMinecraftのインベントリ画面](/images/posts/games/minecraft/mod-introduction/mod-introduction-23.jpg)

**右側に初めて見るアイテムの一覧が増えています！**

これで導入成功です！おつかれさまでした！

## 注意点

ここからは、MODの導入に関して注意することをもう少し**深掘りして説明**します。

### 1.MODのバージョンを確認する

MODは、ForgeやFabricのバージョンと互換性がある必要があり、メイン**バージョンが1違うだけで正常に動作しなくなります**。(マイナーバージョンの場合は動く場合もある)

しっかり確認した上でダウンロードをするようにしましょう。

### 2.MODの信頼性を確認する

MODは、導入するとマインクラフトの動作が変わるため、**ウイルスが含まれている可能性**もあります。

そのため、信頼できる提供元からダウンロードして導入する必要があります。

しかし、CurseForgeにアップロードされているファイルはすべて**ウイルススキャンがされている**のでその点は安心です。

### 3.多くのMODを導入しすぎない

MODはたくさん入れすぎるとマインクラフトの動作が**とても遅く不安定になったり**、**MODとMODの互換性の問題**で、そもそも**起動ができなくなってしまう**問題が起きます。

MODは適度な量で、必要なMODだけ入れるようにして、入れる時は**一つずつ起動を確認しながら導入**していきましょう。

### 4.ワールドのバックアップを取る

MODを導入していないワールドや、MODを新たに導入しようとしているワールドでは、新しくMODを導入したことによって**ワールドがクラッシュ等してワールドデータが壊れてしまう**ことがあります。

それを防ぐために、**既存のワールドデータは必ずバックアップを取る**ようにしましょう。

### 5.オンラインプレイでの注意点を理解する

オンラインプレイでは、**サーバーのMODの利用ルール**について理解することが大切です。

**他プレイヤーに不具合**が起きたり、**サーバーに不具合**が起きたりするためです。

そのため、許可されていない状態でMODを使用すると**最悪永久BAN**という可能性もありますので、必ずサーバーのMODルールを読んでください。

## まとめ

以上で、マインクラフトMODの導入方法についての解説が全部終わりました！

MODを導入することで、マインクラフトの世界を**より楽しく**、**より便利に**、**より奥深く**楽しむことができます。

注意点をよく理解してぜひ様々なMODを楽しんでみましょう！
