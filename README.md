miac-website
=======================

[中山大学现代互联网应用俱乐部（MIAC）网站](http://sysumiac.com)


## 功能设想
* 发布文章: 
	* 俱乐部成员可以发布技术文章
	* 其他成员可以评论、分享
* 分享：
	* 类似于微博发布，限定140字
	* 带分类标签（技术、心情、吐槽等），可以用来过滤
	* 可带附件（资料分享）
* 讨论墙
	* 发布一个话题
	* 可以在下面进行评论、讨论
	* 赞同、反对
* 相册
	* 俱乐部成员可以上传俱乐部图片
* 作品展示
	* 上传作品

## 团队构建
* 分享和讨论：wiki
* 协同工作：github
* 任务管理：issues
* 文档管理：wiki、README

## 技术架构
（考虑到参与项目人员学习成本问题，暂采用比较传统的架构，以后可以往SPA上迁移）
* 版本管理（git & github）
* 后端
	* 语言：PHP
	* MVC框架：ThinkPHP
	* 数据库：MySQL
* 前端
	* jQuery
	* Grunt
	* Flat UI

## License
[MIT](http://mutedsolutions.mit-license.org/)

