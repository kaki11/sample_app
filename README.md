# Ruby on Rails チュートリアルのサンプルアプリケーション

これは、次の教材で作られたサンプルアプリケーションです。
[*Ruby on Rails チュートリアル*](http://railstutorial.jp/)
[Michael Hartl](http://www.michaelhartl.com/)著

## ライセンス

[Ruby on Rails チュートリアル](http://railstutorial.jp/)内にあるソースコードはMITライセンスとBeerwareライセンスの元で公開されています。
詳細は[LICENSE.md](LICENSE.md)をご覧ください。

## 使い方

このアプリケーションを動かす場合は、まずリポジトリを手元にクローンして下さい。
その後、次のコマンドで必要になるRubyGemsをインストールします。

```
$ bundle install --without production
```

その後、データベースのマイグレーションを実行します。

```
$ rails db:migrate
```

最後に、テストを実行してうまく動いているかどうか確認してください。

```
$ rails test
```

テストが無事に通ったら、Railsサーバーを立ち上げる準備が整っているはずです。

```
$ rails server
```

詳しくは、[*Ruby on Rails チュートリアル*](http://railstutorial.jp/)を参考にして下さい。