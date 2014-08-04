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
            "t": "userincome",
            "time":"2014/01"
        }
    }

####响应

    {
        "ctx": {
            "t": "userincome",
            "err": 0,
            "reason": ""
        },
        "resp": {
            
        }
    }
    
###四,用户结算历史

####请求

    {
        "ctx": {
            "uid": "5000797",
            "pwd": "123123"
        },
        "req": {
            "t": "usersettle",
            "time":"2014/01",
            "pagesize":20,
            "pageindex":1
        }
    }

####响应

    {
        "ctx": {
            "t": "usersettle",
            "err": 0,
            "reason": ""
        },
        "resp": {
            "total":50,
            "pagesize":20,
            "pageindex":1,
            "data":[
                {
                    "time":"2014-04-01",
                    "money":100
                },
                {
                    "time":"2014-04-02",
                    "money":200
                }
            ]
        }
    }
