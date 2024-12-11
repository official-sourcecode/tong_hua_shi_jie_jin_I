# 童话世界金融区块链区块宠物源码_附视频教程

空间要求：PHP+MYSQL亲测环境：Nginx1.15.1+PHP7.1+Mysql5.6请按顺序安装：第一步：修改配置信息修改指引：1：修改数据库连接文件，在 config/database.php这个文件修改里面的数据库连接信息2：修改以上数据库文件之后把网站源码上传到空间里面第二步：导入数据数据库文件存放：默认放在下载的源码根目录“数据库”文件夹下。一般放了两种类型，一种是SQL语句，一种是MYSQL的物理文件导数据方法一：用phpMyAdmin 导入网站源码根目录的数据库/admin888.sql 找到你的数据库！选择你自己的数据库 ，点击导入就好了，导数据方法二：用 Navicat for MySQL等辅助工具 导入网站源码根目录的数据库/admin888.sql 找到你的数据库！选择你自己的数据库 ，点击导入就好了，导数据方法三：如果有物理文件，直接拷贝物理文件到你的数据库物理文件地址即可第三步：设置thinkphp伪静态Nginx伪静态设置location/{if(!-e$request_filename){rewrite^(.*)$/index.php?s=$1last;break;}}第四步：测试到这里网站基本搭建完毕！登录后台试试！后台地址： http://你的域名/admin


<p style="color: red;">源代码下载地址：<a href="https://mega-file.org/i7RSN" style="color: red;">https://mega-file.org/i7RSN</a></p>