#API-获取排行榜接口

**简要描述：** 

- 获取排行榜接口

**请求URL：** 
- 正式接口： `https://hello-coder.com/api/wxapp/Bet/getLeaderboard`
- 测试地址： `https://hello-coder.com/api/wxapp/Bet/getLeaderboard` 
  
**请求方式：**
- POST

**参数：** 

 - 接口参数：

|参数名|必选|类型|说明|
|:----    |:---|:----- |----- |
| type | N | string | month,year默认不填显示周排行榜 |

 **返回示例**

```json
{"code":1,"msg":"获取成功","data":[{"uid":"1","total":2,"win_total":2},{"uid":"2","total":2,"win_total":1,"nick_name":"NG CHIU","avatarUrl":"https:\/\/wx.qlogo.cn\/mmopen\/vi_32\/Q0j4TwGTfTLDVQKU5g7ic2e0AqiaYtU5vR0RX7IiciaeHEfMrhib4fXia91w3DGOGn679LeawRqgBd4EI98RGtZpkcCg\/0"}]}
```

 **返回参数说明** 

|参数名|类型|说明|
|:-----  |:-----|----- |
| uid | int | id  |
| total | string | 竞猜次数  |
| win_total | string | 猜中次数  |
| nick_name | string | 用户昵称  |
| avatarUrl | string | 用户头像  |

**错误代码**

| 错误码 | 描述 |
|:-----  |:-----|
|  | |

 **备注** 

- 更多返回错误代码请看首页的错误代码描述