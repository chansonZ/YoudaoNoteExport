# YoudaoNoteExport
导出有道云笔记，保存为JSON和DOCX/XML文件。DOCX/XML文件是笔记的内容，JSON文件是笔记的其它信息（包括标题、创建时间、修改时间等）

**注意：没有下载图片以及其它内容，只有文字。**

---------------------

本文来自 wesleyflagon 的CSDN 博客 ，全文地址请点击：https://blog.csdn.net/wesleyflagon/article/details/78979476?utm_source=copy 

使用方法：

python main.py 用户名 密码 [存盘目录 [文件类型]]

文件类型是xml（默认）或docx


举例：

mkdir notes

python main.py 用户名 密码 ./notes docx


在Ubuntu 16.04 + Python 2.7的环境中测试通过。
