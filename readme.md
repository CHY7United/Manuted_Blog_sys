浙江财经大学信息管理与人工智能学院 18计算机2班陈泓禹\
《开源软件开发课程大作业》————曼联足球俱乐部球迷论坛系统\
基于Express+mongodb+Nodejs基础开发\
感谢潘峰老师课程内容，借鉴了Github上两位博主的demo，以此开发的简单功能的程序\
在未来还需要进行更多的改进内容... 


### 使用说明：
1. 首先需要搭建mongodb数据库环境，https://www.mongodb.org.cn/ ，详细可以看《MongoDB 4.2手册》
2. 在Visual VScode环境中进行Express环境搭配 -> npm install
3. 在开始使用的过程中，首先需要在当前工作文件夹中的terminal开启mongodb，->mongodb ->mongod --dbpath
4. app.js 进入'Server is running at http://localhost:8081'
5. 除此之外还可以进行数据库查看db.stats(); 更多功能可以利用mongodb手册进行使用。

### 课程要求
期末考核采用项目形式，要求提交完整的可运行的project，与说明书一起打包，上传彩云相应目录下。项目类型限定为B/S类型的信息管理系统或信息处理系统。系统编程语言限定为nodejs，数据库必须使用mongodb，但还可以使用其他数据库；后端框架express（可选其他类型）。可以引用，但必须注明出处，不可以与别人的系统构思和结构完全相同，不可以有法律风险。在程序中尽量详尽的写出注释。

1．数据管理系统评分标准： 
1)包含用户注册登录界面，能够区分管理员和普通用户。（10分） \
2)数据库设计部分。（10分）\
及格标准：Mongodb至少使用三个collection，每个collection至少20个测试数据，每个document至少三个字段。\
3)有数据查询显示功能，要求体现在具体的实际功能中。（20分）\
及格标准：有两个collection的联合查询功能。\
4)网站有实用功能。（20）\
5)界面美观，程序撰写规范。（10）\
6)其他。（10分）\
7)网站设计运行说明书。（10分）\
8)项目版本管理使用git，公开，其他人可以从远程仓库下载。网站设计运行说明书中要给出下载链接。（10分）

2．信息处理系统评分标准：
基本要求：数据库数据具备数据更新功能，数据要求能自动从网上实时获取，能够对数据进行处理，至少包括数据清洗、统计和曲线显示功能。
1)	包含用户注册登录界面，能够区分管理员和普通用户。（10分）
2)	数据库设计部分。（10分）
3)	数据自动获取、存储和分析。（30分）
4)	网站有实用功能。（10）
5)	界面美观，程序撰写规范。（10）
6)	其他。（10分）
7)	设计运行说明书。（10分）
8) 项目版本管理使用git，公开，其他人可以从远程仓库下载。网站设计运行说明书中要给出下载链接。（10分）。
