# 猫娘乐园主题后台管理界面
基于FreshUI_V3.1进行二次开发

## 使用方法

<font color='red'>0、万事先备份，防止火葬场，**建议直接整站压缩备份**</font>>

1、直接 **删除** 网站根目录 **admin** 文件夹，**新建admin文件夹**，将压缩包内所有文件解压到admin文件夹内

2、移动  **Menu.php** 到网站根目录 **var/Widget** 文件夹内，清理浏览器缓存

3、修改网站后台的左上角logo

在`admin/FreshUi.php`中，将

```php

<a class="navbar-brand brand-logo" href="index.php"><img src="img/logo.png" alt="logo"></a>
<a class="navbar-brand brand-logo-mini" href="index.php"><img src="img/logo-mini.png" alt="logo"></a>

```
中的src修改为你的头像的地址即可！







