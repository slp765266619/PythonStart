## python自学项目

将在这里分享自学python中得一些坑，和项目应用
### 既然是自学就会有一些计划

将按照天数对应学习内容，标注为一天的不代表学习只用一天，只是代表一个学习内容

## 第一天 主要是变量的学习
1.1 python安装（win和linux下）
1.2 ipython安装及使用
1.3 变量的定义
1.4 变量赋值
1.5 运算符（赋值、算术、关系、逻辑）
1.6 表达式
相关练习：写一个四则运算器，要求从键盘读取数字
体会input()与raw_input()区别
扩展知识：十进与十六进制互相转换、十进制与字符串互相转换
## 第二天 数据类型
1.1 数值类型（整型、长整型、浮点型、复数型）

1.2 序列之字符串类型（引号的使用、下标与切片）
1.3 序列之元组
1.4 序列之列表（增、删、改、查及一些方法，体会对象的方法）
1.5 获得帮助
1.5.1 ipython下使用help命令获得帮助信息
1.5.2 https://docs.python.org/2/library
1.6 相关练习：1）字符串转换成列表---list()函数
              2）列表转换成字符串---字符串的join()方法
扩展知识：去掉列表里的重复元素，体会set()的使用
## 第三天 字典
1.1 字典的创建
1.2 字典的访问：keys()、values()、items()、iteritems()等方法
1.3 字典的更新：update()方法
1.4 删除字典里的元素及字典
1.5 遍历字典
知识扩展：把2个列表存到一个字典里，其中一个列表的各个元素分别作为字典的key，另一个列表的各个元素作为字典的value。掌握dict()函数的使用
## 第四天 流程控制
1.1 if语句语法格式
1.2 理解布尔值True和False
False的为：
空列表([] )、空元组(() )、空字典({} )、空字符串('' )、零值(0 )、特殊对象None、对象False（很明显）。
除了以上几点以外的所有东西都视为"True"
1.3 体会条件表达式
1.4 for循环语法格式
1.5 range()与xrange()
1.6 使用for遍历序列与字典
1.7 使用for遍历文件

相关练习：打印乘法口诀表
## 第五天 流程控制
1.1 while循环语法格式
1.2 文件对象的一些方法，read()、readline（）、readlines（）
1.3 使用while遍历文件
1.4 break与continue

相关练习：
统计系统的free的内存
扩展练习：
统计apache进程所占的内存及百分比
## 第六天 函数
1.1 函数定义
1.2 函数参数
1.3 默认参数
1.4 函数变量
1.5 全局变量
1.6 函数返回值
1.7 函数的多类型传值和冗余参数

相关练习：判断一个字符串是纯数字，使用函数
使用字符串的isdigit()方法改造上面的例子

## 第七天 函数
1.1 函数的递归调用
1.2 os模块下的一些方法：os.path.isdir、os.path.isfile、os.path.join、os.listdir
1.3 匿名函数lambda

相关练习：递归列出目录里所有文件

## 第八天  内置函数与模块
1.1 常用函数
abs()
max()
min()
len()
divmod()
pow()
round()
callable()
type()
isinstance()
cmp()
range()
xrange()

1.2 类型转换函数
int()
long()
float()
complex()
str()
list()
tuple()
hex()
oct()
chr()
ord()
eval()

1.3 模块的使用
1.4 PYTHONPATH变量

相关练习：求相邻的mac地址。
例如已知mac地址：00:0C:29:D1:6F:E9，下一个相邻的mac地址是：00:0C:29:D1:6F:EA


## 第九天 面向对象编程
1.1 简单了解面向对象
1.2 了解类和对象
1.3 掌握类的创建
1.4 掌握类的属性：公有属性、私有属性、内置属性
1.5 掌握类的方法：公有方法、私有方法、类方法、静态方法
1.6 装饰器及使用
1.7 魔法方法：__str__()、__init__()、__del__()

## 第十天 面向对象编程
1.1 类的继承
1.2 类多重继承
1.3 掌握super函数
1.4 类的总结

相关练习：
使用类创建一个rc脚本，以memcached为例
通过这个例子，对类的使用有一定了解，加深及巩固关于类的一些概念。


## 第十一天 Python如何使用标准输入及输出
1.1 掌握python下的标准输入sys.stdin
1.2 python对文件操作的一些方法:
    fd.read()、fd.readline()、fd.readlines()
1.3 掌握python下的输出sys.stdout、sys.stderr
1.4 理解locals()的含义
1.5 掌握sys.argv的使用，对比shell下的$0,$1...$n

知识点扩充：内置变量__file__
相关练习：
使用python实现类似tee的命令。

## 第十二天 optparse模块的使用
1.1 重点掌握optparse模块的使用
1.2 OptionParser类的方法add_option()和parse_args()
1.3 理解add_option()方法的一些参数：dest、action、default、help
1.4 在程序中使用函数，是程序层次分明
1.5 支持统计多个文件

相关练习
写个程序统计文件大小，例如：1.py [-H] filename
支持-H选项，以可读的方式显示文件文件，1-1024B直接显示文件大小，比如100。1k-1M以单位K显示，例如10K。1M-1G之间以单位M显示，例如10M。

## 第十三天 wc命令支持-n选项
1.1 理解__name__
1.2 给wc添加-n选项
1.3 掌握os.path下的一些方法：
    os.path.exists()
    os.path.isfile()
    os.path.isdir()

相关练习：
统计目录大小，类似du命令，支持-H（readable）

## 第十四天 hashlib模块与生成器
1.1 掌握hashlib模块
1.2 掌握os.walk模块
1.3 理解生成器的概念，与return的区别
1.4 练习
1.4.1 计算某个目录下文件的md5sum
1.4.2 计算某个目录的md5sum
1.4.3 找到目录中内容相同的文件
1.5 字典排序，按照key或者value排序

相关练习：
找出目录中占用空间大的前10个文件。

## 第十五天 Python作为胶水语言调用外部命令
1.1 python调用外部命令的方法
1.1.1 os.system
1.1.2 os.popen
1.1.3 os.popen2
1.1.4 os.popen3
1.1.5 os.popen4
1.2 subprocess.call

相关练习：
使用以上方法执行ifconfig和chown命令，体会各自的执行结果

## 第十六天  异常处理
1.1 捕获异常
1.2 处理异常
1.3 自定义异常
1.4 异常的语法结构
1.5 掌握glob模块的用法
1.6 掌握shlex模块的用法

## 第十七天 Popen的使用
1.1 重点掌握subprocess模块的Popen
1.2 理解管道PIPE
1.3 掌握一些方法及属性
    p.stdout.read()
    p.communicate()
    p.pid

相关练习:
收集主机信息
1. 主机名：hostname
2. IP地址：ip
3. 操作系统版本：osver
4. 服务器厂商：vendor
5. 服务器型号：product
6. 服务器序列号：sn
7. cpu型号：cpu_model
8. cpu核数：cpu_num
9. 内存大小：memory

作业：收集主机mac地址。提示使用tcpdump -nn -i eth0 port 68 -l

## 第十八天 正则表达式
1.1 掌握正则表达式
1.1.1 元字符
1.1.2 一些方法findall、match、search
1.2 掌握一些flag
1.3 匹配syslog
1.4 分组

相关练习：
使用正则表达式收集主机网卡名、ip地址、mac地址

## 第十九天 web开发框架django
1.1 安装django
1.2 创建工程项目与应用
1.3 理解MTV模型
1.4 掌握settings.py、urls.py、views.py这些文件
1.5 了解一些数据类型：CharField、IPAddressField、IntegerField等。
1.6 启动runserver
1.7 定义数据模型并访问数据

扩展知识：看django官方文档
https://docs.djangoproject.com/en/1.8/ part1-3
http://djangobook.py3k.cn/2.0/

## 第二十天 CMDB项目
1.1 创建SimpleCMDB项目
1.2 导入数据，使用curl
1.3 使用post和get方法传递数据
1.4 导入数据，使用urllib
1.5 主机分组
1.6 掌握models.py文件

相关练习：创建应用hostinfo，使用收集脚本把信息存到cmdb。


## 第二十一天 序列化
1.1 了解序列化
1.2 掌握pickle模块
1.3 掌握json模块
1.4 django连接mysql数据库
1.5 安装MySQLdb模块，分别使用rpm包及pip方式

相关练习：改写收集脚本使用json模块

## 第二十二天 实现API
1.1 编写API
1.2 考虑使用什么样的数据结构
1.3 json格式的API
1.4 shell格式的API

相关练习：调用API，查看主机组里有哪些主机

## 第二十三天 django与apache或者nginx整合
1.1.1 gunicorn模块安装
1.1.2 整合django与nginx
1.2.1 wsgi模块安装
1.2.2 整合django与apache


## 第二十四天 nagios配置文件生成器
1.1 nagios安装
1.2 nagios配置文件生成器--gen.py
1.2.1 通过API，得到主机和组的信息
1.3 使用序列化保证cmdb的数据有效性

相关练习：通过cronjob，定期执行gen.py，产生nagios的配置文件

## 第二十五天 插件编写
1.1 编写nagios插件原则
1.2 使用shell编写插件
1.3 使用python编写插件
1.4 监控内存插件
1.5 datetime模块的使用
1.6 监控syslog插件

相关练习：编写监控syslog的插件，1分钟内出现相同的错误3次报警，并发邮件。

## 第二十六天 监控远程主机
1.1 NRPE插件
1.2 监控远程主机的内存
1.3 监控远程主机的syslog


## 第二十七天 多线程--thread模块
1.1 多线程介绍
1.2 thread模块
1.3 线程锁的使用

相关练习：使用两个线程输出hello world

## 第二十八天 多线程--threading模块
1.1 threading模块
1.2 启动线程的两种方法
1.3 互斥锁
1.4 线程间通信Queue模块，理解生产和消费


## 第二十九天 多进程--multiprocessing
1.1 multiprocessing模块
1.2 进程池Pool


## 第三十天 paramiko模块
1.1 paramiko模块
1.2 并行命令
1.3 fabric模块

相关练习：结合CMDB，实现并行命令
知识扩展：dsh、pdsh的使用

## 第三十一天 saltstack
1.1 安装saltstack
1.2 体会salt命令
1.3 学会查看官网文档
1.4 sls文件格式

知识扩展：
使用pip方法安装saltstack

## 第三十二天 target
1.1 体会state.sls与state.highstate
1.2 理解target
1.2.1 glob
1.2.2 grains
1.2.3 compound
1.2.4 nodegroup

## 第三十三天 编写模板
1.1 sls文件模板
1.2 配置文件模板
1.3 saltstack与SimpleCMDB整合

## 第三十四天 mysql工具箱
1.1 掌握ConfigParser模块
1.2 理解类的继承
1.3 掌握函数的冗余参数与多类型传值
1.4 掌握getattr与setattr函数
1.5 完成mysql.py库

## 第三十五天 创建mysql实例
1.1.1 理解包的创建
1.1.2 使用包
1.2.1 创建mysql实例
1.2.2 掌握optparse模块
1.2.3 掌握subprocess模块

## 第三十六天 调整mysql配置文件参数
1.1 掌握MySQLdb模块的使用
1.2 mysql配置文件检查
1.3 两个字典的比较
1.4 mysql配置文件调整

## 第三十七天 AB复制
1.1 mysql的AB复制原理
1.2 创建主库
1.3 创建从库

## 第三十八天 mysql备份
1.1 mysql的备份
1.2 掌握datetime模块
1.3 mysql恢复
1.4 则正表达式的使用

## 第三十九天 ddns
1.1 配置dns
1.2 nsupdate命令
1.3 python dns模块
1.3.1 dns.query的使用
1.3.2 dns.message的使用
1.3.3 dns.tsigkeyring的使用

## 第四十天 通过DNS实现从库的LB集群
1.1 检查mysql从服务器的状态
1.2 dns动态记录更新

## 第四十一天 CMDB整合

## 第四十二天 网络编程
1.1 socket介绍
1.2 socket编程
1.3 实现ftp服务器

## 第四十三天 SocketServer模块
1.1 SocketServer模块
1.2 实现ftp server

## 第四十四天 graphite+carbon+whisper
1.1 安装graphite
1.2 graphite工作原理
1.3 统计网卡流量

## 第四十五天 统计apache日志的code
1.1 分析apache日志
1.2 文件倒读
1.3 理解文件的方法：
    read()
    seek()
    tell()

## 第四十六天 使用文件倒读统计apache的code

## 第四十七天 diamond
1.1 安装diamond
1.2 自定义收集器
1.3 修改diamond
1.4 统计apache日志的code

## 第四十八天 源码安装python
1.1 源码安装python2.7
1.2 源码安装pip
1.3 源码安装ipython

## 第四十九天 源码安装graphite套件
1.1 源码安装graphite套件
1.2 源码安装diamond
1.3 apache与graphite整合
1.4 分析自动化运维思路

## 第五十天 日志统计工具
1.1 logstash安装
1.2 编写logstash配置文件
1.3 分析多个日志文件

## 第五十一天 logstash扩展
1.1 logstash+statsd+graphite
1.2 Diamond与statsd测试比较

## 第五十二天 logstash一些插件
1.1 file插件
1.2 date插件
1.3 分析php的错误日志，正则表达式的使用
1.4 punct插件

## 第五十三天 ELK整合
1.1 php日志在graphite上展示
1.2 ELK整合

## 第五十四天 代码管理
1.1 安装jenkins
1.2 jenkins管理应用代码
1.3 客户端部署脚本编写
1.3.1 使用urllib2下载应用代码
1.3.2 对下载的文件校验，hashlib模块
1.3.3 tarfile模块

## 第五十五天 代码的版本控制
1.1 版本控制：livever、lastver
1.2 回滚
1.3 文件锁

## 第五十六天 fabric模块的使用
1.1 fabric检查状态
1.2 整体测试

## 第五十七天 kvm虚拟机的管理
1.1 安装kvm虚拟机
1.2 qemu-kvm命令
1.3 virsh命令

## 第五十八天 安装虚拟机
1.1 掌握libvirt模块
1.2 编写程序获取虚拟机信息
1.3 编写安装虚拟机工具
