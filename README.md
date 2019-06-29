# 数字货币量化策略交易平台
数字货币-程序化24*365小时自动策略交易PC客户端

[![AppVeyor build status](https://ci.appveyor.com/api/projects/status/github/softethervpn/softethervpn?branch=master&svg=true)](https://ci.appveyor.com/project/softethervpn/softethervpn) [![Travis CI build status](https://travis-ci.org/SoftEtherVPN/SoftEtherVPN.svg?branch=master)](https://travis-ci.org/SoftEtherVPN/SoftEtherVPN) [![gitlab-ci build status](https://gitlab.com/SoftEther/SoftEtherVPN/badges/master/build.svg)](https://gitlab.com/SoftEther/SoftEtherVPN/pipelines) [![Coverity Scan Build Status](https://scan.coverity.com/projects/16304/badge.svg)](https://scan.coverity.com/projects/softethervpn-softethervpn)

- 以所谓的“搬砖”为代表的“数字货币量化交易”在数字货币圈一直是个颇有些神秘色彩的存在，很多人把量化交易视为是币圈闷声发大财的典型代表，认为它是币圈躺着赚钱的捷径之一。但是其实任何一种金融资产，在诞生之初，由于介入的投资者的心理和行为偏见，以及信息的处理速度的的差异，必然会导致大量的跨交易所，跨合约掉期，跨商品(币种)的套利机会，这种机会基于传统经济学里的一价原理，使得掌握了绝对信息和速度优势的机构和个人投资者以几乎无风险的方式在不同的币种和交易所之间来回套利，俗称"割韭菜"模式。

- 数字货币的诞生，是区块链发展的一个落地的应用之一。如果我们仅仅只是把数字货币当成一种和传统金融衍生品一样的投机产品去交易的话，那么无论是技术分析，还是行为心理分析，还是基本面供需分析，都是同样适用的。

- 传统的金融衍生品诸如股票，期货，外汇，债券，都有大量的第三方量化程序化软件的支持，这些软件除了能够提供行情，图表，最重要的是提供一个策略编辑环境，以供普通投资者可以在软件上进行策略开发，这些策略包括统计策略，套利策略，技术分析下的策略，等等，在计算机的帮助下，完成全年365*24小时不间断的执行交易，帮助投资者在行情极速转变以及几乎24小时运行的的金融市场能控制风险的同时，扩大投资标的范围，捕捉更大量的投资机会，获得更大的收益。

- 当前的绝大部分数字货币交易所，无论是Okex，币安，还是bitmex等等，交易的终端基本都是基于Web网页模式，在网页端完成现货币种兑换，合约交易(类似传统金融期货交易)，永续合约(类似传统金融CFDs差价合约交易)交易等。界面只支持图表和下单界面，并没有支持策略交易，量化交易，自动交易，半自动交易，监控，多币种同时交易，投资组合等模块。这给在之前以交易期货和股票和为主交易数字货币的交易者而言，有很大的操作困扰，更有甚者，因为数字货币目前是365*24小时连轴交易，其实策略交易，监控，风控模块，对于数字货币交易者而言是极其紧迫的需要的。

- 因为作者之前所在的金融机构除了交易全球市场外，也在积极拓展新兴市场交易机会,为量化交易员开发数字货币交易终端，以协助交易员更好的完成交易，借此机会，线下也和几个朋友发布一款小型团队的简易版本，不过功能足以协助广大数字货币致力于量化交易的发烧友完成策略自动交易和各类风控管理。

* * *
### 完成授权
*
![image](https://github.com/handayu/AI-Trader-DownLoad/blob/master/image/Licese.png)


### 登陆(用个人申请的APIKey进行登陆)
*
![image](https://github.com/handayu/AI-Trader-DownLoad/blob/master/image/Login.png)

### 策略-半自动交易
![image](https://github.com/handayu/AI-Trader-DownLoad/blob/master/image/Indicator.png)
![image](https://github.com/handayu/AI-Trader-DownLoad/blob/master/image/Strategy.png)
![image](https://github.com/handayu/AI-Trader-DownLoad/blob/master/image/Trade.png)


### 对接国内外Multicharts进行图表和策略交易

### 跨交易所加密数字货币搬砖套利实例
- 横跨Bittrex,BitFinex,PoloNiex,Okex以及币安交易所的套利交易。
- 传统的套利模式很多，这点个人来看，其实和日常生活中的"东边买菜西边卖"没有多少差异，对于价差稳定的品种而言跨期和同市场下的跨交易所套利纯粹是拼硬件，对于价差不稳定的品种而言，近远期逼仓和升贴水成了最大的风险，对于同一个市场下的跨品种套利而言，单品种基本面不稳定成了最大的风险，而对于跨市场而言，汇率相对大资金来说也是有挺大风险的，需要锁汇，但是对于跨市场而言，个人感受是其实是最好的套利交易环境，且风险更加可控，原因有二：
- 1.信息效率差更明显
- 2.跨市场如果参与者的主体结构是个人投资者，羊群效应会更明显，价差的机会更多(尤其数字货币，几乎都是羊毛)；
- 3.品种固定的前提下，相比跨品种会一价原理更稳定；

- 看到,其实在国际最大的数字货币交易平台Bittrex和Bitfinex，以及Poloneix之间对于Btc-Usdt，就有几乎稳定的-100 - +50的价差，并且相当稳定。
- 对于已经存在且交易的的3000多个数字货币对以及上万种不同的数字货币产品，以及几十个不同国家和地域的数字货币交易所而言，这种价差是非常值得尝试的，所以
- 笔者上线传统趋势追踪CTA交易全球期货，CFD,外汇,和美股资产之余，也在开始尝试数字货币的趋势追踪策略,尤其是不同交易所之间的跨交易所套利交易，补充趋势追踪的策略类型。

![image](https://github.com/handayu/AI-Trader-DownLoad/blob/master/image/arbitrage.png)

* * *

### 技术应用？
- ThirdPartySoftWare
- Trade Strategy交易策略
- Edi
- 事件引擎
- Windows Hook
- Net Framework4.6.1


### 参与本项目？

如有兴趣的量化－程序化交易员或者团队:
   请加 QQ：578931169。
   WeChart: hanyu196910
   
   <h3 id="weibo-weixin">微信</h3>
 *「DotNet」：专注 .NET量化交易平台开发，量化交易，程序化交易，投资组合构建。
   <br><img src="https://github.com/handayu/OandaTrading/blob/master/image/wechart.jpg" width=150 height=150>
* * *

