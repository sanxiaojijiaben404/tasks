# Git 学习

## 了解

1. Git是分布式版本控制系统，相较于集中式控制系统来说不需要考虑网络问题。多人合作时同步更方便。分支管理能力强大。

2. 工作区域：工作区   暂存区   本地仓库

   文件状态：未跟踪   未修改   已修改    已暂存

## 安装，初始化配置和使用

安装：在官网上下载即可。

初始化配置：

> 在GitBash里面

* 配置名字和邮箱

  ````
  git confing --global user.name "..."
  git confing --global user.email ...........
  ```
  ````

  - 可能会用上的

    ```
     git confing --global creadential.helper store  //保存用户名和密码
     git confing --global --list  //查看Git的配置信息
    ```

* 创建仓库

  ```
  git init 名字 
  ```

  - 可能会用上的

    ```
    git clone 地址  //克隆已有的一个仓库
    ```

* 添加和提交文件

  ```
  git remote add origin 地址  //添加远程仓库地址
  git status  //查看仓库的状态
  git  add .//将所有文件添加到暂存区
  git commit -m "..." //提交已暂存的更改并添加提交信息
  ```

  - 可能会用上的
  
    ```
    git add  *.文件形式  //把以该文件类型结尾的文件全部添加到暂存区里面
    git log  //查看提交记录
    git remote remove origin  //移除当前的错误远程仓库
    git remote -v  //查看当前的远程仓库配置
    ```

* 回退版本

  ![回退]（https://www.picgo.net/image/QQ20251112-195636.UOEZhN）


  

* 查看差异

  ```
  git diff  //工作区vs版本库
  git diff HEAD  //工作区+暂存区vs本地仓库
  git diff --cached 或者git diff --staged  //暂存区vs本地仓库
  git diff <commit_hash><commit_hash>或者git diff HEAD~HEAD  //比较提交之间的差异
  git diff <branch_name><branch_name>  比较分支之间的差异
  ```

  * 可能会用上的

    ```
    del 文件名  //删除文件
    ```

​           ![QQ20251112-195636](D:\install_file\QQ\QQ20251112-195636.png)     

> 这个听了几遍也没完全理解

* SSH的配置

> 这个有点复杂，直接上图片

![Screenshot_2025_1114_122924](D:\install_file\QQ\Screenshot_2025_1114_122924.jpg)

* ```
  git clone repo-address//克隆仓库
  git push <remote><branch>//推送更新内容
  git pull <remote>//拉取更新内容
  ```

* 分支

  ```
  git branch 名字 //创建分支
  git branch //查看分支列表
  git swich 名字 //切换分支
  git merge 名字 //合并分支
  git branch -d 名字 //删除已被合并的分支
  git branch -D 名字 //强制删除未被合并的分支
  ```

  * 分支冲突

    ![QQ20251114-130324](D:\install_file\QQ\QQ20251114-130324.png)

  

参考：

[bilibili【GeekHour】一小时Git教程]([17.解决合并冲突_哔哩哔哩_bilibili](https://www.bilibili.com/video/BV1HM411377j?spm_id_from=333.788.player.switch&vd_source=2e665bb499620ff7c35d9d551c1ca19e&p=17))

[deepseek]([DeepSeek | 深度求索](https://www.deepseek.com/))

[廖雪峰的 Git 教程]([简介 - Git教程 - 廖雪峰的官方网站](https://liaoxuefeng.com/books/git/introduction/index.html))

[Google]([Google](https://www.google.com.hk/))


