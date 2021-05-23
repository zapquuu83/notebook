#class和id选择器
##id 选择器
	 以id的名字作为目标名，记得前面要加一个#符号
	 注意 一个页面只能存在一个唯一的ID，并不推荐使用，因为后期JS要常用到id这个属性，可能会有冲突
*#p1{
		color: skyblue;
	}
	#p2{
		color: pink;
	}
###
	<p id="p1" class="bg_black">
			急急急
			</p>


	<p id="p2">
		ji
	</p>
##class选择器
	以class属性所对应的名字作为目标的名字，记得前面加个"."符号
	注意 可以用class来代替id选择器 并且class选择器还可以多次重用，可以更好的控制一个或多个标签
.bg_black{
			background: black;
	}
###
	<p class="bg_black">
	34
	</p>
