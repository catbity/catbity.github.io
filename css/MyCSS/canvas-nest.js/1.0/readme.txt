��̬�ɽ���������js���룩

1. �򿪲��͸�Ŀ¼/themes/next/layout/_layout.swig�ļ�����֮ǰ��Ӵ������£�
{% if theme.canvas_nest %}
<script type="text/javascript"
color="0,0,255" opacity='0.7' zIndex="-2" count="99" src="//cdn.bootcss.com/canvas-nest.js/1.0.0/canvas-nest.min.js"></script>
{% endif %}


����˵���� 
- color ��������ɫ, Ĭ��: ��0,0,0�����������ֱַ�Ϊ(R,G,B) 
- opacity: ����͸���ȣ�0~1��, Ĭ��: 0.5 
- count: ������������, Ĭ��: 150 
- zIndex: ������z-index���ԣ�css�������ڿ������ڲ��λ��, Ĭ��: -1
2. �򿪲��͸�Ŀ¼/themes/next/_config.yml���ҵ��ֶ�canvas_nest��������Ϊtrue�����û���ҵ����ֶΣ���������ӡ� 
3. hexo clean , hexo d -g���Կ���Ч��~


ԭ��ҳ��https://blog.csdn.net/lemonxq/article/details/78578650