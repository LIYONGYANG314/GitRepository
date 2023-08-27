# Git Learning

## 本地初始化

本地建立`git`仓：

```bash
liyongyang@liyongyangdeMacBook-Pro GitLearning % cd GitRepository 
liyongyang@liyongyangdeMacBook-Pro GitRepository % git init
Initialized empty Git repository in /Users/liyongyang/Documents/GitLearning/GitRepository/.git/
```

为设备配置`UserName`以及`email`以唯一标识一台设备的信息：

```bash
liyongyang@liyongyangdeMacBook-Pro GitRepository % git config --global user.name "LIYONGYANG"   
liyongyang@liyongyangdeMacBook-Pro GitRepository % git config --global user.email "2803116880@qq.com"
```



至此，本地就算建好一个`Git`仓库了。

## GitHub远程仓库

首先需要到`GitHub`上，新建一个仓库，然后将此仓库克隆到本地：

```bash
liyongyang@liyongyangdeMacBook-Pro GitLearning % git clone https://github.com/LIYONGYANG314/GitRepository.git
Cloning into 'GitRepository'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (3/3), done.
```

之后就可以用此仓库上传东西了。

