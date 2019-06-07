---
title: Sublime Text 2 安装Package Control
date: 2015-12-16 11:47:00
tags: []
categories: [Text]
---

<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;由于Package Control安装后经常性消失，原因未知，所以每次都需要重新安装。。</p> 
<p>安装前确保能电脑能访问&nbsp;<a rel="nofollow" href="http://wbond.net/" target="_blank"  >http://wbond.net/</a>&nbsp;，因为官网被宕了，强行安装会出错。</p> 
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Sublime Text 2-控制台-&gt;输入以下内容:<br /></p> 
<p><br /></p> 
<p>import urllib2,os; pf='Package Control.sublime-package'; ipp=sublime.installed_packages_path(); os.makedirs(ipp) if not os.path.exists(ipp) else None; urllib2.install_opener(urllib2.build_opener(urllib2.ProxyHandler())); open(os.path.join(ipp,pf),'wb').write(urllib2.urlopen('http://sublime.wbond.net/'+pf.replace('&nbsp;','%20')).read()); print('Please restart Sublime Text to finish installation')<br /></p> 
<p><br /></p> 
<p>安装完成之后，重启 Sublime Text 2 ，使用ctrl+shift+p快捷键进入命令模式，输入Install Package即可安装插件。</p> 
<p><br /></p>