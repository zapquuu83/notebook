#css引用方式
##第一种引用方式
	行内引入（只能控制当前元素）
	注意:不推荐的写法 因为结构混乱 且不利于重用
###实例
	<div style="width: 500px; height: 500px; background-color:darkorange;">
			我是一个病
		</div>
		<div style="width: 500px; height: 500px; background-color:darkorange;">
			我是另一个病
		</div>
##第二种引用方式
	页内引入（只能针对当前html文件）
	注意:改写法通常不推荐使用 因为只能控制当前页面 不能重用到其他页面上
###实例
	div{
			border-radius:50% ;
		}
##第三种引用方式
	页外引入（可以针对1个或者多个html文件）
	注意:是一个独立的css文件 注意语法的写法 可以有效的重用样式
###实例
	<link rel="stylesheet" type="text/css" href="css/web.css" />