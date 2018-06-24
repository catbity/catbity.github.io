动态可交互背景（js引入）

1. 打开博客根目录/themes/next/layout/_layout.swig文件，在之前添加代码如下：
{% if theme.canvas_nest %}
<script type="text/javascript"
color="0,0,255" opacity='0.7' zIndex="-2" count="99" src="//cdn.bootcss.com/canvas-nest.js/1.0.0/canvas-nest.min.js"></script>
{% endif %}


属性说明： 
- color ：线条颜色, 默认: ‘0,0,0’；三个数字分别为(R,G,B) 
- opacity: 线条透明度（0~1）, 默认: 0.5 
- count: 线条的总数量, 默认: 150 
- zIndex: 背景的z-index属性，css属性用于控制所在层的位置, 默认: -1
2. 打开博客根目录/themes/next/_config.yml，找到字段canvas_nest，将其置为true【如果没有找到该字段，请自行添加】 
3. hexo clean , hexo d -g可以看到效果~


原网页：https://blog.csdn.net/lemonxq/article/details/78578650