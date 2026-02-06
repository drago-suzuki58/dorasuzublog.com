---
title: 【Ren'Py】開発が爆速になるかもしれない多機能デバッグツール、Ren'Py Debug UIの紹介
tags:
  - MOD
  - RenPy
  - RenPy Debug UI
  - デバッグ
  - プログラミング
category:
  - programming
date: 2025-07-17 10:11:31
---

![](https://dorasuzublog.com/wp-content/uploads/2025/07/image-1024x600.jpg)

Ren'Py公式チュートリアルに導入したスクショ

Ren'Py Debug UI (GitHub)
[https://github.com/drago-suzuki58/renpy\_debug\_ui](https://github.com/drago-suzuki58/renpy_debug_ui)

今回は私の自作Ren'Py用デバッグツールを紹介したいと思います

Ren'Pyを使って開発したり、Mod開発をしたりしている方には非常に使いやすく、便利なものになっていると思います

## 機能

### 言語切り替え (Language Settings)

![](https://dorasuzublog.com/wp-content/uploads/2025/07/image-5.png)

ゲーム内のどんなときでも、わざわざメニューを開いて言語切り替えをせずともこのUIでサクッと切り替えできます

ゲーム内で利用できる言語を自動で取得し、表示します

Default LanguageはRen'Pyで定められた既定の言語、いわゆるNone言語にします

### セリフ位置 (Script Position)

![](https://dorasuzublog.com/wp-content/uploads/2025/07/image-4.png)

現在のセリフや選択肢の、コード上の位置やファイル名を参照できます

間違っているセリフや翻訳を見つけたときとかに一発で該当箇所を特定できます

### ゲーム情報 (Information Metrics)

![](https://dorasuzublog.com/wp-content/uploads/2025/07/image-3.png)

ゲームエンジンの状態を確認できます

表示される項目は、

*   Screen Size: 実際のゲーム描画サイズ
*   Window Size: 実際のゲームウィンドウのサイズ
*   Renderer: レンダリングエンジン
*   Fullscreen: フルスクリーンか否かの真偽値
*   Ren'Py: 実行されているRen'Pyのバージョン
*   Platform: 実行されているプラットフォーム

になります

### 変数エクスプローラー&エディター (Store Explorer)

![](https://dorasuzublog.com/wp-content/uploads/2025/07/image-6.png)

Ren'Pyのstore変数に登録されている値を直接参照したり、編集することができます

編集の際は、以下のようなボックスから編集が可能です

![](https://dorasuzublog.com/wp-content/uploads/2025/07/image-1-1024x600.jpg)

特に、フラグ変数の編集で挙動を簡単に確かめたり、変数の挙動の確認に役立つと思います

## 導入方法

バージョンについて

Ren'Py Debug UIは、Ren'Pyバージョン**6.99.11**以降のみで動作します

それ以降のバージョンであれば互換性がありますが、それ以前のバージョンではコード自体記法が異なり、動作しません(対応予定もありません)

推奨バージョンは**8.0**以降です

まず導入したい該当のRen'Pyのプロジェクトフォルダを開いてください

### Git分かる人向け

Ren'Pyプロジェクトのgameフォルダで、

```bash
git clone https://github.com/drago-suzuki58/renpy_debug_ui.git
```

で導入完了です

### Git分からない人向け

あらかじめ、Ren'Pyのプロジェクトの**game**フォルダに**renpy\_debug\_ui**というフォルダを作成しておいてください(重要)

*   <プロジェクトのルート>
    *   game
        *   renpy\_debug\_ui
    *   renpy

のような構成になっていれば問題ないです

このGitHubリンクより、Download ZIPでダウンロードをしてください
[https://github.com/drago-suzuki58/renpy\_debug\_ui](https://github.com/drago-suzuki58/renpy_debug_ui)

![](https://dorasuzublog.com/wp-content/uploads/2025/07/image-1.png)

ここでダウンロードできたzipファイルを解凍し、**renpy\_debug\_ui-main**フォルダの中身を全部、先程作った**renpy\_debug\_ui**フォルダに入れてください

これで導入完了です

## 使い方

Insertキーを押すことでいつでもメニューの表示非表示を切り替えられます
グラフィックを見たいときや、単純に邪魔なときに非表示にできます

## 発展

実はこのDebug UIは、自分でゲームを作るときだけでなく、Ren'Py製ゲームのModとしても機能するようになっているので、すでにSteamやitch.ioで配布されているゲームに導入して利用することもできます

これを利用すれば有志による非公式翻訳や、ゲームの挙動を解析して新しい機能を追加するModdingにも利用できるかと思います

また、Windowsだけでなく、おそらくWebビルドを含めたすべてのプラットフォームでRen'Py Debug UIは動作するので、そのときのデバッグにも有効活用できると思います

(MacやiOSは私が持っていないので動作未確認ですが、動くと思います)
(動いたらぜひ教えてほしいです！)

## おまけ

このUIはImGuiなどのようなUIライブラリの挙動やデザインを参考にしていたりします

あのUIがどれだけ完成されているのかを今回を通じてよくわかりました

何か質問などあれば、ここのコメントやGitHubのIssueなどに書いていただければ返答できるかもしれません
絶対的な解決は保証できませんが、どうぞよろしくお願いします

また、他にも機能を追加するかもしれないので、ぜひGitHubにスターを付けていただけたら励みになります！
