# Summary
<h2>视频的使用</h2>
    <!--
        video    视频标签
        autoplay    自动播放
        controls    控制台

        mp4  MPEG-4/H.264 必须注意视频编码为H264，否则浏览器不识别
        flv  原生不支持
        ogg       谷歌或火狐支持
        webm 谷歌和火狐和Edge支持
    -->
<video  controls>
    <source src="/static/media/video.webm"  type="video/webm"/>
    <source src="/static/media/video.mp4"  type="video/mp4"/>
</video>

#定义和用法
controls 属性规定浏览器应该为视频提供播放控件。
如果设置了该属性，则规定不存在作者设置的脚本控件。
浏览器控件应该包括：
•播放
•暂停
•定位
•音量
•全屏切换
•字幕（如果可用）
•音轨（如果可用）