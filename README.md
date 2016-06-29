# [GitIndonesia.github.io](http://gitindonesia.github.io)
[![Build Status](https://img.shields.io/travis/GitIndonesia/GitIndonesia.github.io/master.svg?style=flat-square)](https://travis-ci.org/GitIndonesia/GitIndonesia.github.io)

![Built With Love](http://forthebadge.com/images/badges/built-with-love.svg)
![Makes People Smile](http://forthebadge.com/images/badges/makes-people-smile.svg)

Source code Homepage Komunitas Git Indonesia.
<br>
Project ini dibangun dengan bantuan dari

  * [Bootstrap](https://github.com/twbs/bootstrap)
  * [Jekyll](https://github.com/jekyll/jekyll)

## Persyaratan
- Ruby >= 2.0
- [RubyGems](http://rubygems.org/pages/download)
- Jekyll >= 3.0
- Git

## Membangun situs
```shell
# Install dependencies
gem install bundler --no-ri --no-rdoc
bundle install

# Eksekusi perintah jekyll
bundle exec jekyll clean
bundle exec jekyll build
bundle exec jekyll serve

# Buka browser dengan alamat http://localhost:4000
#   tekan CTRL+C untuk mengakhiri serve
```

## Validasi HTML (htmlproofer)
[`HTMLProofer`](https://github.com/gjtorikian/html-proofer) adalah serangkaian tes untuk memvalidasi hasil HTML Anda. Tes ini memeriksa apakah referensi gambar Anda adalah sah, apakah tag alt ada, apakah link internal ada, dan sebagainya.

Untuk validasi berkas lokal, pastikan situs sudah dibangun dengan `bundle exec jekyll build` sudah dieksekusi.
```shell
bundle exec htmlproofer ./_site --disable-external --assume-extension --allow-hash-href --check-html
```
Validasi ini terdapat pada travis-ci dan otomatis mengeksekusi validasi setiap ada push ke repo. [Cek status](https://travis-ci.org/GitIndonesia/GitIndonesia.github.io).

## Kontribusi
Feel free.
