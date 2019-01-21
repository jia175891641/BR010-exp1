
# 简介
【BR010-综合实例1】功能:监视感应器有没有在一定时间内感应。假如超过2秒内未感应 报警
# 程序预览
这里提供2个版本的程序：
## 多线程版本：
原理:采用另外一个监视进程去监视主程序是否在正常运作，优点是灵活性高，报警以后能运行指定的程序
![image](https://github.com/jia175891641/BR010-exp1/blob/master/%E5%A4%9A%E7%BA%BF%E7%A8%8B%E7%89%88%E6%9C%AC.PNG)
## 精简版:  
原理：利用死等语句自带的报警功能，优点是语句简洁，缺点是报警后不能做其他事情(如果要做，也是可以，需要外接线路实现,将报警的输出口外接一个24V的中间继电器去触发急停键或者其他输出口)  
![image](https://github.com/jia175891641/BR010-exp1/blob/master/%E7%B2%BE%E7%AE%80%E7%89%88.PNG)

# 程序下载
      点击 右上方 绿色的`Clone or download` 再点 Download Zip 下载后解压 
      直接双击 .bent  文件，上位机会自动识别或打开，如果需要烧录进控制器，还需要购买烧录器,烧录器驱动
      温馨提示:厂家发货时候，能提供免费烧录服务，欢迎有志之仕在Github上分享您的作品
# 资料参考
如第一次接触此控制器，请先看完以下3个教程，尤其是`在线编程方法`：

视频教程：
BR010基本功能介绍：  
[![Watch the video](https://img.alicdn.com/imgextra/i3/140795238/TB23Vqhm_vI8KJjSspjXXcgjXXa_!!140795238.png)](http://cloud.video.taobao.com//play/u/140795238/p/2/e/6/t/1/50031896985.mp4)  
BR010在线编程方法：  
[![Watch the video](https://img.alicdn.com/imgextra/i2/140795238/TB2M.dlm0rJ8KJjSspaXXXuKpXa_!!140795238.png)](http://cloud.video.taobao.com//play/u/140795238/p/1/e/6/t/1/50066572897.mp4)  
BR010脱机编程方法：   
[![Watch the video](https://github.com/jia175891641/BR010-VB-/blob/master/%E6%8D%95%E8%8E%B7.PNG)](https://cloud.video.taobao.com//play/u/140795238/p/1/e/6/t/1/50066686709.mp4)  

淘宝店铺(右键新窗口中打开)：[BR010可编程一体机](https://item.taobao.com/item.htm?spm=a1z10.3-c.w4002-4148446461.35.4c0494c0LgyZdJ&id=522079098086)  
官方网站(右键新窗口中打开):[浙江浦江奔腾数控设备有限公司](http://www.btcnc.net/ "点击前往")  
上位机下载(右键另存为)：[易语言2.0](http://www.btcnc.net/web/2moto/Downloads/softBR010.zip "右键再点另存为")  
使用说明书:[纸质说明书](http://www.btcnc.net/web/2moto/Downloads/%E3%80%90BR010%E3%80%91%E5%BF%AB%E9%80%9F%E7%BC%96%E7%A8%8B%E6%8C%87%E5%8D%97%E4%B8%8E%E5%AE%9E%E4%BE%8B.doc)  

