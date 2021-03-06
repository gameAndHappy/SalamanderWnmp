# WPF制作的wnmp环境

[![Build Status](https://travis-ci.org/slimphp/Slim.svg?branch=develop)](https://travis-ci.org/slimphp/Slim)
[![Coverage Status](https://coveralls.io/repos/slimphp/Slim/badge.svg)](https://coveralls.io/r/slimphp/Slim)
[![Total Downloads](https://poser.pugx.org/slim/slim/downloads)](https://packagist.org/packages/slim/slim)
[![License](https://poser.pugx.org/slim/slim/license)](https://packagist.org/packages/slim/slim)

## 集成包下载
[下载地址](http://pan.baidu.com/s/1skJzyLR)

## 主界面
![SalamanderWnmp](https://cloud.githubusercontent.com/assets/16663435/23488421/78163122-ff27-11e6-9240-5db785a0da50.png)

## 其他功能
#### 常规设置
![常规设置](https://cloud.githubusercontent.com/assets/16663435/23488508/00fdf128-ff28-11e6-9b2f-711b5a46b5f9.png)


#### 调色面板
![调色面板](https://cloud.githubusercontent.com/assets/16663435/23488548/4fcc4b6a-ff28-11e6-8a1c-cf45b961340d.png)


#### 编程面板
![编程面板](http://git.oschina.net/uploads/images/2017/0222/160849_e369b9e1_433553.png)




## 注意
php 版本为7.0.1 64位版本，需要MSVC14 (Visual C++ 2015)运行库支持，下载：https://download.microsoft.com/download/9/3/F/93FCF1E7-E6A4-478B-96E7-D4B285925B00/vc_redist.x64.exe





## 配置

集成包下有文件：配置.txt
#### php
修改php.ini中的extension_dir配置，改为php目录下ext目录的绝对路径

#### nginx

修改conf目录下nginx.conf中的localhost虚拟主机的root（网站根目录），改为某个目录（譬如D:/web_root）的绝对路径（使用/，使用\会出错）

#### mysql

修改my.ini文件中base_dir和data_dir的配置，分别修改为mysql目录和mysql目录下的data目录的绝对路径


## 联系我
* 我的技术栈：PHP，java，node，C#，Go，VC++/C  喜欢技术的童鞋可以找我交流
* QQ：1906747819
* Blog：http://51nazi.com
* segmentfault：https://segmentfault.com/u/baofan_55d05d0eebd33



