Shen Long Protocol V1.0
====


###一, 获取用户应用

####请求

    {
        "ctx": {
            "uid": "5000797",
            "pwd": "123123"
        },
        "req": {
            "t": "getAppList",
            "pagesize":20,
            "pageindex":1
        }
    }

####响应

    {
        "ctx": {
            "t": "getAppList",
            "err": 0,
            "reason": ""
        },
        "resp": {
            "total": 50,
            "pagesize":20,
            "pageindex":1,
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
    

###二, 用户同步

####请求

    {
        "ctx": {
            "uid": "5000797",
            "pwd": "123123"
        },
        "req": {
            "t": "usersync"
        }
    }

####响应

    {
        "ctx": {
            "t": "usersync",
            "err": 0,
            "reason": ""
        },
        "resp": {
            
        }
    }
    

###三, 用户收益

####请求

    {
        "ctx": {
            "uid": "5000797",
            "pwd": "123123"
        },
        "req": {
            "t": "income",
            "time":"2014/01"
        }
    }

####响应

    {
        "ctx": {
            "t": "income",
            "err": 0,
            "reason": ""
        },
        "resp": {
            
        }
    }
    
###四,用户结算

####请求

    {
        "ctx": {
            "uid": "5000797",
            "pwd": "123123"
        },
        "req": {
            "t": "settle",
            "time":"2014/01"
        }
    }

####响应

    {
        "ctx": {
            "t": "settle",
            "err": 0,
            "reason": ""
        },
        "resp": {
            
        }
    }
