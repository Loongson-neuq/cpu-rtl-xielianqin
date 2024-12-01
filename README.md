***本仓库会不定期更新, 请大家及时 pull 以保持最新代码***

# 这是自己CPU的代码仓库
由于采用增量开发, 即在之前的基础上进行开发, 所以以后将采取在同一个仓库提交代码的方式, 方便大家的代码管理.

请大家在commit信息中写明提交的内容, 以便于查看代码的变化, 以及我们判断是否完成了作业.

# 2024.12.1更新
1. 请完成lab6的调试改错, 在debug过程中学习提供核的数据通路, 测试平台的使用方法和调试技巧.
2. 尝试根据之前所学的流水线切分方法将单周期核切分成五级流水线, 尝试完成lab7.



# myCPU链接至远程仓库方法
1. 在本地目录的 myCPU 中打开 git bash

2. 初始化本地仓库
```shell
git init
```

3. 将本地仓库与远程仓库关联
```shell
git remote add origin git@github.com:yourName/repositoryname.git  (建议)

git remote add origin https://github.com/yourName/repositoryname.git
```
yourName是用户名，repositoryname是仓库名字, **你自己的仓库地址**

4. 将远程仓库的文件使用变基方式拉到本地
```shell
git pull --rebase origin master
```

5. 继续开发代码, 提交推送和之前一样