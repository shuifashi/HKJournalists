# HKJournalists
系统分析与设计-计应16组
> 本项目为数据科学与计算机学院系统分析与设计课程－计应16组 **HKJournalists** 的作业提交平台

> 成员：王铄南，张平淼，王水，吴允劲

##简易git使用指南
###简介
  git是目前一个分布式版本控制系统，详细教程见[廖雪峰git教程](http://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000)或者[Pro Git](https://git-scm.com/book/en/v2)
  
###配置
1. 注册github帐号<https://github.com/>
2. [windows安装](http://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000)git

###简易教程（参考[git使用简易指南](http://www.bootcss.com/p/git-guide/)）
* 创建新仓库
  * 创建新文件夹，打开执行 ``` git init ``` 以创建新的仓库
* 创建本地仓库的克隆版本 ``` git clone /path/to/repository ```


* 添加与提交
  1. 添加到缓存区 ``` git add <filename> ``` 或者 ``` git add * ```
  2. 使用如下命令以实际提交改动 ``` git commit -m "代码提交信息" ```
  3. 推送改动 ``` git push origin master ``` 可以把 master 换成想要推送的任何分支。

  
* 更新与合并
  * 要更新你的本地仓库至最新改动，执行：``` git pull ```
  * 合并其他分支到你的当前分支（例如 master），执行：``` git merge <branch> ```
  * 标记为合并成功：``` git add <filename> ```
 
  
* 标签
  * 可以执行如下命令以创建一个叫做 1.0.0 的标签：```git tag 1.0.0 1b2e1d63ff```
  * 使用如下命令获取提交 ID：```git log```

  
