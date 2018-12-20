# 这是一个用户登录和注册系统
# 该系统目前实现以下功能

1. 后台管理应用
2. 注册功能
3. 登录功能
4. 邮箱验证

# 项目使用方法
## 安装环境
```bash
# 进入到项目环境根目录
cd mysite

# 安装依赖包
pip install -r requirements.txt
```

## 配置项目数据库与邮箱设置
* 进入项目mysite 目录下
* 重命名文件 settings.example.py 为 settings.py
* 修改其中的 数据库项目为你对应的MySQL数据库信息
* 修改其中的 发件邮箱信息为你自己的邮箱信息

## 启动项目
```bash
python manager.py runserver
```


