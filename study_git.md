1.本来master中有一个x.txt文件。
	i。建立一个分支a，后修改x.txt在第一行加一个7
	在master分支中修改x.txt在第二行加一个2

然后用merge合并，<font color='red'>（合并时要明白1）合并一般是向master中合并2）在两个分支中位于其中一个时，merge命令后跟另外一个3）如果能成功合并，也只是其中被合并的分支改变，另一个并没有变）</font>可以合并

	ii。建立一个分支a，后修改x.txt在第一行加一个7
	在master分支中修改x.txt在第一行同一位置加一个2

此时不能合并，要人为修改，就是把另一个的部分人为录入一遍或者变成一个完全新的东西。
2.git merge -m "merge reason" 分支名
3.Git:更新被拒绝，因为您当前分之的最新跟新落后于其对应的远程分支的解决方法？
linux:https://blog.csdn.net/u012300744/article/details/80264807
windows:https://www.cnblogs.com/dotnet261010/p/10848386.html
