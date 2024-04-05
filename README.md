一款边办公边交易的Excel AI Crypto Trading bot量化机器人，完全免费的量化交易平台,与实盘基本接近的回测数据，优化了网格参数和下单逻辑，降低了交易损耗和实现利润的最大化，收益优于80%以上的同类型策略，支持自定义调用交易函数，纯办公环境运行，无需安装额外程序，适合小白量化入门，交易员辅助下单！
注意事项：

1、运行环境：Windows 系统，office2007以后版本或带VBA的WPS基本都可以运行， Excel需启动宏才可以运行Excle trading bot；

2、杀毒软件可能误报，建议关闭杀毒软件，或将okex_exe加入到信任列表，程序无任何后门，请放心使用；

3、务必确保电脑能访问okx.com,如不能访问请设置好科学上网或部分地区修改host也可以；

4、请务删除表格中1-11行中的任何内容，否则将引起软件异常。

5、本软件仅提供封装的交易接口，无法保证收益，所有收益均基于使用者的参数设定，造成的亏损，概不负责。

 

建议先使用模拟交易熟悉软件，下面以模拟交易为例，说明一下如何进行自动策略交易：

1、登录okx网页版打开https://www.okx.com/cn/account/my-api获取API；

2、点击申请交易V5 API，输入密码，勾选交易，切勿勾选提现，以免API泄露导致资金损失，另外可以绑定IP提高API的安全性；

3、打开 策略交易 表格，点击API设置按钮；

4、将API创建页面的API key、密钥和密码分别填入，apikey、apisecre 和PASSHRASE中；

5、选中OKEX主站(实盘交易)或测试站(模拟交易)，点击API设置即成功设置好了API；

6、点击参数设置按钮，在弹窗中设置好策略参数(目前仅支持USDT本位合约，合约代码格式为btc-usdt-swap)；

7、下拉交易策略，选好策略，目前有三个可选策略(网格，类马丁和组合策略)，弹窗右下角点击设置参数；

8、最后点击启动策略按钮，将进行自动策略交易。

![001](https://github.com/aijiebots/office-crypto-bot/assets/166122673/6a0b3241-7c8c-4509-8120-6dfb3cf853e1)


常见问题：

一、支持哪些交易所？


答：目前支持欧易交易所和币安，在excel中即可运行okx trading bot,后续会考虑增加其他交易所

二、excle trading bot手机上可以用吗?
答：excle trading bot软件运行在安装了Excel或wps的个人电脑或windows服务器上，暂时不支持手机。

三、aijiebot策略交易跟交易所的有什么不同？
答：

1、交易所的网格参数设置受限，只支持格数和价格区间的设定，aijiebot是一款真正的ai crypto trading bot； 

2、交易所的网格运行后，开仓和平仓都只能在固定的价格，一旦设定不可更改，而aijiebot可以随时自由的更改；

3、交易所网格手续费损耗偏大，例如网格1-3-5，那么当跌破1买入，突破3卖出，如果刚突破3，又跌破3，此时又会重新买入，而这两个来回的交易完全是无效的，却多了两次手续费，本软件可以让买入间隔和卖出间隔不同，这样可以避免手续费损耗的情况；

4、回测显示收益明显高于同价格区间的80%的交易所策略

