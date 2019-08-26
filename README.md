# demo

这是一个动态获取浏览器窗口相对于屏幕的坐标 demo。
用于解决嵌入最新 chrome 浏览器点击，某一个位置移动整个窗口问题。

### 原理公式：△p = p2 - p1

△p 窗口的位置坐标
p1 是鼠标到客户端的左边的距离 固定，鼠标按下时的 clientX
p2 是鼠标移动之后的位置 screenX

### screenX、screenY、clientX、clientY 之间的关系

![img text](./20150502094344891.jpeg)
