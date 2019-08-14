YfwHome_LiveCamera 介绍
=================
1、本程序基于GatewayWorker开发的物联网监控系统 

YfwHome_LiveCamera 版本 
=================
 版本1.0
 
 功能：
* 1、视频设备接入
* 2、客户端视频实时播放

![实时监控系统展示](https://github.com/Yangfeiwu/YfwHome_LiveCamera/blob/master/image/yfwhome_angular.gif)



YfwHome_LiveCamera 使用
=======================
*支持谷歌，火狐等浏览器

*视频流上传：

打开火狐浏览器，打开url输入： http://你的服务器地址：8088/camera.html  (html会调用你的摄像头上传视频流到服务器)

*观看视频流：

打开火狐浏览器，打开url输入： http://你的服务器地址：8088 （从服务器读取视频流）

目录结构
=======================
image  图片目录
vendor  workerman项目目录
Web     web目录
|--- camera.html   视频流上传
|--- index.html    视频流输出
yfwdoc  教程文档
start.php   启动全部服务
start_web.php 启动web服务
start_worker.php 启动workerman服务

程序启动与停止
=================
php start.php start  启动程序
php start.php start -d  后台启动程序 
php start.php stop   结束程序
