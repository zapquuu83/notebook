#关系选择器
        <ul class="nav">
			<li>首页</li>
			<li>产品
				<ul class="subnav">
					<li class="egg">鸡蛋</li>
					<li>鹅蛋</li>
					<li>炸弹</li>
					<li>恐龙蛋</li>
				</ul>
			</li>
			<li>关于我们</li>
		</ul>
##父子关系
###关系选择器中，父子关系
通过指定父元素及具体的子元素，来指定我们的控制目标
注意:更精准的控制，可以小范围控制某一类元素
###代码
	.nav > li{
				font-size:30px ;
				font-weight: bold;
			}
##后代关系
关系选择器中，后代关系(空格)
通过写出父元素及其后代元素，来指定为我们的控制目标
注意:这种会比父子关系，控制的范围要大，因为他是针对所有的后代元素
###代码
    	.nav li{
				text-shadow: 2px 2px 2px gray /*字体阴影*/; 
			}
		.subnav>li{
				font-size: 20px;
				font-weight: normal;
##兄弟关系
 关系选择器-兄弟关系(+)
通过写出参照元素它的相邻元素，来指定为我们的控制目标
注意:控制的是其中一个兄弟元素
###代码
	.subnav>li + li{
					color: blue;
				}
关系选择器中-兄弟关系（~）
通过写出参照元素和它的后续同辈元素，来指定为我们的控制目标
注意:控制的是后续同辈的所有符合条件的兄弟元素
###代码
		.egg~li{
					border:10px solid pink ;
				}
				