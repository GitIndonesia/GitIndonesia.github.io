# [GitIndonesia.github.io](http://gitindonesia.github.io)
Source code Homepage Komunitas Git Indonesia.

Project ini dibangun dengan bantuan dari

  * [Bootstrap](https://github.com/twbs/bootstrap)
  * [Jekyll](https://github.com/jekyll/jekyll)

## Persyaratan
- Ruby (`v1.9.3` atau keatas untuk `Jekyll 2` dan `v2` atau keatas untuk `Jekyll 3`)
- [RubyGems](http://rubygems.org/pages/download)
- Linux, Unix, or Mac OS X
- Git

## Membangun situs
```shell
gem install bundler --no-ri --no-rdoc
bundle install
bundle exec jekyll clean
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
