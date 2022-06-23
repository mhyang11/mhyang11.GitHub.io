layout: post
title: Canvas
subtitle: canvas的学习心得。
categories: HTML5

HTML5 <canvas>元素用于图形的绘制，通过脚本（如JavaScript）来完成。<canvas> 标签只是图形容器，必须使用JavaScript 脚本来绘制图形。

 HTML canvas fillRect(x,y,width,height) 方法  x是矩形左上角的x坐标，y是左上角的y坐标,width矩形的宽度，height矩形的高度，像素为单位

 HTML canvas getContext(“2d”) 指定在画布上绘制的类型，2d是二维图形的意思。

Canvas 是逐像素进行渲染的。在 canvas 中，一旦图形被绘制完成，它就不会继续得到浏览器的关注。如果其位置发生变化，那么整个场景也需要重新绘制，包括任何或许已被图形覆盖的对象。