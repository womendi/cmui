# cmui
cmui超萌框架,快捷布局
<br />
<b>自己写的布局框架，自适应跨平台设备</b>
<br /><br />
<br />实例网站1 http://www.aiplat.com
<br />实例网站2 http://m.aiplat.com/metro
<br />cmui包含cmreset.css和cmstyle.css、aiplat.css三个css文件，同时生成可用于微信小程序开发的wxss文件
<br /><br />
<b>cmreset.css说明</b>
<br /><br />1,盒模型采用IE盒子，即css3中的box-sizing值为border-box
<br /><br />
<b>cmstyle.css说明</b>
<br /><br />1,栅格系统
<br />请在此文件搜索 ‘栅格系统’
<br />兼容pc与mobile写法:(pc端以1200px居中，mobile以100%适配)
<br />\<div class="cm_main2"\>
          \<div class="cm_main"\>显示主体div\<\/div\>
     \<\/div\>

<br /><br />2,使用em相对单位,cmreset.css中同为em
<br />宽高或长度厚度较小时部分单位使用px,如.cm_bb1e{border-bottom:1px solid #eee}
<br />3,\<span class="cm_fs05"\>cmui\<\/span\>
<br />意思cmui字体大小对应.cm_fs05{font-size:0.5em}
<br />.cm_fs05中cm为cmui的前缀cm,
<br />.cm_fs05中fs为font-size两个单词各自的首字母集合,所有类命名均类似
<br />.cm_fs05中05为0.5em大小,em为如上1说明
<br />.cm_fs06.....cm_fs3--06、07、08、09、1、11、12、13、15，2，3雷同 .cm_fs3{font-size:3em}
<br /><br />3,以上三个css文件的说明文档还有很多未写,后续完善,多谢支持与赞.
<br /><br />
<b>兼容性</b>
<br /><br />1,实测兼容ie8
<br />2,兼容手机、电脑、平板等等一切联网设备