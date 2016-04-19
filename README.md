# [GitIndonesia.github.io](http://gitindonesia.github.io)
[![Build Status](https://img.shields.io/travis/GitIndonesia/GitIndonesia.github.io/master.svg?style=flat-square)](https://travis-ci.org/GitIndonesia/GitIndonesia.github.io)

Source code Homepage Komunitas Git Indonesia.

Project ini dibangun dengan bantuan dari

  * [Bootstrap](https://github.com/twbs/bootstrap)
  * [Jekyll](https://github.com/jekyll/jekyll)

## Persyaratan
- Ruby >= 2.0
- [RubyGems](http://rubygems.org/pages/download)
- Jekyll >= 3.0
- Git
- Linux, Unix, atau Mac OS X

## Membangun situs
```shell
gem install bundler --no-ri --no-rdoc
bundle install
bundle exec jekyll clean
bundle exec jekyll build
bundle exec jekyll serve
# Buka browser dengan alamat http://localhost:4000
```

## Deploy
```shell
git add -u
git add .
git commit -m 'Pesan'
git push
```

## Kontribusi
Fell free.
