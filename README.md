 
 
省市区三级联动的选择控件, 整体效果如下：

![mahua](http://img.blog.csdn.net/20141127182555625?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvd3VsaWFuZ2h1YW4=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/Center)

##基本结构

UI：自定义控件WheelView

数据：基于XML的数据解析

适配器：建立通用的Adapter，供给自定义的控件使用



##实现思路

本Demo提供了一份较为完整的，国内所有省市区的三级数据。

具体见project的代码，Assets目录下的province_data.xml文件。 

您也可以自己定制数据格式，配置xml和对应的解析代码。

常见的XML解析器分别为DOM解析器、SAX解析器和PULL解析器,。

本Demo中使用的是XML的SAX解析方式，因为其解析速度快和占用内存小的优势。

解析代码见initProvinceDatas()方法，




##有问题反馈
在使用中有任何问题，欢迎反馈给我，可以用以下联系方式跟我交流

* 邮件(mrwujay@163.com)
* blog: http://blog.csdn.net/wulianghuan

