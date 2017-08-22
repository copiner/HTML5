flex基本概念
1.轴
主轴main axis
交叉轴 cross axis
2.容器
父容器 container
justify-content | align-items
子容器 item
flex | align-self

一、容器
父容器: justify-content 属性用于定义如何沿着主轴方向排列子容器。
1.位置排列
justify-content: flex-start | flex-end | center
2.分布排列
justify-content: sapce-between | space-around

父容器： align-items 属性用于定义如何沿着交叉轴方向分配子容器的间距。
1.位置排列
align-items: flex-start | flex-end | center
2.基线排列
align-items: baseline
3.拉伸排列
align-items: stretch
父容器： 轴向
flex-direction: row | row-reverse | column | column-reverse
父容器：排列方式
flex-wrap: nowrap | wrap | wrap-reverse

缩写
flex-flow

二、子容器

伸缩方式:
flex-basic | flex-grow | flex-shrink

交叉轴对齐方式 align-self:
1.位置排列
align-self: flex-start | flex-end | center
2.基线排列
align-self: baseline
3.拉伸排列
align-self: stretch

主轴顺序
order

缩写
flex:
