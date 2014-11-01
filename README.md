workerman-for-win
=================

workerman windows 版本


此版本为window多线程测试版本，请不要用于生产环境

安装
==============
## 1、要求php为多线程安全版本，标有Thread Safe的版本
PHP5.6线程安全版本下载链接：[http://windows.php.net/downloads/releases/php-5.6.2-Win32-VC11-x86.zip](http://windows.php.net/downloads/releases/php-5.6.2-Win32-VC11-x86.zip)   

## 2、需要安装pthreads扩展
pthreads2.0.9 for php5.6 下载链接： [http://windows.php.net/downloads/pecl/releases/pthreads/2.0.9/php_pthreads-2.0.9-5.6-ts-vc11-x64.zip](http://windows.php.net/downloads/pecl/releases/pthreads/2.0.9/php_pthreads-2.0.9-5.6-ts-vc11-x64.zip)  

安装方法见下载包中的readme，需要拷贝两个文件，设置以下php.ini加入pthreads扩展

## 3、设置php的环境变量
将下载的php放到环境变量里面


## 其它相关链接
  * [PHP其它版本链接](http://windows.php.net/download/)
  * [pthreads其它版本链接](http://windows.php.net/downloads/pecl/releases/pthreads/)

启动
=======
  * 打开workerman-for-win的文件夹，双击start.bat 即可启动

停止
======
  * 启动后看到一个终端界面，按ctrl+c停止服务；或者点击右上角关闭图标停止服务

说明
======
workerman windows多线程版本接口上与linux多进程版本是兼容的，一般来说在windows版本上开发的程序也可以在linux多进程版本中运行。

