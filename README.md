# hello-world
#nothing to write
#waliasp here, first step in python
========================

import webbrowser
IEPath = "C:\Program Files\internet explorer\iexplore.exe"
webbrowser.register('IE', None, webbrowser.BackgroundBrowser(IEPath))
webbrowser.get('IE').open('http://www.baidu.com', new=1,autoraise=True)

