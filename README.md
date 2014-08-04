Demo
====

Demo

V1.0

> 获取用户应用

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

### 多行文本框    
    这是一个有多行的文本框  
    你可以写入代码等,每行文字只要输入两个Tab再输入文字即可  
    这里你可以输入一段代码  
  
### 比如我们可以在多行文本框里输入一段代码,来一个Java版本的HelloWorld吧  
    public class HelloWorld {  
  
      /**  
      * @param args  
   */  
   public static void main(String[] args) {  
   System.out.println("HelloWorld!");  
  
   }  
  
    }  
