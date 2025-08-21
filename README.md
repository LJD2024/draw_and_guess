# 你画我猜游戏

这是一个基于Web的你画我猜游戏，支持多人在线实时绘画和猜测。

## 功能特点
- 实时绘画功能（使用HTML5 Canvas）
- 多人在线游戏房间
- 实时聊天功能
- 计时器和分数系统
- 词语随机选择

## 技术栈
- 后端：Python + Flask
- 前端：HTML5, CSS3, JavaScript
- 实时通信：Socket.IO

## 项目结构
```
draw_and_guess/
├── app.py              # 主应用入口
├── requirements.txt    # 依赖包列表
├── static/
│   ├── css/
│   │   └── style.css   # 样式文件
│   ├── js/
│   │   ├── app.js      # 前端逻辑
│   │   └── drawing.js  # 绘图功能
│   └── img/
│       └── icons/      # 图标资源
└── templates/
    ├── index.html      # 主页面
    └── game.html       # 游戏页面
```

## 安装和运行
1. 安装依赖：
   ```
   pip install -r requirements.txt
   ```
2. 运行应用：
   ```
   python app.py
   ```
3. 在浏览器中访问：http://localhost:5000