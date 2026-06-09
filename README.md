# lowcarbon
# 碳减减 - 全栈低碳社交应用
> 一款倡导低碳生活的移动应用 + 管理后台，采用鸿蒙 + Spring Boot 架构，前后端分离。
## 📁 子仓库
| 模块 | 技术栈 | 仓库地址 |
|------|--------|----------|
| 移动端前端（鸿蒙） | ArkUI, ArkTS | [👉 链接](https://github.com/Nian1214/lowcarbon-mobile-frontend) |
| 移动端后端 | Spring Boot, MyBatis-Plus, Spring Cloud | [👉 链接](https://github.com/Nian1214/lowcarbon-mobile-backend) |
| 管理端前端 | Vue3, Element Plus, Axios | [👉 链接](https://github.com/Nian1214/lowcarbon-admin-frontend) |
| 管理端后端 | Spring Boot, MyBatis-Plus, JWT | [👉 链接](https://github.com/Nian1214/lowcarbon-admin-backend) |

## 🎯 核心功能

- **移动端**：用户登录/注册、低碳行为记录（出行/居家）、碳积分计算、排行榜、碳友圈（动态发布/点赞/评论）、商城兑换、个人碳账户、勋章系统。
- **管理端**：动态审核、互动管控（评论删除）、违规记录追溯、商品管理、订单处理、用户数据概览。

## 🛠 技术架构

- **移动端**：HarmonyOS + ArkUI 声明式开发，通过 Axios 调用后端 API。
- **管理端**：Vue3 + Element Plus，前后端分离，响应式布局。
- **后端**：Spring Boot + MyBatis-Plus，微服务模块（用户服务、行为服务、社区服务、商城服务），OpenFeign 远程调用，Gateway 网关，JWT 鉴权。
- **数据库**：MySQL 存储业务数据。
- **测试**：Apifox 接口测试 + 功能测试。

## 👤 个人贡献

- 作为项目组长，完成需求分析、系统设计、任务分配及核心代码实现。
- 负责移动端登录/注册、社区板块（动态展示/发布/点赞、碳友圈）和管理端动态审核/互动管控/违规查询。
- 设计 13 张数据库表，编写关键业务 API，并使用 Apifox 完成接口测试。
- 编写 10+ 页原型图、绘制时序图与用例图，输出完整实训报告。
