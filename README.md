# ionic3-timer

ionic3によるタイマーアプリ

詳細は以下
http://twosquirrel.mints.ne.jp/dokuwiki/doku.php/github上のionic3アプリのインストール#github%E4%B8%8A%E3%81%AE%E3%82%A2%E3%83%97%E3%83%AA%E3%82%92%E3%83%80%E3%82%A6%E3%83%B3%E3%83%AD%E3%83%BC%E3%83%89%E3%81%97%E3%81%A6%E3%82%A4%E3%83%B3%E3%82%B9%E3%83%88%E3%83%BC%E3%83%AB
http://twosquirrel.mints.ne.jp/?p=16984

## Requirement

- Node.js 6.10.2
- Ionic CLI 2.2.2


## Installation

    $ git clone https://github.com/adash333/ionic3-timer.git
    $ cd ionic3-timer
    $ npm install

imageは、  
https://www.photo-ac.com

などからダウンロードして、sakura.jpgという名前に変更して、  
www/assets/img/ フォルダの中に保存。(img/　フォルダがなければ新規作成) 　　

    $ ionic serve

androidアプリの作成(ionic-cli version2.xの場合)

    $ ionic platform add android
    $ ionic build android

androidアプリの作成(ionic-cli version3.xの場合、通常はこちら)

    $ ionic cordova platform add android
    $ ionic cordova build android

エラーが出てうまくいかない場合は、エラーの内容をGoogle検索したり、  
http://qiita.com/567000/items/dc4917027cf060a3e2ea  
を参考になさったりしてください。  
  
(参考)   
http://twosquirrel.mints.ne.jp/?p=15712  
http://twosquirrel.mints.ne.jp/?p=15745  

## Anything Else

このコードは、以下の本の「Chapter 6 イベントドリブンのきほんを学ぼう」のソースコードを参考に、Ionic3アプリに書き直しています。

これからWebをはじめる人のHTML＆CSS、JavaScriptのきほんのきほん Kindle版  
たにぐち まこと (著)  
発売日：2017年03月27日  
https://www.amazon.co.jp/dp/B06XT19H2D/

参考

ionic-cli v3になり、コマンドが変更になっていますので、2017年5月以降は、以下のリンクを参考になさってください。

http://tech.pjin.jp/blog/2017/05/23/ionic3-cli/

## Author

adash333
