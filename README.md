# larevel_apache
<br>
Enable mod_rewrite <br>
https://hostadvice.com/how-to/how-to-enable-apache-mod_rewrite-on-an-ubuntu-18-04-vps-or-dedicated-server/ <br>
<br>
添加 AllowOverride<br>
<br>
<Directory /var/www/html/your-project><br>
   AllowOverride All<br>
</Directory><br>
<br>
https://www.howtoforge.com/tutorial/install-laravel-on-ubuntu-for-apache/<br>
<br>
给storage赋予权限<br>
<br>
若分配给某个文件所有权限，则利用下面的命令：<br>
<br>
sudo chmod -R 777 文件或文件夹的名字  # 表示对当前目录及目录下所有的文件赋予可读可写可执行<br>
<br>

添加mysql driver
sudo apt install php7.3-mysql

