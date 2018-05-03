#API-用户登录

**简要描述：** 

- 用户登录

**请求URL：** 
- 正式接口： `https://hello-coder.com/api/wxapp/Public/login`
- 测试地址： `https://hello-coder.com/api/wxapp/Public/login` 
  
**请求方式：**
- POST

**参数：** 

 - 接口参数：

|参数名|必选|类型|说明|
|:----    |:---|:----- |----- |
| code | Y | string | code |
| encrypted_data | Y | string | encrypted_data |
| iv | Y | string | iv |
| raw_data | Y | string | raw_data |
| signature | Y | string | signature |


 **返回示例**

```json
[
]
```

 **返回参数说明** 

|参数名|类型|说明|
|:-----  |:-----|----- |
| uid |int | 用户id  |


**错误代码**

| 错误码 | 描述 |
|:-----  |:-----|
|  | |

 **备注** 

- 更多返回错误代码请看首页的错误代码描述