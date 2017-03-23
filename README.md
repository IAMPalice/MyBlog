# 项目背景
因为自学了Java开发和一些框架，虽然大致了解工作流程，但是没有具体实现过还是不行，所以就想着做个东西出来练练手，
刚好在学习java期间一直在CSDN上记录学习过程，
所以就想着做一个小型的博客平台，实现基本的用户登录、文章编写与发布、文章分类归档等功能。
# 项目介绍
## 使用的工具与技术
  使用MySQL数据库存储数据，Eclipse为开发工具，JDK使用的是1.7版本，Tomcat使用的是8.11版本。
  后端使用S2SH框架组合进行开发，页面使用EL表达式和OGNL表达式进行数据渲染。
  部分异步请求的页面使用jQuery进行ajax请求，Vue.js进行数据渲染，Bootstrap框架搭建前端页面。 
  其中编写文章使用的是自制的一个简易markdown编辑器，用marked.js进行markdown语法解析，然后用highlight.js进行语法高亮。
## 各模块的功能
### 首页
  #### 主要功能有：
    显示网站上的所有文章
    按访问数显示推荐博主
    显示文章的分类
    查看文章详情与访问用户博客
  ### 界面如下：
 ![image](http://github.com/OverrideRe/MyBlog/raw/master/Pictures/Home.png)
### 我的博客
### 个人中心
### 博客管理
### 文章编写
# 遇到的问题与感想

