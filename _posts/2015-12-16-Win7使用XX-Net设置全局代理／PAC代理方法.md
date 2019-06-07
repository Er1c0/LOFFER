---
title: Win7使用XX-Net设置全局代理/PAC代理方法
date: 2015-12-16 14:36:50
tags: []
categories: [Text]
---

<p><strong>XX-Net项目主页&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</strong><a rel="nofollow" href="https://github.com/XX-net/XX-Net" target="_blank"  >GitHub@XX-Net</a></p> 
<p><br /></p> 
<ul> 
 <li><p><strong>PAC代理</strong>：通常推荐勾选这个选项。单击后设定代理为自动切换脚本<a rel="nofollow" href="http://127.0.0.1:8086/proxy.pac" target="_blank"  >http://127.0.0.1:8086/proxy.pac</a>。设置后，所有支持的程序都默认通过XX-Net上网，由XX-Net的脚本自动判断，国内网站直接连接，被屏蔽的网站走代理。</p></li> 
</ul> 
<p><br /></p> 
<p><br /></p> 
<ol> 
 <li><p>设置Chrome为默认浏览器</p></li> 
 <li><p>打开XX-Net软件，Chrome将打开http://127.0.0.1:8085/页面</p></li> 
 <li><p>选择Chrome代理切换插件的 GoAgent PAC 选项</p><p>
![](https://imglf2.ph.126.net/YdbLU-AXBIJBVm0v04gvAg==/6631253583166641482.png)
<br /><br /></p></li> 
 <li><p>打开Interet属性-局域网设置-自动配置-使用自动配置脚本&nbsp; http://127.0.0.1:8086/proxy.pac</p><p>
![](https://imglf1.ph.126.net/ddAIwuMpN6Z5aL--f8ahUg==/6631338245561976568.png)
<br /><br /></p></li> 
</ol> 
<p>&nbsp;&nbsp;&nbsp; 5.设置-自动配置-使用自动配置脚本&nbsp; http://127.0.0.1:8086/proxy.pac </p> 
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
![](https://imglf2.ph.126.net/lb4E1q1WCJhrrAkX5LgJRg==/6631425106980588437.png)
</p> 
<p><br /></p> 
<ul> 
 <li><p><strong>全局通过GAE_proxy代理</strong>：单击后设置系统全局代理为&nbsp;网址127.0.0.1 端口8087，所有支持的程序都默认通过XX-Net上网，经由GAE服务器代理。上国内的网站速度较慢。关闭XX-Net后可能无法正常上网。</p></li> 
</ul> 
<ol> 
 <li><p>设置Chrome为默认浏览器</p><p>打开XX-Net软件，Chrome将打开http://127.0.0.1:8085/页面</p><p>选择Chrome代理切换插件的 GoAgent 选项</p><p>
![](https://imglf2.ph.126.net/f7AJ5ySrpK0PIXbhWYmDlQ==/6631358036771298848.png)
<br /><br /></p></li> 
 <li><p>打开Interet属性-局域网设置-代理服务器-地址填入 127.0.0.1 ，端口填入 8087 。并勾选“跳过本地地址的代理服务器”。<br /></p></li> 
 <li><p>设置-代理服务器-地址填入 127.0.0.1 ，端口填入 8087 。并勾选“跳过本地地址的代理服务器”</p></li> 
 <li><p>完成</p></li> 
</ol> 
<p><br /></p> 
<p><br /></p> 
<p><br /></p> 
<p><br /></p> 
<p><br /></p>