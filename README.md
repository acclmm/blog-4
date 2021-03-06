# 浏览器渲染原理
1. 根据HTML构建HTML树。
2. 根据CSS构建CSS树。
3. 把两棵树合成一颗渲染树。
4. layout。
5. paint绘制。
6. composite合成。

# CSS动画的两种做法
## transition：
有四个功能：位移translate 缩放scale 旋转rotate 倾斜skew
*注：1. 一般配合transition使过度，inline元素不支持transform，需要先变成block。
     2. 从看见到看不见用visibility：visible》hidden或者透明的opacity：1》0（但是还是占着位置）

## animation: 
和transition不同的地方是有它加上了关键帧，有特定的语法。

### 个人见解：
css真的很需要动手，不然我很难理解他的用法，当然背单词意思也是哈哈。
