# fullScreen


fullScreen教程 
一引入文件

        <link rel="stylesheet" href="css/jquery.fullPage.css">
        <script src="js/jquery.min.js"></script>

        <!-- jquery.easings.min.js 用于 easing 参数，也可以使用完整的 jQuery UI 代替，如果不需要设置 easing 参数，可去掉改文件 -->
        <script src="js/jquery.easings.min.js"></script>

        <!-- 如果 scrollOverflow 设置为 true，则需要引入 jquery.slimscroll.min.js，一般情况下不需要 -->
        <script src="js/jquery.slimscroll.min.js"></script>

        <script src="js/jquery.fullPage.js"></script>
 
二 重要配置

 1选项
 slidesColor     函数  无   设置背景颜色
 
anchors     数组  无   定义锚链接

menu    布尔值     false   绑定菜单，设定的相关属性与 anchors 的值对应后，菜单可以控制滚动

navigation  布尔值     false   是否显示项目导航

navigationPosition  字符串     right   项目导航的位置，可选 left 或 right

2回调函数

名称  说明

afterLoad   滚动到某一屏后的回调函数，接收 anchorLink 和 index 两个参数，anchorLink 是锚链接的名称，index 是序号，从1开始计算

onLeave     滚动前的回调函数，接收 index、nextIndex 和 direction 3个参数：index 是离开的“页面”的序号，从1开始计算；


 
