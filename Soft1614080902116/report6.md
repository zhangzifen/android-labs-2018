实验六

一.实验目的

掌握Android网络访问方法；

二.实验内容

从网络下载一个文件（图片、MP3、MP4）；<br>
保存到手机，在应用中使用文件；<br>
将应用运行结果截图

三.实验步骤

1.再另外新建一个activity，作为新的活动界面，即下载图片的界面

2.先修改AndroidManifest.xml获取相关的权限<br>，再对前面的活动界面的下载按钮添加一个监听按钮，使它跳转到新的界面

3.在新的界面添加edittext和imageview布局，分别用来存储图片地址和下载后图片显示，编写线程进行获取url，输入输出，并且完成下载

4.连接手机，尝试运行，运行成功后再进行截图上传

四.实验结果

![image](https://github.com/zrh116/android-labs-2018/blob/master/Soft1614080902116/%E5%AE%9E%E9%AA%8C6-1.jpg)

![image](https://github.com/zrh116/android-labs-2018/blob/master/Soft1614080902116/%E5%AE%9E%E9%AA%8C6-2.jpg)

五.实验体会

这次实验我做的是进行图片的下载，通过查阅并参考资料，一步步地完成实验要求，中间运用线程来获取图片信息，但其中遇到了图片无法显示的问题，但后来请教同学，
要在Minifestxml进行权限的设置后才能运行，但最后还是顺利完成了实验。
