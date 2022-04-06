# jksb

适配了 GitHub Actions，可以实现每天定时运行，并使用微信发送运行结果。

**经过简单测试，已经可以正常运行**

## 技术方案

python+selenium+firefox。

## 项目配置

首先 Fork ，之后前往 Settings-Secrets 填写下列信息，注意需要大写。
| NETID | PASSWORD | SEND_KEY             | RECURL(可选)                                            |
| ----- | -------- | -------------------- | -------------------------------------------------- |
| NETID | 密码     | [Server酱](https://sct.ftqq.com/sendkey) 绑定微信，并获取SendKey用于微信通知申报情况| [第三方在线识别平台](http://fast.95man.com)获取api地址识别验证码 |





## 免责声明

此脚本仅供学习交流，禁止商业使用，使用软件过程中，发生意外造成的损失由使用者承担。如遇身体不适、或居住地址发生变化，请及时更新健康申报信息。



