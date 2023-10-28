# HamCQIP

A [Flarum](http://flarum.org) extension.修复因为使用阿里CDN的IP显示问题 fix ip addr when use ali cdn

## Installation

Install with composer:

```sh
composer require hamcq/flaurm-ext-ip:"*"
```

## Updating

```sh
composer update hamcq/flaurm-ext-ip:"*"
php flarum migrate
php flarum cache:clear
```
