# Wechat-Hospitable-Shandong-tour-guide
&nbsp;&nbsp;&nbsp;&nbsp;本小程序涉及到的重点为小程序的整体配置方法和页面配置方法。首先将小程序的所有图片放入到images文件夹，其次进行页面配置。在app.json中包含了"pages" "window". "tabBar" 3个关键字。其中pages关键字对应的键值是一个数组，定义了五个页面: index.，taishan，quancheng，sankong和wodejiaxiang；window关键字对应的键值定义了3个属性: navigationBar-BackgroundColor，navigationBarTitleText和navigationBatTextStyle；tabBar关键字对应的键值定义了color，selectedColor选中标签的文本颜色，backgroundColor，list标签列表，其中pagePath表示页面路径，text表示标签文本.，而iconPath表示未选中状态时的标图标路径，selecedcoPah选中时的标签图标路径。然后再各个页面文件夹里的页面json文件里配置标题文字。&nbsp;&nbsp;&nbsp;&nbsp;

&nbsp;&nbsp;&nbsp;&nbsp;在这个小程序的样式设计上，我采用四个盒模型进行布局，以此来使页面布局更合理更美观，管理样式设置更有效快捷，将第一个盒模型用于标题，对标题进行颜色，字体大小等样式进行约束，在用一个盒模型用来约束地点介绍内容，在进行样式设计并且用textstyle类选择器通过text-indent：50px做到首行缩进，text-align：left做到文本左对齐以及line-height：30px设置行间距，然后在第三个盒子里是旅游景点推荐的内容，在textstyle2类选择器进行类似的样式设计。在景点推荐里，我通过导入图片，并进行居中设置。在最后的盒模型里放页面底部介绍语“好客山东欢迎您“以及注释，并用textstyle5，textstyle3和textstyle4类选择器分别进行样式设计。

&nbsp;&nbsp;&nbsp;&nbsp;以上就是本小程序的设计总结。
