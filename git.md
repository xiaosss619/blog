# 删除本地分支
git branch -d localBranchName

# 删除远程分支
git push origin --delete remoteBranchName

# 创建新分支
git checkout -b remoteBranchName

# 本地分支推向远程
git push -u origin remoteBranchName

# 同步本地去远程
rsync -avz ./dist/* rocky@43.198.7.164:/home/rocky/sg/html/merchant