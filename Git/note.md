# 怎样使用 GitHub[(https://www.zhihu.com/question/20070065/answer/16021641)]

# 常用语句
* 关联远程库
```
$ git remote add origin git@github.com:Saicoding/note.git
```
* 推送
```
$ git push -u origin master(第一次)
$ git push origin master
```
* 创建分支 
```
$ git checkout -b dev
```
* 删除远程分支
```
$ git push origin : dev
```
* 库合并
```
$ git pull --rebase origin master
```
* 克隆库
```
$ git clone https://github.com/angular/quickstart.git yourProjectDir
```
