# BlockWin10AU
* 右键以管理员身份运行 “Block WAU.bat” 即可禁止Windows10的自动更新功能
* 由于涉及到系统关键位置，记得先关闭类似360的安全软件

建议您可以尝试以管理员身份打开命令提示符，在命令行窗口中输入
sc stop wuauserv

sc config wuauserv start = disabled
