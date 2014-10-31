#概要
Chromeのブックマーク または 検索エンジン をランチャーから開ける。
※firefoxでも使える。

#ランチャーの機能
* Chromeのブックマークに登録しているサイトを、ランチャーから開くことができる
> Chromeのブックマークに、
> 名前：「qiita」 URL:「※QiitaのURL」
> と登録していた場合、ランチャーに「qiita」と入力し、Enterを押すとQiitaのサイトを開くことができます。

* shortcutフォルダ外部ファイル(exeファイルや、エクセルなど)
> ランチャーのexeファイルの隣にあるshortcutディレクトリの中に、poderosaのショートカットを登録しておくと、ランチャーからpoderosaを起動できます。

* Chromeのブックマークに登録していない文字をランチャーに入れると、google検索できる
> 例えば、ChromeのブックマークにamazonのURLを登録していないときに、
> ランチャーに「amazon」と入力し、Enterを押すと、googleの検索結果がブラウザに表示されます。

* <strong>（これが一番やりたかった機能！）</strong>Chromeの検索エンジンに登録している検索設定を、ランチャーから起動できる
> 例えば、Chromeの検索エンジンに
> キーワード：「alc」 URL：「http://eow.alc.co.jp/search?q=%s」
> と登録し、ランチャーに「alc product」と入力すると
> アルクで product という単語を検索した結果がブラウザに表示されます。
> 
> ※Chromeの検索エンジンへの登録の仕方
> 1.Chromeのアドレスバーに「chrome://settings/searchEngines」と入力。
> 2.その他検索エンジン　の一番下にある
>「検索エンジンを追加・キーワード・URL」
> に登録したいサイトを入力する

#ランチャーの設置・起動
1. 「clunch」をcheckout
2. 好きなフォルダに、「clunch」フォルダを配置する
3. 「clunch」フォルダにある「clunch.exe」を起動する<br>
※clunch.exeをwindowsのスタートアップに登録しておくと便利です。

#邪魔なときは...
* 「Ctrl + shift + A」でランチャーを表示できる
* 「Ctrl + shift + E」でランチャーを非表示にできる

#こだわり・感想・備考など
* 今まで使っていたランチャーは、いちいちサイトを登録しなければいけなかったので、<br>
  Chromeブックマークに登録　⇒　次からランチャーで一発起動<br>
  できるようにしたかった。
* 普段から、Chromeだけでなく、FFも使っており、FFでもChromeの検索エンジン機能を使いたかったので、ランチャーから起動できるようにした。


* node-webkitを使うと、簡単にデスクトップアプリを作ることができた ※次はChrome appsもやってみたい。
* ソースが汚いので、リファクタリング後、githubにのせる予定
