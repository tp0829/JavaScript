touch a.md  新建文件
mkdir test  新建目录

git init    //仓库初始化
git status  //仓库状态

git add a.md
git rm --cached <file>

git commit -m 'first'
git branch
git branch a
git checkout a
git checkout -b a

git merge a
git merge -d a
git merge -D a

git tag v1.0
git tag
git checkout v1.0

git log //查看日志

push
pull


git remote add origin git@github.com:tp0829/JavaScrite.git
git remote set-url origin git@github.com:tp0829/JavaScript.git
git pull origin master --allow-unrelated-histories 告诉系统我允许合并不相关历史的内容

git config --global alias.lg "log --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit --date=relative"



alias
    - git config --global alias.co checkout  //设置别名 git checkout -> git co
    - git config --global alias.lg "log --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit --date=relative"

~/.gitconfig //配置文件

git diff

git stash
    git stash list
    git stash apply
    
