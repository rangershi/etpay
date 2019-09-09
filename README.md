MorningPay是全球领先的数字资产支付平台，旨在为第三方平台提供快速接入区块链支付服务，实现数字货币资产最快速、最安全的流通，让商户释放精力更加专注于自身的业务开发，而不再需要费时费力的去实现各种公链的支付。 
MorningPay适用于各种规模的交易所、钱包、区块链游戏等相关应用。

**目录说明：**
### 1、doc
详细开发文档。[下载](https://github.com/eostoken/morningpay/raw/master/doc/MorningPay%E5%BC%80%E5%8F%91%E6%96%87%E6%A1%A3.docx)

### 2、morningPayTools
morningPayTools源代码Project。用于生成私钥和相关公钥配置信息，用于初始化商户MorningPay配置。
可以自行打包jar或直接运行com.moringpay.Main类生成基本配置，也可以直接[下载](https://github.com/eostoken/morningpay/raw/master/bin/morningPayTools.jar)已经打包的jar包。
jar包执行：
```
java -jar morningPayTools.jar>data.txt 
```
在当前目录找到data.txt，里面内容生成结果。

### 3、morningPaySDK
java版sdk及Demo。
需要修改com.morningpay.config.Config类中相关配置。

### 4、bin
存放morningPayTools打包为jar的文件morningPayTools.jar。