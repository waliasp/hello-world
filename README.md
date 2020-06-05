# hello-world
#nothing to write
import webbrowser
IEPath = "C:\Program Files\internet explorer\iexplore.exe"
webbrowser.register('IE', None, webbrowser.BackgroundBrowser(IEPath))
webbrowser.open_new_tab('http://www.baidu.com')
