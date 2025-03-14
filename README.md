# SpringBoot 医护人员排班系统 / SpringBoot Medical Staff Scheduling System

![SpringBoot](https://img.shields.io/badge/SpringBoot-2.x-brightgreen)
![MyBatis-Plus](https://img.shields.io/badge/MyBatisPlus-2.3-blue)
![Shiro](https://img.shields.io/badge/Shiro-1.3.2-orange)
![MySQL](https://img.shields.io/badge/MySQL-8.x-4479A1)

# 项目简介  
基于 SpringBoot + MyBatis-Plus + Shiro 的医护人员排班系统，提供科室信息管理、医院信息管理、排班类型管理等功能，适用于医院或医疗机构的高效排班管理。

# 特征介绍  
- ​**权限控制**：集成 Shiro 实现角色/权限动态控制，支持前后端分离鉴权。  
- ​**高效开发**：MyBatis-Plus 零 SQL 实现单表操作，提供 MySQL 数据库支持。  
- ​**多数据源**：支持 MySQL 和 SQL Server 数据库，灵活切换。  
- ​**工具集成**：集成 Hutool 工具库，简化开发流程。  
- ​**接口文档**：支持 Fastjson 进行 JSON 数据处理，符合 RESTful 规范。  
- ​**精简架构**：SpringBoot 脚手架结构，模块化设计便于二次开发。  

# 代码结构 
```
src/
├── main/
│   ├── java/
│   │   ├── com/
│   │   │   ├── annotation/          # 鉴权注解
│   │   │   ├── config/              # 全局配置
│   │   │   ├── controller/          # 接口层
│   │   │   ├── dao/                 # 数据访问层
│   │   │   ├── entity/              # 数据模型
│   │   │   │   ├── model/           # 业务模型
│   │   │   │   ├── view/            # 视图模型
│   │   │   │   ├── vo/              # 值对象
│   │   │   ├── interceptor/         # 请求拦截器
│   │   │   ├── service/             # 服务层
│   │   │   │   ├── impl/            # 服务实现
│   │   │   ├── utils/               # 工具类
│   ├── resources/
│   │   ├── admin/                   # 后台管理前端资源
│   │   ├── front/                   # 前台前端资源
│   │   ├── mapper/                  # MyBatis映射文件
│   │   ├── application.yml          # 主配置
│   │   ├── static/                  # 静态资源
```
# 使用说明  
- 后台地址：http://localhost:8080/springbootjf5zc/admin/dist/index.html  
- 前台地址：http://localhost:8080/springbootjf5zc/front/index.html  
- 管理员账号：abo，密码：abo  
- 推荐使用谷歌浏览器访问  

# 技术文档  
* 核心框架：[Spring Boot](https://spring.io/projects/spring-boot)  
* 持久层框架：[MyBatis-Plus](https://mybatis.plus)  
* 权限认证：[Apache Shiro](https://shiro.apache.org/)  
* 数据库连接池：[MySQL Connector/J](https://dev.mysql.com/doc/connector-j/en/)  
* 工具库：[Hutool](https://www.hutool.cn/)  
* JSON 处理：[Fastjson](https://github.com/alibaba/fastjson)  

# 捐赠  
> 博主将持续更新Java全栈开发项目，包含ssm，springboot，前后端分离系统等项目。  
> 此外如果您够宽裕，请博主喝杯咖啡吧！捐赠将用于服务器维护与开源社区建设，感谢您的认可！  
> 如需更多Java相关项目毕设3000+，sql文件可联系博主v:xq-lucky311  
![输入图片说明](%E7%91%9E%E5%B9%B8%EF%BC%81%E7%91%9E%E5%B9%B8%EF%BC%81.png)
