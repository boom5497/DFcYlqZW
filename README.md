# 前言

感谢您选择基于SSM（Spring、Spring MVC、MyBatis）的客户管理系统。本项目致力于为企业提供一套完善的客户管理解决方案，方便企业高效地管理客户信息，提高业务水平。以下是本项目的详细介绍。

## 内容介绍

本项目是一个基于SSM框架的客户管理系统，主要功能包括：客户信息管理、客户关系管理、客户跟进管理、统计分析等。系统采用前后端分离的设计，后端负责数据处理和业务逻辑，前端负责界面展示和用户交互。

系统具有以下特点：

1. 高效性：基于SSM框架，充分利用其优势，提高系统运行效率。
2. 易用性：界面设计简洁，操作便捷，易于上手。
3. 扩展性：模块化设计，方便后期功能扩展和优化。
4. 安全性：采用安全性高的技术，确保系统稳定运行。

## 技术介绍

- 语言：Java
- 使用框架：Spring、Spring MVC、MyBatis
- 前端技术：JS、Vue、CSS3
- 开发工具：IDEA/Eclipse
- 数据库：MySQL 5.7/8.0
- 数据库管理工具：phpstudy/Navicat
- JDK版本：jdk1.8
- Maven：apache-maven 3.8.1-bin
- 前端环境：Node.Js 12\14\16

## 核心代码

以下是客户管理模块的核心代码：

```java
@Service
public class CustomerService {

    @Autowired
    private CustomerMapper customerMapper;

    public List<Customer> findAll() {
        return customerMapper.selectByExample(new CustomerExample());
    }

    public Customer findById(Integer id) {
        return customerMapper.selectByPrimaryKey(id);
    }

    public int addCustomer(Customer customer) {
        return customerMapper.insertSelective(customer);
    }

    public int updateCustomer(Customer customer) {
        return customerMapper.updateByPrimaryKeySelective(customer);
    }

    public int deleteCustomer(Integer id) {
        return customerMapper.deleteByPrimaryKey(id);
    }
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

## 项目截图

![封面图片](https://img12.360buyimg.com/ddimg/jfs/t1/340429/39/9333/128507/68c27ef3Fe655a483/4c80350062801f33.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/328341/40/18780/60850/68c27ecbF1625e08e/7fd8b56d3ee0cc6a.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/339005/40/9537/27465/68c27ecbF2195d9fe/eb52c09885f9888a.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/336617/25/9405/21373/68c27ecbF45a4dc94/680f85ece18f21bd.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/348243/40/2214/49394/68c27eccFf35bd015/d546da8989660bbd.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/340350/36/9540/38821/68c27eccFdeabd963/8f9c5912ae57b254.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/339657/2/9031/29122/68c27eccF40790536/ac957ea23f0ae1ed.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/336906/5/7993/22480/68c27ecdF10038f9e/33b1d9e69006a591.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/328459/15/18862/33330/68c27ecdF5ab28021/0d6d2bcc30477250.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/336064/2/9495/24328/68c27eceFd0f29712/157a3d0cdab1b93b.jpg)
