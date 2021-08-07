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


git pull更新本地的（从远程仓库获取）

git通过vscode操作需要保持本地仓库和远程仓库名字一致


ubuntu 下测试 
配置也是和win10一样，不过不用添加环境变量

再次测试推送

1、在需要创建 .gitignore 文件的文件夹, 右键选择Git Bash 进入命令行，进入项目所在目录。

2、输入 touch .gitignore ，生成“.gitignore”文件。

3、在”.gitignore” 文件里输入你要忽略的文件夹及其文件就可以了。（注意格式）

我的 .gitignore：

.deploy_git/
node_modules/
public/