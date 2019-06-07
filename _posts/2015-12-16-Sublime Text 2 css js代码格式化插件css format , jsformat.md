---
title: Sublime Text 2 css js代码格式化插件css format , jsformat
date: 2015-12-16 12:27:46
tags: []
categories: [Text]
---

<p>由于HTML-CSS-JS Prettify插件有关nodejs路径问题导致插件不能用，所以转入css format , jsformat，安装前确保已上网及已安装Package Control &nbsp;（&nbsp;<a href="http://er1c0.lofter.com/post/1cfc8374_94998a5" target="_blank"  >Package Control 安装教程</a>）。</p> 
<ol> 
 <li><p><a rel="nofollow" href="http://mutian.wang/tech/1508" target="_blank"  >CSS Format 介绍</a></p><p><br /></p></li> 
</ol> 
<p>&nbsp;保存时自动格式化</p> 
<p>打开 Preferences &gt; Package Settings &gt; CSS Format &gt; Settings – Default，将 Settings – Default 里的内容复制到 Preferences &gt; Package Settings &gt; CSS Format &gt; Settings – User 中，然后将 format_on_save 的值改为 true。</p> 
<p>注意：你需要始终编辑 Settings – User 文件，不要编辑 Settings – Default 文件，否则下次插件更新会覆盖你的设置。</p> 
<p>&nbsp;&nbsp;<strong>&nbsp;&nbsp;</strong>2. jsformat（<a rel="nofollow" href="http://wanghaiyang.me/read.php?key=467" target="_blank"  >配置</a>）<br /></p> 
<p>默认配置格式化后间隙太大，需要将配置文件（ Preferences &gt; Package Settings &gt; jsFormat &gt; Settings – User 中）新增以下内容&nbsp;</p> 
<p>{</p> 
<p>&nbsp;&nbsp;&nbsp;&nbsp;// exposed jsbeautifier options</p> 
<p>&nbsp;&nbsp;&nbsp;&nbsp;&quot;translate_tabs_to_spaces&quot;: true,</p> 
<p>&nbsp;&nbsp;&nbsp;&nbsp;&quot;tab_size&quot;: 4,</p> 
<p>&nbsp;&nbsp;&nbsp;&nbsp;&quot;indent_with_tabs&quot;: false,</p> 
<p>&nbsp;&nbsp;&nbsp;&nbsp;&quot;preserve_newlines&quot;: true,</p> 
<p>&nbsp;&nbsp;&nbsp;&nbsp;&quot;max_preserve_newlines&quot;: 4,</p> 
<p>&nbsp;&nbsp;&nbsp;&nbsp;&quot;space_in_paren&quot;: false,</p> 
<p>&nbsp;&nbsp;&nbsp;&nbsp;&quot;jslint_happy&quot;: true,</p> 
<p>&nbsp;&nbsp;&nbsp;&nbsp;&quot;brace_style&quot;:&nbsp;&quot;end-expand&quot;,</p> 
<p>&nbsp;&nbsp;&nbsp;&nbsp;&quot;keep_array_indentation&quot;: false,</p> 
<p>&nbsp;&nbsp;&nbsp;&nbsp;&quot;keep_function_indentation&quot;: false,</p> 
<p>&nbsp;&nbsp;&nbsp;&nbsp;&quot;eval_code&quot;: false,</p> 
<p>&nbsp;&nbsp;&nbsp;&nbsp;&quot;unescape_strings&quot;: false,</p> 
<p>&nbsp;&nbsp;&nbsp;&nbsp;&quot;break_chained_methods&quot;: false,</p> 
<p>&nbsp;&nbsp;&nbsp;&nbsp;&quot;e4x&quot;: false,</p> 
<p>&nbsp;&nbsp;&nbsp;&nbsp;&quot;wrap_line_length&quot;: 0,</p> 
<p><br /></p> 
<p>&nbsp;&nbsp;&nbsp;&nbsp;// jsformat options</p> 
<p>&nbsp;&nbsp;&nbsp;&nbsp;&quot;format_on_save&quot;: true,</p> 
<p>&nbsp;&nbsp;&nbsp;&nbsp;&quot;jsbeautifyrc_files&quot;: false</p> 
<p>}</p> 
<p><br /></p> 
<p>&nbsp;&nbsp;&nbsp; 3.Sublime Text 2自带代码格式化工具<br /></p> 
<p><br /></p> 
<p>选中代码</p> 
<p>菜单-edit-line-reindent 完成<br /></p> 
<p><br /></p> 
<p><br /></p> 
<p><br /></p> 
<p><br /></p> 
<p><br /></p>