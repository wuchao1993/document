#API-用户竞猜列表接口

**简要描述：** 

- 用户竞猜列表接口

**请求URL：** 
- 正式接口： `https://hello-coder.com/api/wxapp/User/getUserRanking`
- 测试地址： `https://hello-coder.com/api/wxapp/User/getUserRanking` 
  
**请求方式：**
- POST

**参数：** 

 - 接口参数：

|参数名|必选|类型|说明|
|:----    |:---|:----- |----- |

 **返回示例**

```json
{"code":1,"msg":"成功","data":{"yesterdayRank":0,"weekRank":0,"yearRank":2,"totalBet":2,"winProbability":"50.00"}}
```

 **返回参数说明** 

|参数名|类型|说明|
|:-----  |:-----|----- |
| yesterdayRank | string | 昨日排名 |
| weekRank | string | 周排名 |
| yearRank | string | 年度排名 |
| totalBet | string | 竞猜次数 |
| winProbability | string | 胜率 |
**错误代码**

| 错误码 | 描述 |
|:-----  |:-----|
|  | |

 **备注** 

- 更多返回错误代码请看首页的错误代码描述