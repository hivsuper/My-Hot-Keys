# 快捷键以及各类使用记录
IDE混用之后快捷键也记得乱七八糟，故导出或者记录各种配置，以备不时之需。  
## Eclipse-jee-oxygen-R-win32-x86_64
+	Keymap  
	<table>
		<tr><td>跳转到文件</td><td>Ctrl+Shift+R</td></tr>
		<tr><td>查找类</td><td>Ctrl+Shift+T</td></tr>
		<tr><td>全局查找/替换</td><td>Ctrl+H</td></tr>
		<tr><td>打开实现类</td><td>Ctrl+T</td></tr>
		<tr><td>重命名</td><td>Shift+Alt+R</td></tr>
		<tr><td>代码块折叠</td><td>Ctrl+Shift+NumPad /</td></tr>
		<tr><td>代码块展开</td><td>Ctrl+Shift+NumPad *</td></tr>
		<tr><td>Backward History</td><td>Alt+←</td></tr>
		<tr><td>Forward History</td><td>Alt+→</td></tr>
		<tr><td>Organize Imports</td><td>Ctrl+Shift+O</td></tr>
		<tr><td>Content Assist</td><td>Alt+/</td></tr>
		<tr><td>Run</td><td>Ctrl+F11</td></tr>
		<tr><td>Debug</td><td>F11</td></tr>
		<tr><td>代码上移/下移</td><td>Alt+↑/Alt+↓</td></tr>
		<tr><td>复制选中代码</td><td>Ctrl+Alt+↓</td></tr>
		<tr><td>Debug跳入方法/向下逐行调试/跳出方法/直接跳转到下一个断点</td><td>F5/F6/F7/F8</td></tr>
		<tr><td>调出右健菜单</td><td>Ctrl+Alt+S</td></tr>
	</table>

## IntelliJ IDEA Community Edition 2017.2.5
+	Information:java: javacTask: 源发行版 1.8 需要目标发行版 1.8  
	http://www.cnblogs.com/cxj20160928/p/5954336.html  
+	How to create Java files?  
	http://www.cnblogs.com/SitongLiu/p/6554006.html  
+	Keymap  
	<table>
		<tr><td>跳转到文件</td><td>Ctrl+Shift+R</td></tr>
		<tr><td>查找类</td><td>Ctrl+Shift+T</td></tr>
		<tr><td>检索所有文件</td><td>Double Shift</td></tr>
		<tr><td>全局查找</td><td>Ctrl+H</td></tr>
		<tr><td>全局替换</td><td>Alt+H</td></tr>
		<tr><td>打开实现类</td><td>Ctrl+T</td></tr>
		<tr><td>重命名</td><td>Shift+Alt+R</td></tr>
		<tr><td>代码块折叠</td><td>Ctrl+Shift+NumPad /</td></tr>
		<tr><td>代码块展开</td><td>Ctrl+NumPad *</td></tr>
		<tr><td>Backward History</td><td>Alt+←</td></tr>
		<tr><td>Forward History</td><td>Alt+→</td></tr>
		<tr><td>Open Recent Files</td><td>Ctrl+E</td></tr>
		<tr><td>Organize Imports</td><td>Ctrl+Shift+O</td></tr>
		<tr><td>Completion</td><td>Alt+/</td></tr>
		<tr><td>Cyclic Expand Word</td><td>Alt+.</td></tr>
		<tr><td>Cyclic Expand word(Backward)</td><td>Alt+Shift+.</td></tr>
		<tr><td>Cyclic Expand word(Backward)</td><td>Alt+Shift+.</td></tr>
		<tr><td>Run</td><td>Ctrl+Shift+F10</td></tr>
		<tr><td>Debug</td><td>Ctrl+Shift+F9</td></tr>
		<tr><td>显示/隐藏Project视图</td><td>Alt+1</td></tr>
		<tr><td>显示/隐藏Run控制台</td><td>Alt+4</td></tr>
		<tr><td>显示/隐藏Debug控制台</td><td>Alt+5</td></tr>
		<tr><td>关闭当前窗口</td><td>Ctrl+F4</td></tr>
		<tr><td>代码上移/下移</td><td>Alt+↑/Alt+↓</td></tr>
		<tr><td>复制选中代码</td><td>Ctrl+Alt+↓</td></tr>
		<tr><td>Debug跳入方法/向下逐行调试/跳出方法/直接跳转到下一个断点</td><td>F5/F6/F7/F8</td></tr>
		<tr><td>调出右健菜单</td><td>Ctrl+Alt+S</td></tr>
		<tr><td>调用Generate窗口</td><td>Alt+Insert</td></tr>
	</table> 
+	How to open Maven Projects view?  
	View->Tool Windows->Maven projects  

## Windows 10
+	Hot Keys
	<table>
		<tr><td>打开设置</td><td>Windows+X</td></tr>
		<tr><td>打开运行</td><td>Windows+R</td></tr>
	</table>

## MySQL
+	How to grant remote access of database jiaoyan to dev?
```	
	GRANT ALL PRIVILEGES ON jiaoyan.* TO dev@'%' IDENTIFIED BY 'dev';  
	FLUSH PRIVILEGES;
```  
+	How to locate data files?
```	
	show global variables like "%datadir%";
```	

## Git
+	How to revert all changes on local branch?  
```	
	git reset --hard HEAD~1
```
+	How to set local branch's head to some commit?
```
	git reset --hard commit_id
```
+	"Can't start git:git.exe" when SourceTree 2.3.1.0 works with IntelliJ IDEA?
	* https://stackoverflow.com/questions/33860054/cant-start-git-git-exe-warning-pop-up-message-in-pycharm-5-0-2 *  
	Correct path of git.exe should fix this issue. eg. C:\Users\{User}\AppData\Local\Atlassian\SourceTree\git_local\bin\git.exe