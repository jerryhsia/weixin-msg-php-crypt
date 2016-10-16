# weixin-msg-php-crypt
微信消息加解密PHP套件，composer封装。

## 安装

`composer require --prefer-dist "jerryhsia/weixin-msg-php-crypt" "dev-master"`

## 注意事项

- Sample.php提供了示例以供开发者参考。errorCode.php, pkcs7Encoder.php, sha1.php, xmlparse.php文件是实现这个类的辅助类，开发者无须关心其具体实现。
- WXBizMsgCrypt类封装了 DecryptMsg, EncryptMsg两个接口，分别用于开发者解密以及开发者回复消息的加密。使用方法可以参考Sample.php文件。
- 加解密协议请参考微信公众平台官方文档。
