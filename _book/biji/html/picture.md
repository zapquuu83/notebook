# Summary
<!--响应式图片标签
	默认让图片显示的是hd高清图(放在img标签中)，平板则显示md图片，手机等小型设备则显示ld图片
	让浏览器根据屏幕大小，自动选择
	-->
<picture>
	
	<source srcset="img/LD.jpg" media="(max-width:600px)" />
	<source srcset="img/MD.jpg" media="(min-width:601px) and (max-width:999px)" />
	<img src="img/HD.jpg"/>

</picture>

# 解释
HTML <picture> 元素是一个容器，用来为其内部特定的 <img> 元素提供多样的 <source> 元素。浏览器会根据当前页面（即图片所在的盒子的容器）的布局以及当前浏览的设备(比如普通的屏幕和高清屏幕）去从中选择最合适的资源)。