# joomla
using akeeba kickstart restore a website

step to recover
1.首先确保xampp运行正常
2.在phpadmin页面建立root用户 确保有最高权限
3.在htdoc文件夹内 将kickstart内两个文件和要恢复的网站备份文件放入同一个文件夹
4.localhost运行kickstart.php 按提示操作即可


注意：
如用mac，确定文件夹权限问题，不然会出现很多问题，无法启动。
window下确保数据库链接，备份文件中有数据库可以自动回复，kickstart引导页面非常简单，但是建议新建一个名字不同的数据库和用户，用于储存恢复的数据库结构。
