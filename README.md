Dcat-Admin 登录 Google 2FA两步验证 / Dcat-Admin auth verification by Google 2FA
======

![StyleCI build status](https://github.styleci.io/repos/686662708/shield)

Dcat-Admin 登录 Google 2FA两步验证

![image](https://github.com/asundust/auth-captcha/assets/6573979/9d3283ea-2cb4-4ce1-9eff-10ce0b82d41e)

### 重要说明！！！

- 本包依赖于[pragmarx/google2fa-qrcode](https://packagist.org/packages/pragmarx/google2fa-qrcode)，该包的二维码依赖是可选扩展包，默认支持[bacon/bacon-qr-code](https://packagist.org/packages/bacon/bacon-qr-code)、[chillerlan/php-qrcode](https://packagist.org/packages/chillerlan/php-qrcode)扩展，需要手动安装，为了兼容性考虑，请选择下方的其中一个扩展安装即可。
- 以上参见说明：[#3](https://github.com/asundust/dcat-auth-google-2fa/issues/3) [https://github.com/antonioribeiro/google2fa-qrcode#built-in-qrcode-rendering-services](https://github.com/antonioribeiro/google2fa-qrcode#built-in-qrcode-rendering-services)
```
composer require bacon/bacon-qr-code
```
```
composer require chillerlan/php-qrcode
```

### 安装

```
composer require longchen2/dcat-auth-google-2fa
```

### 说明

- 本应用暂不支持Dact-Admin`1.*`版本，也不考虑支持。
- Dact-Admin`1.*`版本可以使用[https://github.com/changzhong/extension-google-authenticator](https://github.com/changzhong/extension-google-authenticator)
- 本项目也是因为看到目前插件空缺才补上，代码参考上述项目。

### 主要功能

- 登录页谷歌2FA认证
- 支持自助绑定解绑
- 管理员可以绑定解绑
- 支持简体中文及英语

### License

[The MIT License (MIT)](https://opensource.org/licenses/MIT)
