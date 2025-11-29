1、以后可以考虑再多分几个vault（多建几个git仓库）
2、移动端每次使用前pull一遍，养成好习惯
3、要修改还是尽量电脑编辑移动端只读，防止移动端忘记push导致冲突
### 平板：
cd "/storage/emulated/0/Obsidian_AllPlatform"
### 手机：
cd "/storage/emulated/0/Obsidian_AllPlatform/OSDN_BackUp"
### 拉取：
git pull origin master


# 平板端（使用termux）
username：Luyuting2049
token（password）：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
cd "/storage/emulated/0/Obsidian_AllPlatform"
	进入到vault所在目录

## 将内容推送至远程仓库：
git status
	查看仓库状态，是否有文件被修改
git add .
	把标红的添加到暂存区
git commit -m "相关提交信息"
	提交到本地git仓库
git push origin master
	把内容推送到远程仓库
	冲突什么的太麻烦了，直接输入以下这行吧：
	git push --force origin master

## 从远程仓库拉取内容
git pull origin master
	注意这里，一开始半天没弄起来是因为master写成main了。现在使用的这个分支是master

# 手机端（还是termux）
操作步骤完全相同，不过地址是
cd "/storage/emulated/0/Obsidian_AllPlatform/OSDN_BackUp"
（在Obsidian_AllPlatform下多了个文件夹）

P.S.新设备会有一些额外操作，比如授予权限，设置全局用户名邮箱，设置安全权限，还有记录用户名token以免每次输入。遇到了问问gpt好了。。

