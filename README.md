# SadFile

版本：1.3.5


**更新记录：**

1.3.1 - 2019-3-16：
添加搜索功能，部分逻辑修改

1.3.5 - 2019-4-17：
修改数据库连接方式支持PHP7.0或以上版本，重新修改了程序目录结构，不再那么混乱，修改了几处小的体验，改了部分php代码。
[1.3.5更新方法点此](update.md)

1.4：
待更新的任务，时间较少，请等待，有其他需求请issues

- [ ] 添加阿里OSS存储方式，支持多种存储并存的存储模式
- [ ] 添加自有的远程服务器的存储方式
- [ ] 修改前端样式结构，更好的用户体验
- [ ] 部分PHP代码重写
...
------

一款极简的个人云盘程序
PHP开发，真的比较简单，就一些比较基本的功能，部分地方体验并算不上完美。
PHP开发新手，懂得不是很多，望大佬口下留情，有问题欢迎提出，我会积极改正

目前只支持对接七牛云存储，不支持存储本地获取对接远程存储服务器，其他的如又拍、阿里等以后看情况添加。所以使用本程序，必须要有七牛云对象存储，建立一个**私有的bucket**，七牛云每月都有免费的额度：https://www.qiniu.com/prices 。如有需要可以自己购买增加。

得利于丰富的接口及支持，本程序支持断点续传、分片上传。



我觉得，这个程序对于一个普通人应该能满足使用需求。



### 一、安装

这个程序安装需求很简单。

**安装环境**： php  5.4以上  mysql 5.5及以上

**安装步骤**：访问 域名/install.html 即可 支持虚拟主机安装

注意安装前，删除根目录下的install.lock文件

**二、程序功能**

1. 基本的文件、文件夹管理（删除、移动、创建、重命名、文件搜索等）
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

**截图展示**
![首页.png](https://i.loli.net/2019/02/01/5c53eacb3c117.png)
![主页.png](https://i.loli.net/2019/02/01/5c53eae6ed075.png)
![11111无标题.png](https://i.loli.net/2019/02/01/5c53eb0ab97a6.png)
![11无标题.png](https://i.loli.net/2019/02/01/5c53eb3ab7897.png)
![111111无标题.png](https://i.loli.net/2019/02/01/5c53eb3ae0f53.png)
![111无标题.png](https://i.loli.net/2019/02/01/5c53eb977b694.png)
![无标题.png](https://i.loli.net/2019/02/01/5c53ec9fda46f.png)

等等...
