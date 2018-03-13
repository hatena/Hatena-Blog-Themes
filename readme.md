# Boilerplate Less （開発終了）

このリポジトリは旧バージョンのBoilerplateです。現在は下記URLで開発しています。

- <https://github.com/hatena/Hatena-Blog-Theme-Boilerplate>

<hr>

Boilerplate は、はてなブログのデザインCSSカスタマイズの土台に適したデザインテーマです。

はてなブログの必要最小限の見た目が調整されています。このテーマをもとにしてCSSを書くと比較的楽にデザインテーマが作れます。  
「オリジナルテーマの制作にチャレンジしたいけど、0から作るのが大変」という方は、このデザインテーマをもとにしてCSSを書くと比較的楽にテーマが作れます。

# 構成

LESSで書かれています。LESSの知識のある方は、`boilerplate.less`を編集してください。LESSを使わない場合は`boilerplate.css`を編集してください。

ファイルの概要は下記のとおりです。

* boilerplate.less
    * 基本となるスタイルが書かれているLESSファイルです。加えて、下記の4つのLESSファイルを読み込んでいます。
* _mixin.less
    * ミックスインです。主にCSS3でベンダープレフィックスが含まれるプロパティを簡単に記述できるようにしています。
* _variable.less
    * テーマで使っている色に関する変数です。
* _media-queries.less
    * media queries に関するスタイルです。
* _normalize.less
    * <a href="http://necolas.github.com/normalize.css/">normalize.css</a>です。


# ライセンス
 
このCSSおよびLESSファイルはMITライセンスのもと自由に複製・再配布できます。
記事本文の書式やコメント欄のスタイルなど、必要な部分だけをコピーして使ってもかまいません。
このデザインテーマをもとにしたテーマの配布も自由です。