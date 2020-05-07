# 智慧树问答复读机

使用 ```Selenium``` 自动复读他人的回答

## 已实现的功能
- 自动登录及复读他人回答
- 控制复读的 题目个数

## 待实现功能
- 为自己点赞
- 自由选择复读的 课程

## 使用教程
- 应安装了 ```python 3.6``` 或更高版本

- 应安装了 包管理器 ```pip```

- 目前仅支持 ```Chrome``` 浏览器（以及基于 ```Chrome```内核的浏览器） 或 ```Firefox```浏览器

1. 配置浏览器驱动   
   若使用 ```Google Chrome```或基于 ```chrome``` 内核的其他浏览器(如 360 等), 请自行百度, 安装**合适版本**的 ```chromedriver```  
   
2. 安装 ```Python``` 依赖库
  ```pip install selenium -i https://pypi.tuna.tsinghua.edu.cn/simple```
  
3. 填写目录下的 ```info.json```
    ```
    {
        "name": "刘陆",     // 姓名
        "username" : "2017061910",        // 学号
        "password": "",       // 密码
        "course": "",      // 完整课程名 (暂不支持选课, 默认应该是毛概)
        "count": 3        // 复读的题目数
    }
    ```

4. 运行脚本  
  ```python main.py```, 将自动打开一个浏览器窗口, 而后自动操作
 