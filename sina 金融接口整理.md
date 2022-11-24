
这个是在csdn 📱的 ，测试了几个；好用的！ 

# 2022新浪商品期货 api

## 新浪期货数据各品种代码（商品连续）如下

```sku
RB0 螺纹钢
AG0 白银
AU0 黄金
CU0 沪铜
AL0 沪铝
ZN0 沪锌
PB0 沪铅
RU0 橡胶
FU0 燃油
WR0 线材
A0 大豆
M0 豆粕
Y0 豆油
J0 焦炭
C0 玉米
L0 乙烯
P0 棕油
V0 PVC
RS0 菜籽
RM0 菜粕
FG0 玻璃
CF0 棉花
WS0 强麦
ER0 籼稻
ME0 甲醇
RO0 菜油
TA0 甲酸
```

```url
商品期货  废弃，数据只有7月份的；日线还是可以用的
http://stock2.finance.sina.com.cn/futures/api/json.php/IndexService.getInnerFuturesMiniKLineXm?symbol=CODE
例子：
http://stock2.finance.sina.com.cn/futures/api/json.php/IndexService.getInnerFuturesMiniKLine5m?symbol=M0
5分钟http://stock2.finance.sina.com.cn/futures/api/json.php/IndexService.getInnerFuturesMiniKLine5m?symbol=M0
15分钟
http://stock2.finance.sina.com.cn/futures/api/json.php/IndexService.getInnerFuturesMiniKLine15m?symbol=M0
30分钟
http://stock2.finance.sina.com.cn/futures/api/json.php/IndexService.getInnerFuturesMiniKLine30m?symbol=M0
60分钟
http://stock2.finance.sina.com.cn/futures/api/json.php/IndexService.getInnerFuturesMiniKLine60m?symbol=M0
日K线
http://stock2.finance.sina.com.cn/futures/api/json.php/IndexService.getInnerFuturesDailyKLine?symbol=M0
http://stock2.finance.sina.com.cn/futures/api/json.php/IndexService.getInnerFuturesDailyKLine?symbol=M1401

股指期货
5分钟
http://stock2.finance.sina.com.cn/futures/api/json.php/CffexFuturesService.getCffexFuturesMiniKLine5m?symbol=IF1306

15
http://stock2.finance.sina.com.cn/futures/api/json.php/CffexFuturesService.getCffexFuturesMiniKLine15m?symbol=IF1306
30分钟
http://stock2.finance.sina.com.cn/futures/api/json.php/CffexFuturesService.getCffexFuturesMiniKLine30m?symbol=IF1306
60分钟
http://stock2.finance.sina.com.cn/futures/api/json.php/CffexFuturesService.getCffexFuturesMiniKLine60m?symbol=IF1306
日线
http://stock2.finance.sina.com.cn/futures/api/json.php/CffexFuturesService.getCffexFuturesDailyKLine?symbol=IF1306
```




## 新浪股票接口：
```api
最近二十天左右的每5分钟数据 
http://money.finance.sina.com.cn/quotes_service/api/json_v2.php/CN_MarketData.getKLineData?symbol=sz000001&scale=5&ma=5&datalen=1023 
（参数：股票编号、分钟间隔（5、15、30、60）、均值（5、10、15、20、25）、查询个数点（最大值242））

新浪关键词查询股票接口 
http://suggest3.sinajs.cn/suggest/type=&key=000627&name=suggestdata_1429775785401

查询股票最新行情 
http://hq.sinajs.cn/list=sh601003,sh601001

```

