vscode配置git
点击左下角的设置按钮，选择 settings，搜索  git.path ，点击 edit in setting.json 
对 git.path 添加 git.exe 路径：

{

    "git.path": "D:/Git/cmd/git.exe"

}

git 免密码push

git config --global user.name "成长中的小牛"
git config --global user.email "1208984024@qq.com"
在vs中每次更新代码都会要输入账号密码，方便起见，可以配置一下让GIT记住密码账号。
git config --global credential.helper store   //在Git Bash输入这个命令就可以了