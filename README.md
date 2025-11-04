# 前言

欢迎来到基于SSM的诗文爱好者交流系统！本项目旨在为广大诗文爱好者提供一个便捷的交流平台，让大家能够在这里分享自己的作品，欣赏和学习他人的佳作。我们致力于打造一个功能完善、界面友好的诗文交流环境，让诗歌文化在网络世界中得以传承与发扬。

# 内容介绍

基于SSM的诗文爱好者交流系统主要包括以下几个模块：用户模块、诗文模块、评论模块和搜索模块。用户模块负责实现用户的注册、登录、个人信息管理等功能；诗文模块负责实现诗文的发布、编辑、删除和展示；评论模块则让用户可以对诗文进行评论、回复，促进交流；搜索模块帮助用户快速找到感兴趣的诗文。

# 技术介绍

## 语言：Java
## 使用框架：Spring、Springmvc、Mybatis
## 前端技术：JS、Vue、CSS3
## 开发工具：IDEA/Eclipse
## 数据库：MySQL 5.7/8.0
## 数据库管理工具：phpstudy/Navicat
## JDK版本：jdk1.8
## Maven：apache-maven 3.8.1-bin
## 前端环境：Node.Js 12\14\16

# 核心代码

以下是项目中诗文模块的一部分核心代码，用于展示诗文的详情：

```java
// controller层
@RequestMapping(value = "/detail/{id}", method = RequestMethod.GET)
public String detail(@PathVariable("id") Integer id, Model model) {
    Poem poem = poemService.selectById(id);
    model.addAttribute("poem", poem);
    return "detail";
}

// service层
public Poem selectById(Integer id) {
    return poemMapper.selectById(id);
}

// mapper层
<select id="selectById" resultType="Poem">
    SELECT * FROM poem WHERE id = #{id}
</select>
```

# 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

# 项目截图

![封面图片](https://img13.360buyimg.com/ddimg/jfs/t1/338016/26/5750/144421/68b73100Fd4c93750/de302ddec3d06eea.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/293616/20/23970/16223/68b730d8F4e6af219/7011a10b19fd1d79.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/334754/3/8246/89028/68b730d8Fb327b99b/b63d2893a9827279.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/335916/33/5768/20830/68b730d8Fb3081719/7ae50787934051b9.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/326726/5/14989/55926/68b730d9Fb650a932/07df00e112263e1c.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/289139/23/8292/15433/68b730d9Fe33b8469/770e14b78f039ea6.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/337610/5/5656/41502/68b730daF222d4ba1/4f174fd7cc2a8c7c.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/327838/30/14840/67660/68b730daF8dc49705/0ba50dd9bf29b0f7.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/337672/29/5784/50138/68b730dbFf52c01f9/d158b5336c48a300.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/340253/11/5795/73971/68b730dbFb3ceb2f2/d559fa9d50c426ad.jpg)

