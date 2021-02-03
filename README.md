# github-actions-demo

## 前言

Github Ac­tions 是 GitHub 推出的持续集成 (Con­tin­u­ous in­te­gra­tion，简称 CI) 服务，它提供了配置非常不错的虚拟服务器环境，基于它可以进行构建、测试、打包、部署项目。简单来讲就是将软件开发中的一些流程交给云服务器自动化处理，比方说开发者把代码 push 到 GitHub 后它会自动测试、编译、发布。有了持续集成服务开发者就可以专心于写代码，其它乱七八糟的事情就不用管了，这样可以大大提高开发效率。本篇文章将介绍 GitHub Ac­tions 的基本使用方法。

## 基础概念

* workflow （工作流程）：持续集成一次运行的过程。
* job （任务）：一个 workflow 由一个或多个 job 构成，含义是一次持续集成的运行，可以完成多个任务。
* step（步骤）：每个 job 由多个 step 构成，一步步完成。
* action （动作）：每个 step 可以依次执行一个或多个命令（action）。
