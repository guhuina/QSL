# QSL

QSL (Qunar SASS Library)，参考了compass，bourbon及sassCore等众多优秀sass库，归纳总结而成。

#如何使用
	
* git clone git@github.com:guhuina/QSL.git
* 将lib放在项目样式文件夹中
* 安需加载相应的模块

```
//重置样式模块
@import "lib/reset.scss";
//css3样式模块
@import "lib/css3.scss";
//兼容ie等浏览器的属性
@import "lib/ie.scss";
//媒体查询模块
@import "lib/media.scss";
//工具模块
@import "lib/util.scss";

```