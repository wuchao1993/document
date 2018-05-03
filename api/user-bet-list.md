#API-用户竞猜列表接口

**简要描述：** 

- 用户竞猜列表接口

**请求URL：** 
- 正式接口： `https://hello-coder.com/api/wxapp/User/userBetList`
- 测试地址： `https://hello-coder.com/api/wxapp/User/userBetList` 
  
**请求方式：**
- POST

**参数：** 

 - 接口参数：

|参数名|必选|类型|说明|
|:----    |:---|:----- |----- |

 **返回示例**

```json
{"code":1,"msg":"成功","data":[{"id":9,"bet_id":2,"uid":"2","user_bet":1,"is_winning":1,"result":1,"time":1524553808,"periods":"20180424"}]}
```

 **返回参数说明** 

|参数名|类型|说明|
|:-----  |:-----|----- |
| id | int | 用户竞猜id |
| bet_id | int | 盘口id |
| user_bet | int | 用户竞猜赛果 |
| is_winning | int | 是否猜中，1猜中 |
| result | string | 是否结束有赛果 |
| periods | string | 期数 |
**错误代码**

| 错误码 | 描述 |
|:-----  |:-----|
|  | |

 **备注** 

- 更多返回错误代码请看首页的错误代码描述