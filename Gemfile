# coding: utf-8
if ENV['DEV_ENV']
  source 'http://ruby.taobao.org/'
else
  source 'https://rubygems.org/'
end

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2'

# Use SCSS for stylesheets
# gem 'sass-rails', '~> 4.0.3'
# Use CoffeeScript for .js.coffee assets and views
# gem 'coffee-rails', '~> 4.0.0'
# Use jquery as the JavaScript library
# gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
# gem 'turbolinks'

# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer',  platforms: :ruby
# Use Uglifier as compressor for JavaScript assets
# gem 'uglifier', '>= 1.3.0'
# bundle exec rake doc:rails generates the API under doc/api.
# gem 'sdoc', '~> 0.4.0',          group: :doc

# Build JSON APIs
gem 'rabl'
# 模板引擎
gem 'haml'
# Mailgun RoR adapter
gem 'mailgun_rails'
# 支持 CORS
gem 'rack-cors', :require => 'rack/cors'
# 模型字段值枚举
gem 'enumerize'
# 用来分页
gem 'kaminari'
# 定时任务
gem 'whenever', require: false
# PostgreSQL 驱动
gem 'pg'
# 国际化辅助
gem 'rails-i18n'
# 身份验证
gem 'jwt'
# 请求头的 accept-language 信息
gem 'http_accept_language'
# 用填充 deleted_at 替代真正删除数据
gem "paranoia", "~> 2.0"
# 配置文件封装
gem 'settingslogic'
# 图片上传
gem 'rest-client'
gem 'ruby-filemagic'
gem "fog", "~> 1.27"
gem 'carrierwave', github: 'carrierwaveuploader/carrierwave'
gem 'carrierwave-upyun'
# 邮件地址格式验证
gem 'valid_email'
# 消息队列
gem 'delayed_job_active_record'

group :development, :test do
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem "spring-commands-rspec"
  # 自动重启服务
  gem 'guard-rails'
  # 用来给模型声明数据库结构的工具
  gem 'guard-annotate'
  # 用来生成外键迁移的工具
  gem 'immigrant'

  # 调试
  gem 'pry'
  gem 'pry-nav'
  gem 'web-console', '~> 2.0'

  # 测试框架
  gem 'rspec-rails'
  # 扩展 rspec ，增加 2.x 版本中的 its 方法
  gem 'rspec-its'
  # expect().to receive
  gem 'rspec-mocks'
  # 邮件测试的常用匹配器
  # https://github.com/bmabey/email-spec/
  gem 'email_spec'

  # 加速测试
  # gem 'spork-rails'
  # 测试数据预构件
  gem 'factory_girl_rails'
  # 自动测试
  gem 'guard-rspec'
  # 常用的 mock 数据生成
  # https://github.com/stympy/faker
  gem 'ffaker'
end

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use unicorn as the app server
gem 'unicorn'

# Collect errors
gem "sentry-raven"

# Use Capistrano for deployment
gem 'capistrano', '~> 3.1.0'
# Rails specific capistrano functions
gem 'capistrano-rails', '~> 1.1.0'
# Integrate bundler with capistrano
gem 'capistrano-bundler'
# Integrate rbenv with capistrano
gem 'capistrano-rbenv', '~> 2.0'
# Deployment should never fail because of forgot to create a deployment directory
gem 'capistrano-safe-deploy-to', '~> 1.1.1'
# Automatic install specificed ruby
gem 'capistrano-rbenv-install'
group :development do
  # For delayed_job
  gem 'capistrano-delayed-job', github: 'bolasblack/capistrano-delayed-job', branch: 'master'
  # Automatic and sensible unicorn + nginx configuraion.
  gem 'capistrano-unicorn-nginx', github: 'bolasblack/capistrano-unicorn-nginx', branch: 'master'
  # Abstracts and speeds up common administration tasks for PostgreSQL
  gem 'capistrano-postgresql', '~> 3.0'
end

# Use debugger
# gem 'debugger', group: [:development, :test]
