# 🐍Showdoc2SwiftModel
### 高效搬砖，拒绝复制粘贴！
自动获取showdoc返回的数据，并将生成Swift model以供使用。   
Auto generate swift model code from showdoc!

## 环境 - Environment
Python 2.7

## 依赖 - Depend
requests  
markdown2  
matplotlib   
BeautifulSoup

## 如何使用 - How to use
1. 控制台中输入`python showdoc2swiftmodel.py`方可运行   
2. 输入参数   
从showdoc的URL中获取几个参数，以下面的url为例子：
```
http://doc.example.com/web/#/1?page_id=666
```
ShowDoc Path URL : `http://doc.example.com/server`   
Page id : `666`   

然后输入要生成的类名前部分：   
model class prefix: `ZMExample`     
   
然后输入要生成类目的后部分：   
model class shufix: `Model`

这样生成的类名将会是 `ZMExampleModel` , 文件名为 `ZMExampleModel.swift`

3. 接下来需要确认信息是否正确，如果正确请输入Y并按下Enter键。
4. 输入登陆用户名和密码，有时可能还会要求输入验证码，如果弹出了验证码图片，请记住验证码后关闭验证码窗口才可以输入验证码。

🍺 1-2-3-4 Done.

## License
### MIT License

Copyright (c) 2019 Zmsky 

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
