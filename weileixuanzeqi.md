#伪类选择器
		ul li:first-of-type{ /*ul下面的第一个li类型的子元素*/
			background: purple
		}
		ul :first-child{/*ul下面的第一个子元素*/
			background: skyblue
		}
		ul li:first-child{/*ul下面的第一个子元素，并且是li类型，所以这里是不符合现有条件，是不会生效的
		background: skyblue
		}
		
		伪类css
		指明父元素，则表示全页面搜索符合的子元素
		尽量不要这样子写，因为效率低，所以应该尽可能加上一个父元素，缩小搜索的范围
###nth-child nth-of-type    区别
nth-child可以选择父元素下的字元素，nth-of-type也可以。但是它们到底有什么区别呢？ 
1.如果子元素的类型不定，但位置相对固定，应该选择nth-child系列，直接粗暴直接，根据位置决定
			 2.如果子元素相对固定且统一，应该选择nth-of-type系列，效率更高
			 3.nth-child系列，首要条件是符合位置，然后才考虑指定的元素类型
			 4.nth-of-type系列，首要条件必须是指定的元素类型，然后才考虑位置
###例如
	<li>one</li>
	<li>two</li>
	nth-child(2)选择的是<li>one</li>
	nth-of-type(2)选择的是<li>two</li>
###伪类选择器(:)
	在指定范围内的元素，精细控制其中某一个元素
	注意:对现有的目标元素，进行更加详细的状态控制
	.nav li:first-child{
				color: skyblue;
			}
			.nav li:last-child{
				color: darkblue;
			}
			.nav li:nth-child(2){
				color: yellow;
			}
	根据指定元素的类型，来做精准控制
	.nav li:last-of-type{
				color: pink;
			}
			.nav li:first-of-type{
				color: purple;
			}
			.nav li:nth-of-type{
				color: yellow;
			}
###缓动动画
	.nav>li{
				color: black;
				transition: all 300ms linear;     
			}
####link 选择器对指向未被访问页面的链接设置样式
	a:link{color:blue;}
####visited 用于设置指向已访问页面的链接的样式
	a:visited {color:blue;}
####hover 选择器用于设置鼠标指针浮动到链接上时的样式
	a:hover{color:red;}
####active 选择器用于选择活动链接
	a:active{color:yellow;}
####ul要加class
	<ul class="nav">
			<li><a href="http://bulejj.com">新闻1</a></li>
			<li><a href="http://bulejj.com">新闻2</a></li>
			<li><a href="http://bulejj.com">新闻3</a></li>
			<li><a href="http://bulejj.com">新闻4</a></li>
			<div>12</div>
		</ul>
		
			
		