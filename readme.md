# oragnizaiton Demo

![git之多人协同开发](https://blog.csdn.net/menergy/article/details/123600990)

- 当执行 `git checkout .`或者 `git checkout -- <file>` 命令时，会用暂存区全部或指定的文件替换工作区的文件。这个操作很危险，会清除工作区中未添加到暂存区中的改动
- 当执行 `git checkout HEAD .`或者 `git checkout HEAD <file>` 命令时，会用 HEAD 指向的 master 分支中的全部或者部分文件替换暂存区和以及工作区中的文件。这个命令也是极具危险性的，因为不但会清除工作区中未提交的改动，也会清除暂存区中未提交的改动。
- 当执行`git reset HEAD`命令时，暂存区的目录树会被重写，被 master 分支指向的目录树所替换，但是工作区不受影响。
- 当执行`git rm --cached <file>` 命令时，会直接从暂存区删除文件，工作区则不做出改变。
  -dev
