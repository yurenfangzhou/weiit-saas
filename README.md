
# SAAS微信小程序电商-开源项目[weiit-saas]

weiit-saas是一款Java开源项目，属于weiit团队自研产品，意在通过技术封装，让企业无需代码开发，帮助企业一键生成小程序、公众号，让企业拥有独立品牌的自营商城。产品竞争对手《有赞》、《微盟》。

## 最新下载
-  gitee开源地址：[https://gitee.com/wei-it/weiit-saas](https://gitee.com/wei-it/weiit-saas)
-  github开源地址：[https://github.com/HalfMouse/weiit-saas](https://github.com/HalfMouse/weiit-saas)
## 一、引言

 
 -  目前系统能解决的[**主要问题**](https://my.oschina.net/oyxm0/blog/4776398)
 -  **2016年3月**weiit团队推出SAAS电商1.0版本，帮助20家企业完成独立品牌商城上线，成功接入微信；
 -  **2017年6月** weiit团队启动2.0版本开发，主打**小程序**一键生成，并获得部分企业付费支持；
 -  **2018年5月** weiit团队研发成功并上线SAAS电商2.0版本，快速获得200多家企业使用与支持；
 -  **2018年到2019年**weiit团队研发经费无法持续，放弃SAAS系统持续迭代，转型做技术服务商；
 -  **2020年** weiit团队宣布，SAAS电商产品免费开源，让圈内的技术大佬一起学习与交流；
 - weiit团队承诺“weiit-saas”系统完全开源，跟喜欢研究SAAS概念的技术大佬交流与学习成长。
 
 
 
## 二、主要特点


 - 项目采用**Spring+SpringMVC+Mybatis**主流开源框架，遵循MVC架构，设计轻巧，使用简单，开发人员接手与二次开发简单易懂；
 - 项目依赖的**核心支持jar包**，都已经完全开源
 - 项目完成了对阿里云、腾讯云、微信生态的快速接入与代码示例，并成功运用到了商业中，方便大家学习对**OSS/COS/短信服务/快递服务/公众号/小程序/微信开放平台/微信支付**的技术点与应用场景的学习。
 - 小程序与公众号第三方授权集成，让开发者与企业省去繁琐的配置，对**AppId/AppSecret**集成彻底告别。
 - 微信支付**第三方授权**集成，让开发者与企业省去繁琐的配置，让企业服务成本大大降低。
 - 小程序**代码自动push与升级**，公众号基本常规功能（**自定义菜单、图文、素材，群发**）全部接管，让企业无需登录微信官方入口，统一化管理企业信息与数据。
 - 微信**消息通知与模板**自动同步与管理，让企业场景融合无障碍。
 - 像**淘宝装修**一样的自定义装修功能，实现企业电商场景多元化，解决不同行业不同模板，让企业需求得到真正解决。
 - 丰富的**营销工具**，解决企业微营销需求，并集中化管理。拼团活动、积分活动、砍价活动等等，方便二次开发。
 - 不同企业数据隔离，真正实现SAAS数据隔离模型，让企业数据互不干扰。
 - 不同企业不同域名自动分配，让企业小程序、公众号前端隔离，避免因为公众号或者小程序推广时导致域名被检测导致的封号问题出现，即不同企业不同域，意在防止saas平台中的企业受到其他企业的影响。



## 三、Maven仓库

 - maven仓库依赖的核心jar包项目，gitee开源地址：[https://gitee.com/wei-it/weiit-frame](https://gitee.com/wei-it/weiit-frame)
 - maven仓库依赖的核心jar包项目，github开源地址：[https://github.com/HalfMouse/weiit-frame](https://github.com/HalfMouse/weiit-frame)

weiit-saas系统依赖jar支持1：
```maven
 <dependency>
    <groupId>com.weiit</groupId>
    <artifactId>weiit-support-core</artifactId>
    <version>1.0.0</version>
</dependency>
```

weiit-saas系统依赖jar支持2：
```maven
 <dependency>
    <groupId>com.weiit</groupId>
    <artifactId>weiit-resource-common</artifactId>
    <version>1.0.0</version>
</dependency>
```

weiit-saas系统依赖jar支持3：
```maven
 <dependency>
    <groupId>com.weiit</groupId>
    <artifactId>weiit-suppor-task</artifactId>
    <version>1.0.0</version>
</dependency>
```



## 四、演示地址


一、测试环境演示：

| 用户端 | 演示地址 |测试账户 |
|--|--|--|
| 商家端|http://saasmerchant.wei-it.com/  |18306668080   123456 |
| 渠道端|http://saasplatform.wei-it.com/  |qudao  123456 |
| 平台端|http://saasplatform.wei-it.com/  |pingtai 123456 |


二、生产环境演示：

| 用户端 | 演示地址 |测试账户 |
|--|--|--|
| 商家端|http://www.wstore.me  |18339835117   123456 |
| 渠道端|  |不提供演示|
| 平台端|  |不提供演示|
| 用户端|  |小程序搜索“衣家好店” |


三、成功案例：

<img src="https://weiit.oss-cn-shenzhen.aliyuncs.com//weiit/2020-12-01/a2f7387e-29ff-4890-8917-64a174f1dc85.png"  width="150" height="150"  />
<img src="https://weiit.oss-cn-shenzhen.aliyuncs.com//weiit/2020-12-01/2c7b2c24-ca20-4cd7-8d23-a06b7c216ba8.png"  width="150" height="150"  />
<img src="https://weiit.oss-cn-shenzhen.aliyuncs.com//weiit/2020-12-01/4e4b1d4c-1459-4acb-b7e1-f70862768edb.jpg"  width="150" height="150"  />
<img src="https://weiit.oss-cn-shenzhen.aliyuncs.com//weiit/2020-12-01/a0621572-8c28-4a20-8746-97d8a3096e1d.jpg"  width="150" height="150"  />
<img src="https://weiit.oss-cn-shenzhen.aliyuncs.com//weiit/2020-12-01/f3301cbe-7272-44c4-bb1e-98d771d80c02.jpg"  width="150" height="150"  />




## 五、系统功能



![avatar](https://weiit.oss-cn-shenzhen.aliyuncs.com/weiit/2020-11-20/90362bf9-3456-482d-98eb-338e71e35020.png)
![avatar](https://weiit.oss-cn-shenzhen.aliyuncs.com/weiit/2020-11-20/4b0e5dc0-4581-471f-b2dd-fab55fee2b13.png)
![avatar](https://weiit.oss-cn-shenzhen.aliyuncs.com/weiit/2020-11-20/ce68d706-ebc2-4090-9aa2-1c1f82739680.png)
![avatar](https://weiit.oss-cn-shenzhen.aliyuncs.com/weiit/2020-11-20/a6123bc3-03e0-43ab-99cf-1049fd20168a.png)
![avatar](https://weiit.oss-cn-shenzhen.aliyuncs.com/weiit/2020-11-20/ceae7982-db9e-42d4-b60c-3f1796f6e88d.png)
![avatar](https://weiit.oss-cn-shenzhen.aliyuncs.com/weiit/2020-11-20/63dbe1b8-56a8-498d-a92f-9af19966c2c9.png)
![avatar](https://weiit.oss-cn-shenzhen.aliyuncs.com/weiit/2020-11-20/c843515c-1801-4620-9b5c-e3ea54fe0b33.png)
![avatar](https://weiit.oss-cn-shenzhen.aliyuncs.com/weiit/2020-11-20/dadbcd1a-7ef2-405f-a887-657cce035e50.png)
![avatar](https://weiit.oss-cn-shenzhen.aliyuncs.com/weiit/2020-11-23/56f75e5e-384c-42a6-b18d-3f304feb5109.png)
![avatar](https://weiit.oss-cn-shenzhen.aliyuncs.com/weiit/2020-11-23/a226cbb2-0a24-4442-b66d-daba945f6cf2.png)
![avatar](https://weiit.oss-cn-shenzhen.aliyuncs.com/weiit/2020-11-23/4c8e646b-b352-437d-a741-8c8817767298.png)
![avatar](https://weiit.oss-cn-shenzhen.aliyuncs.com/weiit/2020-11-20/de60d77f-51fe-4044-8ab4-3b1e295632ba.png)
![avatar](https://weiit.oss-cn-shenzhen.aliyuncs.com/weiit/2020-11-20/01d5c0e8-2097-4bda-9b51-e74a4fb63f48.png)
![avatar](https://weiit.oss-cn-shenzhen.aliyuncs.com/weiit/2020-11-20/ff0ea0c2-5e8d-42ef-b7f6-6786354b809d.png)
![avatar](https://weiit.oss-cn-shenzhen.aliyuncs.com/weiit/2020-11-23/cc0c9f83-0f93-4563-b45a-cef4a58eefe8.png)

![avatar](https://weiit.oss-cn-shenzhen.aliyuncs.com/weiit/2020-11-21/206a4140-b661-4b57-9d7a-4ecec9c06141.png)
![avatar](https://weiit.oss-cn-shenzhen.aliyuncs.com/weiit/2020-11-21/8ecce496-5bae-460b-a4d1-6655d6e1b007.png)
![avatar](https://weiit.oss-cn-shenzhen.aliyuncs.com/weiit/2020-11-21/370f9fb7-d524-4096-a28e-be45a39f720c.png)
![avatar](https://weiit.oss-cn-shenzhen.aliyuncs.com/weiit/2020-11-21/f6a0ef21-846b-430d-856b-d40be56fc267.png)
![avatar](https://weiit.oss-cn-shenzhen.aliyuncs.com/weiit/2020-11-21/3a0aea35-d57b-43e4-aab8-665bbba1f6ab.png)
![avatar](https://weiit.oss-cn-shenzhen.aliyuncs.com/weiit/2020-11-21/14e16c48-ea39-4cf8-8db1-67c1e67a7945.png)
![avatar](https://weiit.oss-cn-shenzhen.aliyuncs.com/weiit/2020-11-21/14e16c48-ea39-4cf8-8db1-67c1e67a7945.png)
![avatar](https://weiit.oss-cn-shenzhen.aliyuncs.com/weiit/2020-11-21/c611ca08-6058-4471-9751-f5998b510765.png)
![avatar](https://weiit.oss-cn-shenzhen.aliyuncs.com/weiit/2020-11-21/208f185f-b738-4928-8fa4-c3f99fe693ba.png)
![avatar](https://weiit.oss-cn-shenzhen.aliyuncs.com/weiit/2020-11-21/8ebe503a-25f4-41c7-a7c7-d11f74d6bc6b.png)
![avatar](https://weiit.oss-cn-shenzhen.aliyuncs.com/weiit/2020-11-21/d7cccb53-a06b-431e-816c-a030f8e69e96.png)
![avatar](https://weiit.oss-cn-shenzhen.aliyuncs.com/weiit/2020-11-21/4a49e10b-f2ab-427c-a342-c015add1a87d.png)
![avatar](https://weiit.oss-cn-shenzhen.aliyuncs.com/weiit/2020-11-21/f3aa81c6-45c2-48fc-9175-476f8d95cfae.png)
![avatar](https://weiit.oss-cn-shenzhen.aliyuncs.com/weiit/2020-11-21/24199145-e964-4d45-94f9-8e87add7d841.png)
![avatar](https://weiit.oss-cn-shenzhen.aliyuncs.com/weiit/2020-11-21/82f86f59-84c9-4b7b-b4cd-492a233827c5.png)
![avatar](https://weiit.oss-cn-shenzhen.aliyuncs.com/weiit/2020-11-21/48f8995a-c2a1-46c3-8dd2-e4bce5540e7d.png)



## 六、系统核心
![avatar](https://weiit.oss-cn-shenzhen.aliyuncs.com/weiit/2020-12-07/1d247d67-a6b4-4c0b-a87c-9f7f318ab499.jpg)
详情：[系统核心](https://www.processon.com/view/link/5fca03875653bb7d2b2b1c11)

## 七、技术支持

weiit开源技术1群（已满）

加的时候请备注一下，我拉你进1群。

![avatar](https://weiit.oss-cn-shenzhen.aliyuncs.com/weiit/2021-03-12/08917164-20ad-4e5e-933f-a9dc339693fe.jpeg)



