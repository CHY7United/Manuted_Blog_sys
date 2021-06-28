浙江财经大学信息管理与人工智能学院 18计算机2班陈泓禹
开源软件开发课程大作业
基于Express+mongodb+Nodejs基础开发
借鉴了Github上两位博主的demo 以此开发的简单功能的程序

##### api 接口路由
	 / 				首页
  	 /register    用户注册
 	 /login      用户登录
 	 /comment    评论获取
	 /comment/post  评论提交
	 
	 
##### main 模块
	/                首页
 	/view            内容页


##### admin 模块//管理模块
	   /                            首页
	  ##用户管理
	  /user                        用户列表
	  ##分类管理
 	  /category                    分类列表
 	  /category/add                分类添加
 	  /category/edit               分类修改
 	  /category/delete             分类删除
 	  ##文章内容管理
     /article                     文章列表
     /article/add                 文章添加
     /article/edit                文章编辑
     /article/delete              文章删除
     ##评论内容管理
     /comment                     评论列表
     /comment/delete              评论删除


