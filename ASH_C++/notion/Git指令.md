将所有文件放入暂存区：    git add .

提交：   git commit 

提交（带备注）：  git commit -m "备注内容"

查看提交代码节点： git log

查看提交代码修改文件内容：git log -- stat

查看单次修改内容：git diff  f2e2d2192b0795b519d6a9cc6f162475cb705149            编码部分填写commit id

代码回退： git reset --hard  f2e2d2192b0795b519d6a9cc6f162475cb705149        这两个都可以
				  git checkout f2e2d2192b0795b519d6a9cc6f162475cb705149 

查看分支：git branch

创建分支： git checkout - b aaa                                                                       aaa是分支名

切换分支：git checkout  aaa

合并分支：git checkout  master
				 git merge aaa

克隆仓库： git clone https://github.com/ansenhao/Cpp_Note.git