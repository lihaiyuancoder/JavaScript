<!--
 * @Description: 
 * @Autor: lihaiyuan
 * @Email: lihaiyuan@goldenfintech.com.cn
 * @Date: 2020-01-16 09:53:36
 -->
复制：
mkdir  只能建在当前目录下
如果上一级目录不存在则用：
mkdir -p 文件多级目录下
减压文件：
tar zxvf 文件夹

如果安装了zip压缩工具则：
解压：
unzip 加压文件.zip
减压到指定目录下：
2.unzip
unzip -o -d /home/sunny myfile.zip
把myfile.zip文件解压到 /home/sunny/
-o:不提示的情况下覆盖文件；
-d:-d /home/sunny 指明将文件解压缩到/home/sunny目录下

压缩文件：
将当前文件下的所有文件全部压缩：
zip -r 压缩文件.zip ./*

删除压缩文件的内容：
zip -d 压缩文件.zip  删除的文件
向压缩文件中添加文件
zip -m 压缩文件.zip  ./添加文件

跨文件夹压缩：
zip -r filename.zip file1 file2 file3 /usr/work/school
上面的命令把 file1、file2、 file3、以及 /usr/work/school 目录的内容（假设这个目录存在）压缩起来，然后放入 filename.zip 文件中。






 
