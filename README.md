Demo
====

Demo

V1.0

> 获取用户应用

### 多行文本框    
    这是一个有多行的文本框  
    a
    
###请求
    {
        "ctx": {
            "uid": "5000797",
            "pwd": "123123"
        },
        "req": {
            "t": "getAppList"
        }
    }

***

###响应

    {
    "ctx": {
        "t": "getAppList",
        "err": 0,
        "reason": ""
    },
    "resp": {
        "total": 50,
        "size":20,
        "data":[
            {
                "title": "QQ浏览器",
                "url": "http://zxly.file.18.net/1"
            },
            {
                "title": "QQ手机助手",
                "url": "http://zxly.file.18.net/2"
            }
        ]
    }
    }


  
