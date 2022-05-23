# Python学生信息管理系统-By CaixyPromise

#### 介绍
Python学生信息管理系统。学生教师端分离，支持数据的增删查改、数据分析与统计。

#### 软件架构
Python3.9版本
Python-Tkinter库开发的图形界面
Python-Pandas库数据处理
Python-matplotlib库数据分析与展示
Python-Pickle库登录信息序列化处理（Pickle版本：Python3.9-5） **低于该版本的Python，可能会出现无法读取当前版本的pickle文件** 。

#### 软件功能
- 学生、教师登录
- 成绩分析与统计
- 成绩登记、发布与导出
- 添加班级信息与管理

#### 默认测试账号
 **初始默认管理员账号密码为admin,admin** 
可以使用pickle或pandas.pickle模块的读user_data文件下的udpk文件获取详细账号信息，student为学生，teacher为老师

#### 文件目录
-  work_data
- ​	.udsc格式文件 本质为csv文件转型，已登记完成的成绩文件
- user_data
- ​	|-- .udcl格式文件 pickle加密文件，各班最新发布成绩文件
- ​	|-- .udpk格式文件 pickle加密文件，student和teacher分别是学生、教师的账号信息
- ​					 其中包含了账号、密码、所在班级信息
- class_data
- ​	|-- .csv格式文件 班级成员信息
- img
- ​	|-- welcome.png 登录界面背景图
