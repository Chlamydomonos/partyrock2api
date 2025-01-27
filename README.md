# Partyrock2api

Fork自https://github.com/cchking/partyrock2api ，略作修改以适配SillyTavern。

只修改了Typescript版本，Python版本仍然不能连接SillyTavern。

Typescript版本是用Deno运行的，运行前先确保安装了Deno。

使用方法见[原README](https://github.com/cchking/partyrock2api/blob/e9cf5676e20a57e7417c1343adb526ca72a6c7db/README.md)

注意，通过上述方法提取到格式为`XXX|||XXX|||XXX`Key后，需要对其进行Base64编码再放到SillyTavern中使用。