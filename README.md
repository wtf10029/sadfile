# SadFile

版本：1.3.0

------

一款极简的个人云盘程序
PHP开发，真的比较简单，就一些比较基本的功能，部分地方体验并算不上完美。
PHP开发新手，懂得不是很多，望大佬口下留情，有问题欢迎提出，我会积极改正

目前只支持对接七牛云存储，不支持存储本地获取对接远程存储服务器，其他的如又拍、阿里等以后看情况添加。所以使用本程序，必须要有七牛云对象存储，建立一个**私有的bucket**，七牛云每月都有免费的额度：https://www.qiniu.com/prices 。如有需要可以自己购买增加。

得利于丰富的接口及支持，本程序支持断点续传、分片上传。



我觉得，这个程序对于一个普通人应该能满足使用需求。



### 一、安装

这个程序安装需求很简单。

**安装环境**：php 5.4及以上+mysql 5.5及以上

**安装步骤**：访问 域名/install.html 即可 支持虚拟主机安装



**二、程序功能**

1. 基本的文件、文件夹管理（删除、移动、创建、重命名等）
2. 部分文件支持在线预览（如图片、视频等）
3. 文件的分享功能
4. 文件分享管理（取消分享、修改提取密码、下载次数）
5. 程序的系统设置（基本设置、七牛云配置、万能提取码、关闭分享功能等）
6. 参考其他程序而出现的图廊页面（支持开启关闭图廊、开放图廊（查看图廊是否需要登录）、指定图廊显示图片的目录）
7. 等等....



**三、当前版本缺陷**

1. 移动端支持，但是适配的并不好，主要是我懒。
2. 登录后的主页，用以显示基本信息的，有好几个地方并没有完善（并不影响使用）
3. 部分功能页面，体验还差点火候
4. 程序设计、语法上由于新手，所以还是存在一些不符合规范的问题
5. ...

**四、使用到的框架**

php没有用到框架，主要是前端

**amazeui**-HTML5 跨屏前端框架

**五、鸣谢**

HTML5UP-图廊使用了它的multiverse模板

还有我自己，然后没了。

**六、相关版权**

作者：术与道    

MIT 授权许可