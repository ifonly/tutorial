### windows 系统创建以点.开头的文件
windows 系统下创建以点.开头的文件可能会提示必须键入文件名，有技巧：
- 创建文件名时后面多输一个点（前提是你的系统在文件夹选项里关闭掉“隐藏已知文件类型的扩展名”），如创建`.gitignore.`
- cmd 命令行下切换到对应目录后运行`type nul > .gitignore`即可
- 使用一些软件进行创建如 Sublime Text