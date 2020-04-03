LaTeX入门教程
##################


安装
***************************


这里为大家介绍Tex Live + Texstudio的安装 [#f1]_。





TeX Live属于比较完善的LaTeX编译器，其自带的文本编辑器为TeXworks是一款简洁的LaTeX编辑器，如果没有过多的需求，TeXworks完全可以满足需要。当然，为了追求更加美观或者流畅的体验，很多用户往往结合Atom、Sublime、VS Code、TeXstudio等编辑器来进行论文书写。这里我们选择了较为简单但功能强大的TeXstudio。



Windows
+++++++++++++

TeX Live 的当前版本是 2019，你可以从官方站点下载它们的安装包。点击\ `此处 <http://mirror.ctan.org/systems/texlive/Images/texlive2019.iso>`_，将会「自动选择」距离你最近的镜像下载。


当然，这个自动选择可能不太靠谱。如果你身处中国大陆，发现下载速度很慢，可以尝试\ `清华大学 <https://mirrors.tuna.tsinghua.edu.cn/CTAN/systems/texlive/Images/texlive2019.iso>`_\ 和\ `中国科技大学 <https://mirrors.ustc.edu.cn/CTAN/systems/texlive/Images/texlive2019.iso>`_\ 的镜像站。


你需要使用虚拟光驱软件（对于 Windows 8 及更高版本的微软用户，可以直接加载），加载下载得到的光盘镜像。而后，执行安装脚本，将 TeX Live 安装在你的系统中。


右键单击 install-tl-advanced.bat，以管理员权限执行；

按照指令选择安装路径，根据电脑配置不同大概需要15min-1h不等。

Mac
+++++++++++++

TeX Live 在 macOS/OS X 上的名字是 MacTeX，它的官方站点是 ``https://tug.org/`` mactex。你可以在\ `这里 <http://tug.org/cgi-bin/mactex-download/MacTeX.pkg>`_\ 下载 MacTeX 的安装器，而后安装 MacTeX。


如果你身处中国大陆，发现下载速度很慢，可以尝试\ `清华大学MacTeX  <https://mirrors.tuna.tsinghua.edu.cn/CTAN/systems/mac/mactex/MacTeX.pkg>`_\ 和\ `中国科技大学MacTeX  <https://mirrors.ustc.edu.cn/CTAN/systems/mac/mactex/MacTeX.pkg>`_\ 的镜像站。


下载以后打开安装包，将MacTeX安装在你的电脑中。



安装Texstudio
+++++++++++++

Texstudio 是免费软件，体积也比较小，直接从网络资源获取即可。

安装成功以后，打开texstudio，新建一个文件，输入以下代码，然后点运行，如果下方没有报错就是安装成功啦。



.. code-block:: latex

	\documentclass{article}
	\begin{document}
		Hello, LaTex.
	\end{document}


关于在线平台Overleaf
++++++++++++++++++++++
实际上，配置LaTeX环境是令每一个初学者都很头疼的事情。

如果你不想一开始就将大把的时间花费在环境配置上，可以先从在线运行环境Overleaf开始。









第一个\LaTeX程序
********************

新建一个 ``my_test.tex`` 文档,写下如下的内容：

.. code-block:: latex

	\documentclass{article}  
	% 文档类型: 可选report / book / proc / slides / minimal
	\begin{document}   				% 开始编写文档，命令以\开头
		"hello \LaTeX!"   			% 文档内容，用%注释
	\end{document}     				% 结束编写文档，命令以\开头


点击编译，就可以得到一个pdf文件了。


If :math:`\sigma_{1}` equals :math:`\sigma_{2}` then etc, etc.




.. math::
	(a + b)^2 = a^2 + 2ab + b^2
	(a - b)^2 = a^2 - 2ab + b^2




基本结构
****************






章节和段落
****************





符号和公式
****************




插入图表
****************




参考文献
****************



附录
****************





美赛论文模板
****************







.. [#f1] Text of the first footnote.
