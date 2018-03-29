Laravel 繁簡轉換 (5.3 版本)
===============

# 安裝方式

1. composer require easter1021/laravel5-zhconverter
2. 在 config/app.php 'aliases' 中加入 'ZhConvert' => Easter1021\LaravelZhconverter\LaravelZhconverter::class,
3. use ZhConvert;

# 使用方式

```
// 簡 to 繁
ZhConvert::translate('无疑，这个村子弥漫着一种懒散而颓废的感觉','TW');

// 繁 to 簡
ZhConvert::translate('我是一個不大會拒絕人的人，看著這個中年人','CN');
```

# 注意事項

1. 目前只支援UTF-8

# 資料來源

繁簡字來源：http://www.mediawiki.org/wiki/MediaWiki
