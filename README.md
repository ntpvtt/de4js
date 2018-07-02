# Phuong Blog

JavaScript Deobfuscator and Unpacker

## Helper

The **Unreadable** option is disabled by default, because it uses data from [JS Nice](http://www.jsnice.org/). This cannot be done with JavaScript. You need to install UserScript [de4js_helper.user.js](https://github.com/ntpvtt/de4js/blob/master/userscript/de4js_helper.user.js) to enable it.

Install one of the following links:

- [Github](https://github.com/ntpvtt/de4js/raw/master/userscript/de4js_helper.user.js)

## Features

- Source code beautifier / syntax highlighter.
- Make obfuscated code [readable](#helper).
- Performance unpackers:
    - **Eval**, e.g. Packer, [WiseLoop](http://wiseloop.com/demo/php-javascript-obfuscator)
    - **Array**, e.g. Javascript Obfuscator
    - [_Number](http://giapqb.blogspot.com/p/mahoa-javascript.html)
    - [Packer](http://dean.edwards.name/packer/)
    - [Javascript Obfuscator](https://javascriptobfuscator.com/Javascript-Obfuscator.aspx)
    - [My Obfuscate](http://myobfuscate.com/)
    - **URL encode**, e.g. bookmarklet
    - [JSFuck](https://github.com/aemkei/jsfuck)
    - [JJencode](http://utf-8.jp/public/jjencode.html)
    - [AAencode](http://utf-8.jp/public/aaencode.html)

## Development

### Install

    git clone https://github.com/ntpvtt/de4js.git
    cd de4js

If you don't have Ruby installed, install [Ruby 2.1.0 or higher](https://www.ruby-lang.org/en/downloads/).

Fix missing libraries on **Ubuntu**:

    sudo apt install ruby-dev zlib1g-dev

Install **Bundler**:

    gem install bundler

Install **Jekyll** and other [dependencies](https://pages.github.com/versions/) from the GitHub Pages gem:

    bundle install

### Run

    bundle exec jekyll serve

Preview **de4js** in your web browser at `http://localhost:4000`

## License

[MIT License](//www.phuongblog.com/) © [PhuongBlog](https://ntpvtt.github.io/)

## Credits

### Open Source Contributors

- [js-beautify@1.7.3](https://github.com/beautify-web/js-beautify)
- [highlight.js@9.12.0](https://github.com/isagalaev/highlight.js)
- [clipboard.js@1.7.1](https://github.com/zenorocha/clipboard.js)
- [magic-check@1.0.3](https://github.com/forsigner/magic-check)
- [cat-in-136](https://cat-in-136.github.io/2010/12/aadecode-decode-encoded-as-aaencode.html)
- [Decoder-JJEncode](https://github.com/jacobsoo/Decoder-JJEncode)
- [nderscore](https://codegolf.stackexchange.com/a/28745)
