# csdn
csdn刷阅读数
使用方法：
将
self.data = {
            "page": "1",  第几页
            "size": "20", 每页多少条数据
            "businessType": "blog", 获取的版块
            "noMore": "false",  
            "username": "xxx"  哪个用户
        }
        
        根据自己需要爬取的内容选择版块，现在默认是blog就是发布的文章，发布的文件暂时无法刷。
        使用者只需要将username修改为自己的账号用户名即可。记住是账号用户名
 相关的需要的模块如下
requests (2.22.0)
selenium (3.141.0)
jsonpath (0.82)

启动命令
python  Csdn_click.py
Python2  python3均可
