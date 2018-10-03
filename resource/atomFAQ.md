## atom找不到GitHubDesktop
安转atom的时候在（C:\Users\Administrator\AppData\Local\atom）下会自动生成一个bin目录，
需要在系统环境变量下配置才能直接使用.所以，方法就是：先在atom的安装目录下新建bin文件夹，
并在dos环境下，在路径C:\Users\Administrator\AppData\Local\atom下输入命令 atom –squirrel-updated，
这样就会看到bin目录里有一些文件，重新打开GitHubDesktop，这样就可以连接atom了
