#API-获取btc实时行情接口

**简要描述：** 

- 获取btc实时行情接口

**请求URL：** 
- 正式接口： `https://hello-coder.com/api/wxapp/Coins/getBtcInfo`
- 测试地址： `https://hello-coder.com/api/wxapp/Coins/getBtcInfo` 
  
**请求方式：**
- POST

**参数：** 

 - 接口参数：

|参数名|必选|类型|说明|
|:----    |:---|:----- |----- |


 **返回示例**

```json
{"code":1,"msg":"获取成功","data":"9410.00"}
```

 **返回参数说明** 

|参数名|类型|说明|
|:-----  |:-----|----- |
| data | float | btc实时价格（usd）  |


**错误代码**

| 错误码 | 描述 |
|:-----  |:-----|
|  | |

 **备注** 

- 更多返回错误代码请看首页的错误代码描述