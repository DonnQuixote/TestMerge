# TestMerge
测试合并分支

假设想要把master分支中的东西合并到main分支上面去：
1.本地拉取最新更改
git pull origin main
2.切换到要合并的分支
git checkout main
3.将目标分支合并到当前分支
git merge maste --allow-unrelated-histories
4.手动解决任何冲突。打开包含冲突的文件，并查找标记为冲突的部分。编辑文件以解决冲突，并删除Git添加的冲突标记。
5.将合并后的分支推送到远程存储库：
git push origin main

