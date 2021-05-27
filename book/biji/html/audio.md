# Summary
<h2>音频的基本使用</h2>
    <!--
        src 资源source
        autoplay    加载完成后自动播放
        controls    音频控制台


        注意点    在苹果系列的浏览器和安卓移动端的浏览器会禁止自动播放，需要用户点击操作才能播放
    -->
    <audio src="/static/media/music.mp3" autoplay></audio>
    <!--
        .wav
        .ogg
        .mp3    主流平台都是支持的

        注意: 所以，尽可能使用AE、格式工厂等软件进行格式转换

#代码
<h2>音频的基本使用</h2>
		<!--audio 音频标签
			src 资源source
			autoplay 加载完后自动播放
			controls 音频控制台
			
			注意点 在苹果系列的浏览器和安卓移动端全部会禁止自动播放 需要用户自己点击播放
		-->
		<audio src="music/music.mp3" autoplay="autoplay"></audio>
		<!--.mp3 主流
			.ogg 只有谷歌和火狐支持
			.wav 除了ie11以下不支持 其余都支持
			注意 所以尽可能使用ae和格式工厂等软件进行格式转换
		-->
		<h2>视频的应用</h2>
		<!--mp4 MPEG-4/H.264 注意视频编码为H264，否则浏览器会不识别
			flv 不支持
			webm谷歌和火狐支持
			ogg 谷歌和火狐
		-->
		<video controls="">
			<source src="music/vidio.webm" type="video/webm"></source>
			<source src="music/vidio.mp4" type="video/mp4"></source>
		</video>