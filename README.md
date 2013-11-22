# Ruby on Rails チュートリアル：サンプルアプリケーション

これは以下で使用する最初のアプリケーションです。
[*Ruby on Rails Tutorial: Learn Rails by Example*](http://railstutorial.jp/)
by [Michael Hartl](http://michaelhartl.com/).

herokuにデプロイ時は以下2つを追加してgit pushする必要あり。

config/application.rb:
config.assets.initialize_on_precompile = false

config/database.yml:
   adapter: postgresql
   encoding: utf-8
   database:
   username:
   password: 
