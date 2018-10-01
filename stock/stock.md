# **Stock**
## **Mac設定**
### 基本設定
* [Mac設定1](https://boxil.jp/mag/a2245/?page=2)
* [Mac設定2](https://matome.naver.jp/odai/2138629469334511401)
* [Mac設定3](https://takakojima.com/mac%E5%88%9D%E5%BF%83%E8%80%85%E3%81%AB%E3%81%8A%E3%81%99%E3%81%99%E3%82%81%E3%81%AE%E8%A8%AD%E5%AE%9A/)

### アプリ
* [Macおすすめアプリ](https://pc-karuma.net/mac-recommended-app/)
* [Atomショートカットキーチートシート](https://qiita.com/yamagh/items/0fb4e7bbbd3c9ef4d855)  

### ターミナル
* [iterm2の導入から、zshの導入、Rictyの導入。Preztoを導入するかは各自決めて良い](https://www.te-nu.com/entry/2018/08/30/214757)
* [zshの設定](https://news.mynavi.jp/article/zsh-24/)
* [iterm2の設定](https://qiita.com/ruwatana/items/8d9c174250061721ad11)

* 抜けるためには　Ctrl+c  
* [ツリー構造を出力するコマンド](https://www.yoheim.net/blog.php?q=20160802)
### マークダウン
* [Markdown記法一覧](https://qiita.com/oreo/items/82183bfbaac69971917f)
* [Markcown細かいところが知りたい場合](https://qiita.com/higuma/items/3344387e0f2cce7f2cfe)
* [Atomに入れるMarkdownのパッケージ](https://qiita.com/kouichi-c-nakamura/items/5b04fb1a127aac8ba3b0)
## **開発基礎**
* [.bashrcと.bashprofileの使い分け](https://qiita.com/magicant/items/d3bb7ea1192e63fba850)
* [Railsのアプリケーションサーバ、Webサーバを知るにはいい記事かも](https://qiita.com/jnchito/items/3884f9a2ccc057f8f3a3)
### Git×GitHub
* [Git初心者の用語説明](https://qiita.com/nnahito/items/e546b27f73e7be131d4e)  
* [Gitのコマンドチートシート](https://qiita.com/konweb/items/621722f67fdd8f86a017)
* [git-flowとGitHub-flowの違い](https://qiita.com/nnahito/items/565f8755e70c51532459)

### Docker
* [Dockerとは](https://www.slideshare.net/zembutsu/docker-images-containers-and-lifecycle)

>Docker仮想化環境構築入門を読んで
> DockerCompseとは何か
> * マルチコンテナのDockerアプリケーションを定義して実行するために使用するツール
> * 用途としては、開発環境の構築、自動テストの実行環境の立ち上げなど、アプリケーションのコンテナの他に、DBなどのコンテナが必要な場合に使用されることが多い
> * Webサーバ、DBサーバなどの各コンテナの定義をYAML形式のファイルに記述しておき、その適宜ファイルを使って、まとめてコンテナの管理を行う
> * 実際のDockerfile,docker-compose.ymlの記載方法もまとめていきたい

* [docker-composeのコマンドチートシート](https://qiita.com/wasanx25/items/d47caf37b79e855af95f)
* [docker再起動時にA server is already running.となり、Exitされてしまう時の対対処法](http://hsuzuki.hatenablog.com/entry/2017/06/08/151658)
## **モデリング**
* [astahの使い方動画](http://astah.change-vision.com/ja/product/videos.html#astah)
### テスト駆動開発
* [テスト駆動開発を読んで](https://dev.classmethod.jp/study_meeting/read/what-tdd/)  

* [ちょっと面白そう](https://twop.agile.esm.co.jp/tdd-was-broken-by-mania-cb5a6e94b021)

## **バックエンド=Rails**  
* ローカル環境でrailsを動かすことはできたが、【rbenv global 2.5.1】でバージョン変更ができないため、  
 2.3.7を使用中
* バージョン変更の方法は、全体共通のglobalとプロジェクト毎に設定ができるlocalがある。localで設定されたものが優先される  
* [モデル作成に必要なコマンド類](https://qiita.com/zaru/items/cde2c46b6126867a1a64)
* 公式ページをしっかりみよう。
  - Qiitaに乗っているようなことは公式ページかGitHubがソース元。read.meを読もう
    - gemを追加する時

* **前島からの提案**
  - githubからrailsのプロジェクトを落としてきて動かす
  * プロジェクトを複数作り、違うバージョンのrubyで使う
    →localでバージョン変更を行う
    ・rbenvの公式ホームページを見に行った
    ・バージョンをglobalで変更しようとしたが、
    できなかったため、localで変更
    ・rbenv versions は2.5.1だが、画面は2.3.7
    　→画面は固定なのでは？

    学んだこと
    ・installをする時はまず公式を見に行こう
    ・つまずいても、最終ゴールに到達できる道があるなら、その道にを突き進んでみることも大切
    ・rubyのバージョンはrbenvで、GemはBundleで管理する
  * bundle exec rails s -p 3000 -b '0.0.0.0'を実行すると、画面が表示される

## **フロントエンド=Vue.js**
* 結局JavaScript
