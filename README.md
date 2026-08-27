# 前言

您好！这是一个基于Spring Boot的养老院管理系统毕业设计分享项目。本项目以实用性为出发点，致力于为养老院提供一套全面、高效、易用的管理系统。以下是对本项目的详细介绍。

## 内容介绍

本项目主要包括以下功能模块：老人信息管理、员工信息管理、床位管理、餐饮管理、活动管理等。通过这些模块，可以实现对养老院各项业务的高效管理。此外，本项目还提供了完善的用户权限控制，确保系统安全可靠。

以下是项目的主要特点：

1. 界面简洁友好，易于操作。
2. 采用前后端分离的设计，便于维护与扩展。
3. 代码结构清晰，方便学习与二次开发。

## 技术介绍

本项目采用以下技术栈：

- 语言：Java
- 使用框架：Spring Boot
- 前端技术：JS、Vue、CSS3
- 开发工具：IDEA/Eclipse
- 数据库：MySQL 5.7/8.0
- 数据库管理工具：phpstudy/Navicat
- JDK版本：jdk1.8
- Maven: apache-maven 3.8.1-bin
- 前端环境：Node.Js 12\14\16

## 核心代码

以下是一段关于老人信息管理的核心代码：

```java
@RestController
@RequestMapping("/oldPeople")
public class OldPeopleController {

    @Autowired
    private OldPeopleService oldPeopleService;

    @GetMapping("/list")
    public ResponseEntity<List<OldPeople>> list() {
        List<OldPeople> list = oldPeopleService.list();
        return ResponseEntity.ok(list);
    }

    @PostMapping("/add")
    public ResponseEntity<Void> add(@RequestBody OldPeople oldPeople) {
        oldPeopleService.add(oldPeople);
        return ResponseEntity.ok().build();
    }

    // ...其他代码
}
```

## 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

# 项目截图

![封面图片](https://img11.360buyimg.com/ddimg/jfs/t1/316391/15/26207/125454/689ebf4cFf760afd0/2220939e970f5f5e.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/295836/8/18833/21651/689ebf2aFd7a9f09a/654edb0401c5a5b3.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/307002/6/26590/69850/689ebf2bF24ac0d78/64dca98ed1ec4236.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/318544/26/21045/82450/689ebf2dFee4c6252/7b78d6aa162f53a7.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/311082/30/26605/27340/689ebf2dF2a58d7c3/1da092ef9e721fae.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/327568/29/4751/19374/689ebf2dF3c9dc1b8/3af2920af466d566.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/315401/12/26580/19089/689ebf2eF27388064/b3ff96dbf5a8fd13.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/309845/26/26556/26107/689ebf2fFfd840fd1/acb81a877f25ab30.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/294520/34/25808/28462/689ebf30F4453eaef/50b8e5de604d2eb7.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/314902/15/26122/20353/689ebf30F40ae165d/e8de6a91f6d52ef1.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
