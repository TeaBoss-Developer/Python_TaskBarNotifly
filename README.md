# Python_TaskBarNotifly
Send system notifications through the taskbar by calling the Win32 API

使用例子:
alert = Alert.Notifly() #创建Notifly实例(别问为什么是Notifly,一开始打错了())
alert.showMsg("TITLE","MSG")#输出msg
alert.Dispose()#释放实例
