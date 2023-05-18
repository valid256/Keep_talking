
# Keep Talking and Nobody Explode
# 线路模块和复杂线路的判断程序 



## 项目背景

因为偶然间和朋友玩Keep Talking and Nobody Explode 这个游戏，玩到后面有些卡关，就用Poe用Python写了判断的剪线的代码，真是科技改变生产力。

## 功能特性


- 关于线路模块：根据线路数量、颜色、顺序、末位序号的条件，判断剪断哪条线路。
- 复杂线路模块：根据线路有无红色、蓝色、星号、LED灯等条件，判断是否需要剪断线路。

## 环境依赖

- 操作系统：Windows 10
- 编程语言：Python 3.9

## 安装和使用
# 运行结果如下
![image](https://github.com/valid256/Keep_talking/assets/132802690/4a809da1-882a-4666-8495-ae79160c842e)

![image](https://github.com/valid256/Keep_talking/assets/132802690/60bc4762-778b-4dc9-806d-0d1d3a73e6cc)


```bash
# 克隆项目到本地
git clone https://github.com/yourname/yourproject.git
# 进入项目目录
cd yourproject
# 安装依赖库
pip install -r requirements.txt
# 运行主程序
python main.py
```

## 目录结构描述


```
yourproject
├── README.md # 说明文档
├── main.py # 主程序入口
├── wire.py # 剪线模块代码
├── complex_wire.py # 复杂线路模块代码
├── images # 图片资源文件夹
│   ├── wire.png # 线路图片
│   ├── complex_wire.png # 复杂线路图片
│   └── ...
└── sounds # 音效资源文件夹
    ├── beep.wav # 蜂鸣声音效
    ├── boom.wav # 爆炸声音效
    └── ...
```
（假的根本没有hhh）

## 版本内容更新

- v1.0.0 (2023-5-1)：完成了基本功能，实现了剪线模块和复杂线路模块。
- v1.0.1 (2023-4-29)：修复了剪线模块中颜色判断错误的bug。
- v1.1.0 (2023-4-28)：增加了声音和图形界面，提升了用户体验。
（其实只写了一版）
## 声明

本项目仅供学习交流使用，不涉及任何商业目的。本项目参考了《Keep Talking and Nobody Explodes》游戏中的关于线路模块和复杂线路模块的规则，版权归Poe所有。
## 鸣谢

感谢Prophet_LZ陪我度过快乐的游戏时光。

## 协议



[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
