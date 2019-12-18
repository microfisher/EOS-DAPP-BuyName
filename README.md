# EOS短账号销售游戏
主要用于购买.e结尾的EOS短号靓号，支持推荐分红、客户返利等等。

![EOS短号销售网站](
https://github.com/microfisher/EOS-DAPP-BuyName/blob/master/website.jpg)

## 智能合约

开发语言：C++

## 游戏规则

#### 销售短号
* 支持两种买号方式（向智能合约按规则转账、EOS钱包直接购买），自动抵押CPU、RAM、NET资源，可设置抵押数额及比例。
* 按单价向账号e转账，备注内填写要注册的账号 + 公钥 转账成功即可自动完成注册
* 例：12345.e+EOS5sCkZ18dWaWVjL2YTn2kLZnNEpGuMsteGMaUJLpKL1BMCuH19H

#### 推荐分红
* 转账0.123eos到账号buyname.io即可，您的付款账号将成为分红收款账号。同时您的付款账号将收到一个由账号buyname.io发送的6位推荐码。
* 你获得分红=（单价5.7-客户返利假设为0-ram成本0.29）*25%默认比例=1.35eos
* 分红由智能合约自动转入你的收款账号

* `推荐方法一：
推荐链接注册：“.e超短账号注册 http://eos58.io/eostothemoon/你的推荐码”
复制保存以上内容与推荐链接，以随时发送给您的朋友注册。`

* `推荐方法二：
推荐转账注册：让您的朋友向账号e转账，并在备注内填写：要注册的账号+公钥+6位推荐码
例如：12345.e+EOS5sCkZ18dWaWVjL2YTn2kLZnNEpGuMsteGMaUJLpKL1BMCuH19H+112233`


#### 客户返利
* 每位推荐人可以调取账号售价的0-10%进行客户返利，在短账号注册成功后，智能合约会将客户返利自动转账到新注册的账号。
* 用推荐人账号向buyname.io转账0.0001eos，并在备注内填写0-10数字中的任意一个整数，如0为无返利，5为5%返利（如单价5.7eos，则返利=5.7*5%=0.285eos），最多返10%。转账成功即设置成功。

#### 公钥校验
* 公钥填写错误，即使填错一位。
* 要注册的账号位数与价格不对应。
* 转账金额与规定价格不符。
* 要注册的账号已被注册
* 要注册的账号位数不在规定范围
* 备注内容为空。
* 因CPU或RAM不足导致的系统错误。
