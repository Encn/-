“100” 返回成功；其他均有误，提示返回信息。



### 用户登录：

- <http://localhost:8080/login/auth>
- 请求：

```
{"username":"test","password":"43423432"}
```

- 返回：

```
{
    "returnCode": "100",
    "returnMsg": "请求成功",
    "returnData": {
        "result": "用户名或密码错误"
    }
}
```

- 注意： cookies 中 JSESSIONID

------

### 查询用户信息

- <http://localhost:8080//login/info>
- 请求

```
{}
```

- 返回

```
{
    "returnCode": "100",
    "returnMsg": "请求成功",
    "returnData": {
        "cardType": "1",
        "telephone": "1301234512345",
        "id": 1,
        "cardNumber": "22222222222222",
        "username": "tank"
    }
}
```

------

### 添加用户

- <http://localhost:8080/user/add>
- 请求

```
{"username":"test","password":"43423432","real_name":"张三","telephone":"13012341234","cardtype":"1","cardnumber":"22022019901010123X"}
```

- 返回

```
{
    "returnCode": "100",
    "returnMsg": "请求成功",
    "returnData": {}
}
```

### 添加投诉建议

- <http://localhost:8080/suggest/add>
- 请求

```
{"type":"1", "title":"ttttt", "content":"ccccccc", "depart":"dddddd", "region":"1,2,3"}
```

type : 1/2 投诉/建议

- 返回

```
{
    "returnCode": "100",
    "returnMsg": "请求成功",
    "returnData": {}
}
```