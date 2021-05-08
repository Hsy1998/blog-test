# Hello Guys
## 内容摘自饥人谷，第一次博客记录
- git push 和 git pull 的区别
~~~~
git push 使用本地的对应分支来更新对应的远程分支
git pull 从远程获取最新版本并merge到本地
~~~~

- 配置git快捷命令
~~~~
touch ~/.bashrc
echo 'alias ga="git add"'>> ~/.bashrc
echo 'alias gc="git commit -v"'>> ~/.bashrc
echo 'alias gl="git pull"'>> ~/.bashrc
echo 'alias gp="git push"'>> ~/.bashrc
echo 'alias gco="git checkout"'>> ~/.bashrc
echo 'alias gst="git status -sb"'>> ~/.bashrc
~~~~
最后 code ~/.bashrc 在文件最后加上
~~~~
alias glog="git log --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit -- | less"
~~~~
