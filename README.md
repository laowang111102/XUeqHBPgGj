## 前言

您好！这是一个关于“培训咨询微信小程序+SSM”的项目。在这个项目中，我们采用了一系列前沿的技术手段，构建了一套完善的培训咨询微信小程序。以下是关于本项目的详细介绍。

## 内容介绍

本项目旨在为广大用户提供便捷的培训咨询服务。通过微信小程序，用户可以随时随地了解各类培训课程信息、预约课程、咨询问题等。后台管理系统采用SSM框架，确保了系统的高效稳定运行。此外，项目还具备良好的可扩展性，方便后期根据需求进行功能拓展。

## 技术介绍

- **语言：** Java
- **使用框架：** Spring、SpringMVC、MyBatis、微信小程序
- **前端技术：** JS、Vue、CSS3、Uniapp
- **开发工具：** IDEA/Eclipse、Uniapp
- **数据库：** MySQL 5.7/8.0
- **数据库管理工具：** phpstudy/Navicat
- **JDK版本：** jdk1.8
- **Maven：** apache-maven 3.8.1-bin
- **前端环境：** Node.Js 12\14\16

## 核心代码

以下是本项目中的一个核心代码片段，展示了如何实现课程信息的查询：

```java
// CourseMapper.xml
<select id="selectCourseList" parameterType="map" resultType="course">
    SELECT * FROM course
    <where>
        <if test="name != null and name != ''">
            AND name LIKE CONCAT('%', #{name}, '%')
        </if>
        <if test="status != null">
            AND status = #{status}
        </if>
    </where>
    ORDER BY id DESC
</select>
```

## 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

## 项目截图
![封面图片](https://img14.360buyimg.com/ddimg/jfs/t1/287858/27/15293/84822/68c4e118F94561193/784ad4a6cb6dfc5b.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/324047/1/19542/5892/68c4e0f0Fa79ffc14/d1478360b317e526.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/336451/11/10115/52511/68c4e0f0F338f0fa6/fd08952b0c5901f2.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/339082/19/10227/42084/68c4e0f0Fa5162409/0f168e7f74534d9f.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/336769/22/10217/31269/68c4e0f1F67653154/b01464076c6288a7.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/351350/12/2910/27187/68c4e0f1Fe85e4d56/f2caaee2b0c277b5.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/328136/36/19402/24814/68c4e0f2Fa48b5847/320398749cd2cea0.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/325820/36/19668/39044/68c4e0f2F87728659/3cde8daa37cae17d.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/323479/6/19023/30441/68c4e0f2Fe6b840d1/4027553c54d240c2.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/325103/19/19552/49264/68c4e0f2F170ea051/2815430d5f4cd890.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
