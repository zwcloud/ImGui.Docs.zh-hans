## 体系

四个渲染层级：

从顶向下：

* 1层：__控件__  
* 2层：__渲染树__  
    每个控件对应一个渲染树的子树。树上的每个节点对应一个基础图形。
* 3层：__基础图形（primitive）__  
    最小的抽象渲染单元：线段、矩形、三角形、圆、多边形、折线段、圆弧、二次贝赛尔曲线（bezier-curves）、三次贝塞尔曲线（quadratic-curves）等等。
* 4层：__基本绘制API（接口）__  
    实现：
    1. 以OpenGL为基础、基于路径的渲染API
    2. Cairo
    3. 等等其他图形绘制API
