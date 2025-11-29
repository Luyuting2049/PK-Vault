# 平板端（使用termux）
username：Luyuting2049
token（password）：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
cd "/storage/emulated/0/Obsidian_AllPlatform/OSDN_BackUp"
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

