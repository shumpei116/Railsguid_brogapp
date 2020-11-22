# README

使い方
このアプリケーションを動かす場合は、まずはリポジトリを手元にクローンしてください。 その後、次のコマンドで必要になる RubyGems をインストールします。
Ruby version:2.7.2

$ bundle install --without production

Yarnというプログラムをダウンロードします。

$ yarn install --check-files

その後、データベースへのマイグレーションを実行します。

$ rails db:migrate


サーバーを立ち上げてください。

$ rails server

