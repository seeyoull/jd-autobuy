# JD_AutoBuy

## chang log
+ 2017-03-30 实现二维码扫码登陆
+ 2017-06-27 [Golang版JD_AutoBuy](https://github.com/Adyzng/go-jd)



## 运行环境
Python 2.7


## 第三方库
- [Requests][1]: 简单好用，功能强大的Http请求库
- [beautifulsoup4][2]: HTML文档格式化及便签选择器



## 环境配置
``` Python
pip install requests
pip install beautifulsoup4
```

## 使用帮助
``` cmd
> python scraper-jd.py -h
usage: scraper-jd.py [-h] [-u USERNAME] [-p PASSWORD] [-g GOOD] [-c COUNT]
                     [-w WAIT] [-f] [-s]

Simulate to login Jing Dong, and buy sepecified good

optional arguments:
  -h, --help            show this help message and exit
  -u USERNAME, --username USERNAME
                        Jing Dong login user name
  -p PASSWORD, --password PASSWORD
                        Jing Dong login user password
  -g GOOD, --good GOOD  Jing Dong good ID
  -c COUNT, --count COUNT
                        The count to buy
  -w WAIT, --wait WAIT  Flush time interval, unit MS
  -f, --flush           Continue flash if good out of stock
  -s, --submit          Submit the order to Jing Dong
```
