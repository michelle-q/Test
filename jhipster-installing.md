1. node.js 和npm 安装
 官网下载node js[下载地址](https://nodejs.org/en/)
==安装yeoman之前需要安装Ruby 和compass==
2. 安装git，jhipster自动构建时会用到git
 
3.compass  
> Compass 是一个用来开发 CSS 的工具，yeoman启动时需要依赖这个工具  
> 安装compass前需要安装ruby   
[教程](http://blog.csdn.net/dw1067061570/article/details/54947106)
安装成功后配置环境变量：D:\Program Files (x86)\Ruby\bin
 ruby安装成功后安装compass
所以我们只能使用本地安装的方式来安装。本地安装需要下载4个文件：SASS，Chunky_png，Fssm和Compass，下载地址分别为：
SASS.gem: http://rubygems.org/downloads/sass-3.2.13.gem
Chunky_png.gem: http://rubygems.org/downloads/chunky_png-1.2.9.gem
Fssm.gem: http://rubygems.org/downloads/fssm-0.2.10.gem
Compass.gem: http://rubygems.org/downloads/compass-0.12.2.gem

将这4个文件放在ruby的安装根目录下，如我安装在D:\Program Files (x86)\Ruby，然后打开控制台切换到ruby的安装目录
```
gem install sass
sass -v

gem install compass
gem install fssm
gem install chunky_png
# 以上三个都安装成功，查看compass版本才会成功
compass -v
# 卸载
gem uninstall compass
```
4. yeoman
[安装教程](http://blog.csdn.net/u012586558/article/details/52923358)
```
# yeoman
npm install -g yo
# bower
npm install -g bower
# grunt
 npm install -g grunt-cli 
/npm install -g gulp
```
安装成功后需要将安装路径配置到环境变量，yo.cmd所在路径。D:\Program Files (x86)\nodejs\node_global添加到path中



5. phantomjs 安装
> 　PhantomJS是一个基于webkit的JavaScript API。它使用QtWebKit作为它核心浏览器的功能，使用webkit来编译解释执行JavaScript代码

下载地址：https://pan.baidu.com/s/1o9sGsOU 提取码：dovx

解压后，配置环境变量。在path中添加phantom的解压路径。D:\phantomjs\bin
配置成功后可以查看版本号
```
phantomjs --version
```
6. 安装jhipster 

```
npm install -g generator-jhipster
```
