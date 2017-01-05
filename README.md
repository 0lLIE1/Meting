# Meting

![](http://ww2.sinaimg.cn/large/a15b4afegw1fbg1l7wn09j20fw05gq34)

 > :lollipop:Wow, such a powerful music API framework

## Introduction
A powerful music API framework to accelerate development

 + **Easy** - Easy to use, suppose format return.
 + **Light** - 30KB around with only one file.
 + **Powerful** - Suppose various webserver, include netease, tencent, xiami, kugou, baidu and more.
 + **Free** - Under MIT license, you can use it anywhere if you want.

## Get Started

### Install via composer
It is RC version now.

coming soon...

### Install via require
```php
// if you just download the Meting.php into directory, require it with the correct path.
require_once 'Meting.php';
```

```php
// Initialize to netease API
$API = new Meting('netease');

// Enjoy
$data = $API->format(true)->search('Soldier');
```

## Demo
```bash
$ git clone https://github.com/metowolf/NeteaseCloudMusicApi.git
$ cd Meting
$ php -S 127.0.0.1:8080
```
open http://127.0.0.1:8080/demo/simple-test

## License
Meting is under the MIT license.

## Links
Official website: https://i-meto.com

Demo: https://music.i-meto.com

Documentation (unfinished): https://music.i-meto.com/docs
