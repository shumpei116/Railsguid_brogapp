# README

使い方
このアプリケーションを動かす場合は、まずはリポジトリを手元にクローンしてください。 その後、次のコマンドで必要になる RubyGems をインストールします。
Ruby version:2.7.2

$ bundle install --without production
Yarnというプログラムをダウンロードします。

$ source <(curl -sL https://cdn.learnenough.com/yarn_install)
エラーが出る場合にはメッセージの指示に従って下記を実行します。

$ yarn install --check-files
その後、データベースへのマイグレーションを実行します。

$ rails db:migrate
最後に、テストを実行してうまく動いているかどうか確認してください。

$ rails server
c9コマンドを使うには
