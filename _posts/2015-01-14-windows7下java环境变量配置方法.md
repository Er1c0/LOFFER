---
title: windows7下java环境变量配置方法
date: 2015-01-14 08:44:41
tags: [Java, 环境变量, burp]
categories: [Text]
---

<p>java需要自己动手配置环境变量，下面我给介绍一下我本人配置的方法&nbsp;，希望对大家有帮助！<br /></p> 
<p>原料：已装好Java的JDK,哪里下的已经忘了（囧）</p> 
<p>1.用鼠标右击“我的电脑”-&gt;属性&nbsp;&nbsp;&nbsp;&nbsp;</p> 
<p>选择左边导航的“高级系统设置”选项，</p> 
<p>选择右下角的“环境变量”选项</p> 
<p>
![](https://imglf2.ph.126.net/VMCZis58bekNcPHUGDX4xQ==/6619299692747291798.png)
<br />
![](https://imglf0.ph.126.net/T_lVQ8ts0RSZi5WW7xSrAQ==/6630469631372952687.png)
<br />
![](https://imglf0.ph.126.net/2psF3nv-oxWVQqJHm24pvA==/6630713722954319106.png)
<br />
![](https://imglf1.ph.126.net/FA5u4VC5WQQpvh3fRoLZrg==/2440669523075748526.png)
<br /><br /></p> 
<p>2.进行win7下Java环境变量配置</p> 
<p>在&quot;系统变量&quot;下进行如下配置：</p> 
<p>(1)新建-&gt;变量名：JAVA_HOME变量值：D:\Java\jdk1.6.0_12(这只是我的JDK安装路径)</p> 
<p>(2)编辑-&gt;变量名：Path在变量值的最前面加上：%JAVA_HOME%\bin;%JAVA_HOME%\jre\bin</p> 
<p>(3)新建-&gt;变量名：CLASSPATH变量值：.;%JAVA_HOME%\lib;%JAVA_HOME%\lib\dt.jar;%JAVA_HOME%\lib\tools.jar</p> 
<p>(4)编辑-&gt;变量名：JAVA_HOME,变量值：D:\Java\jdk1.6.0_10</p> 
<p>&nbsp;注意：当设置的变量在末尾时，不要加上“；”。</p> 
<p><br /></p> 
<p>3.测试下环境变量是否设置成功<br />&nbsp;&nbsp;在左下角的搜索框中键入<br />&nbsp;&nbsp; cmd<br />&nbsp;&nbsp;&nbsp;或者按下“WIN+R”键,“WIN”键就是&quot;CTRL&quot;和“ALT””中间那个微软图标那个键；<br />&nbsp;&nbsp;分别输入java，javac，java -version&nbsp;命令<br /></p> 
<p>
![](https://imglf0.ph.126.net/8RwWwhUzuMmxmJPjulw7rQ==/6630502616721785907.png)
<br /><br /></p> 
<p>4.你的Java环境变量配置成功！<br /></p> 
<p><br /></p> 
<p>5.若出现<br /><br />&nbsp;&nbsp;&nbsp;'javac'&nbsp;不是内部或外部命令，也不是可运行的程序<br />&nbsp;&nbsp;&nbsp;或批处理文件。<br /><br />&nbsp;&nbsp;&nbsp;说明此次Java环境变量配置出错了，仔细检查下吧！</p> 
<p><br /></p> 
<p>http://jingyan.baidu.com/article/925f8cb836b26ac0dde0569e.html<br /></p> 
<p><br /></p> 
<p><br /></p> 
<p><br /></p> 
<p><br /></p> 
<p><br /></p> 
<p><br /></p> 
<p><br /></p> 
<p><br /></p> 
<p><br /></p> 
<p><br /></p> 
<p><br /></p> 
<p><br /></p> 
<p><br /></p> 
<p><br /></p>