# 作成したサービス内容  
「プログラミング用のタイピングゲーム」
覚えたいプログラミングの構文などを登録し、それを速く正確に打つことができたかを計るゲーム。
点数が高ければ速く、正確に打つことができた事になる。

## なぜこのサービスをつくったか
プログラミングを勉強していくなかで感じたことに、タイピングの速さや、思いついた基本的な構文を性格に瞬時に書くことができると、勉強がより
効率的になるということ。そこで、自分が曖昧だと思う構文を自分で登録し、練習できるようになれば、プログラミング初心者の勉強がより捗る
のではないかと考えたため、このサービスを作成した。



## 使用しているフレームワーク・データベース
Laravel 5.8.37  
Vue.js 2.5.17  
MAMP 5.5

## 実装した機能
ユーザー登録機能  
ログイン機能  
ログアウト機能  
問題登録機能  
問題編集機能  
問題一覧表示機能  
問題削除機能  
問題練習機能  
マイページ  
認証機能  
ページネーション機能

## どのようにしたら使えるか  
①MAMPをインストールし、その中のhtdocsの中に今回私が作ったLaravelプロジェクトを作る。  
インストールの仕方は、下記を参考↓  
https://qiita.com/kuro-wassan/items/1cb32995acc07a4b4cc6  
  
Laravelプロジェクトの作成方法は下記を参考↓  
https://readouble.com/laravel/5.8/ja/installation.html  
  
②ターミナルで、先ほど作ったLaravelプロジェクトのディレクトリに移動し  
```$xslt
php artisan serve
```
を実行。  
  
その後、ターミナルに
```$xslt
http://127.0.0.1:8000
```
と表示されるため、ブラウザでそのURLを入力。すると、laravelで作成したアプリがブラウザに現れる。  
  
③加えてVueを使えるようにするために、ターミナルにて、作成したプロフェクトのディレクトリ上で
```$xslt
npm install
```
を実行。  

④npm installが成功したら、Vueを反映させるために、ターミナルで（ディレクトリはそのまま）  
```$xslt
npm run dev
```
も実行。
  
①〜④が成功すればこのアプリを使うことができる。


