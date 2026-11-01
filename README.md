# to hyy 🎄

一棵用 Python + Pygame 画的 3D 粒子圣诞树。

## 网页版（发给朋友玩的就是这个）

**https://carol3321.github.io/to-hyy/**

打开就能看，手机上也可以，手指/鼠标拖动可以旋转。

- `index.html` — 网页版。纯 canvas，无依赖、无构建，GitHub Pages 直接托管
- `tree.py` — 原版桌面程序

## 桌面版运行

```bash
pip install pygame-ce
python tree.py
```

关掉窗口即可退出。

## 出处

代码来自 [ZekangLi-Zico/Christmas-Tree](https://github.com/ZekangLi-Zico/Christmas-Tree)，网页版是把同一套粒子生成与投影算法原样移植到 canvas。
