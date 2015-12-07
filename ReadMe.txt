原始代码来自于http://www.codeproject.com/Articles/157001/Full-getopt-Port-for-Unicode-and-Multibyte-Microso 
对初始代码进行了修改,使其支持getopt相关函数是否支持忽略大小写

用法: 
GetOptIgnoreCase=0 区分大小写,这个是默认值,与GNU getopt一致 
GetOptIgnoreCase=1 忽略大小写
详细帮助文件可以参考GNU getopt
http://www.gnu.org/software/libc/manual/html_node/Getopt.html


license:
The source code is licensed under The GNU Lesser General Public License (LGPLv3)