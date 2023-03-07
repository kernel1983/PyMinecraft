# Minecraft

这是用Python和Pyglet写的简单的Minecraft游戏，
从<https://github.com/fogleman/Minecraft>fork过来的，
一共只有几百行代码，麻雀虽小，五脏俱全，觉得挺有意思的，
于是把源码读了一遍，并做了详细的注释。
通过这个例子学习Pyglet和Python游戏编程还是不错的，推荐。

以下是游戏视频：

http://www.youtube.com/watch?v=kC3lwK631X8

## Update

Python 3.8+ 支持

## How to Run

    pip install pyglet==1.5.27
    git clone https://github.com/Hawstein/PyMinecraft.git
    cd PyMinecraft
    python main.py
	
## How to Play

### 移动

- W: 向前移动
- S: 向后移动
- A: 向左移动
- D: 向右移动
- Mouse: 改变视角
- Space: 跳
- Tab: 切換飞行模式(飞行模式是可以直接在垂直方向上运动的)

### 建造

- 选择要建造的方块类型
    - 1: 砖块
    - 2: 草地
    - 3: 沙块
- 单击鼠标左键：移除方块
- 单击鼠标右键：添加方块

### 退出

- ESC: 释放鼠标，关闭窗口
