---
title: 基于hexo搭建个人博客
date: 2020-11-25 13:27:31
tags: 经验分享
---

# 安装hexo

查阅hexo官方文档

https://hexo.io/zh-cn/docs/

# 如何使用

## 新建日志

![](1.png)

输入hexo n "日志名"

## 编辑日志

注意使用.md格式编辑

![image-20201125151359131](image-20201125151359131.png)

## **清理&生成hexo博客**

![image-20201125151633025](image-20201125151633025.png)

**hexo clean** 清理缓存

**hexo g** 生成博客

## 创建github仓库

仓库名为：**myicnm**.github.io

**注意事项：仓库名格式必须为 用户名.github.io**

### **安装git部署插件**

![image-20201125152719200](image-20201125152719200.png)

在blog根目录输入 npm install --save hexo-deplover-git

### 配置config

![image-20201125152939254](image-20201125152939254.png)

### 部署hexo到github.io

![image-20201125153104735](image-20201125153104735.png)

输入**hexo d**部署到远端

输入github账号密码登录，完成验证

## 访问BLOG

https://mayicnm.github.io/

![image-20201125153243383](image-20201125153243383.png)

第一步大功告成！

## 注意事项

### 推送远端后404

注意在推送前需要将git账号切换成github的账号！否则将404

查看用户名:git config user.name

切换用户:git config --global user.name "xxx"

切换邮箱:git config --global user.email "xxx"。



