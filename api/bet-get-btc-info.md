#API-获取竞猜信息接口

**简要描述：** 

- 获取竞猜信息接口

**请求URL：** 
- 正式接口： `https://hello-coder.com/api/wxapp/Bet/getBtcInfo`
- 测试地址： `https://hello-coder.com/api/wxapp/Bet/getBtcInfo` 
  
**请求方式：**
- POST

**参数：** 

 - 接口参数：

|参数名|必选|类型|说明|
|:----    |:---|:----- |----- |


 **返回示例**

```json
{"code":1,
"msg":"获取成功",
"data":{"id":2,"coins_name":"btc","coins_img_url":"http:\/\/btc.com","periods":"20180424","rise_total":102,"fell_total":101,"yesterday_last_price":"56000.000","status":1,"fell_percent":"49.75","rise_percent":"50.25"}
}
```

 **返回参数说明** 

|参数名|类型|说明|
|:-----  |:-----|----- |
| id | int | id  |
| coins_name | string | 币名  |
| coins_img_url | string | 币图片地址  |
| periods | string | 竞猜期数  |
| rise_total | int | 看涨人数  |
| fell_total | int | 看跌人数  |
| yesterday_last_price | string | 昨日btc价格  |
| status | int | 状态  |
| fell_percent | int | 看跌百分比  |
| rise_percent | int | 看涨百分比  |


**错误代码**

| 错误码 | 描述 |
|:-----  |:-----|
|  | |

 **备注** 

- 更多返回错误代码请看首页的错误代码描述