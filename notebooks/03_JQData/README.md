# JQData

> 为了满足用户的需求，聚宽数据团队在JQData中不仅提供了全面的基础金融数据，包括沪深A股行情数据，上市公司财务数据，场内基金数据，场外基金数据，指数数据，期货数据，期权数据以及宏观经济数据；除此之外，JQData还针对因子数据和特色数据，引进了聚宽因子库，舆情数据，Alpha特色因子，技术分析指标因子，tick数据以及百度因子数据，助您更好的完成量化研究和投资决策.

## 申请开通 JQData

> 申请试用账号： 聚宽作为国内量化行业的领军企业，本着推动量化行业快速发展的良好愿景，现已开放试用JQData。想要使用JQData的用户只需[提交试用申请](https://www.joinquant.com/default/index/sdk#jq-sdk-apply)，就能开通JQData一年有效期的试用账号。试用账号在试用期间可免费调用JQData的全部基础数据，每天可调用100万条，具体试用权限如下表所示。（注：JQData基础数据包含沪深A股行情数据，上市公司财务数据，指数数据，场内基金数据，期货数据和宏观经济数据）

## 接口文档

> https://dataapi.joinquant.com/docs

## 安装 JQData

```
pip install jqdatasdk
```

## 登录 JQData

```
from jqdatasdk import *
auth('ID','Password') #ID是申请时所填写的手机号；Password为聚宽官网登录密码，新申请用户默认为手机号后6位

```

