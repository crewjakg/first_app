source 'https://rubygems.org'
ruby '2.1.2'
#ruby-gemset=railstutorial_rails_4_1

group :default do
	gem 'rails', '4.1.5'
	gem 'sass-rails', '~> 4.0.3'
	gem 'uglifier', '>= 1.3.0'
	gem 'coffee-rails', '~> 4.0.0'
	gem 'therubyracer',  platforms: :ruby
	gem 'jquery-rails'
	gem 'turbolinks'
	gem 'jbuilder', '~> 2.0'
	gem 'bcrypt', '~> 3.1.7'
	gem 'will_paginate', '~> 3.0'  # ページネーション機能
	gem 'haml'
	gem 'enum_help' #共用体を使用することが出来る
#	gem 'rails-assets-hogehoge'  #bandlerでjavascriptを管理する
	                             #
end

group :development, :test do
	gem 'sqlite3'
	gem 'awesome_print'  #ハッシュなどを読みやすくする メソッド apにobjectを渡す
	gem 'tapp'

end

group :development do
	gem 'spring'
	gem 'pry-rails'
	gem 'pry-doc'
	gem 'pry-stack_explorer'
	gem 'pry-byebug'
end

group :development do
	gem 'better_errors'
	gem 'binding_of_caller'
	gem 'rack-mini-profiler'  #処理速度を計測するために使用
	gem 'bullet'
	gem 'quiet_assets'
	gem 'annotate'
end

group :production do
  gem 'pg', '0.15.1'
  gem 'rails_12factor', '0.0.2'
end

group :doc do
	gem 'sdoc', '~> 0.4.0'
end
