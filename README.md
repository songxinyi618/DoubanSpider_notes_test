# DoubanSpider_notes_test

一句话介绍：这是在DoubanSpider_notes之前的一次尝试，没有调用selenium，企图根据豆瓣书籍的序号来爬取所有书籍的书名、ISBN号、读书笔记内容和用户头像。

备注：还是由于ip的限制，每天只能爬4000本书，而豆瓣据推测有300多万本书，是个大工程啊~ 虽然代码可行，但这项工作没有实际意义，所以爬了几天就放弃了。

语言：Python

软件：Spyder(Python 3.6)

调用的库：

BeautifulSoup —— BeautifulSoup是Python的一个库，最主要的功能就是从网页爬取我们需要的数据。BeautifulSoup将html解析为对象进行处理，全部页面转变为字典或者数组，相对于正则表达式的方式，可以大大简化处理过程。

urllib —— Urllib库是Python中的一个功能强大、用于操作URL，并在做爬虫的时候经常要用到的库。在Python2.x中，分为Urllib库和Urllin2库，Python3.x之后都合并到Urllib库中，使用方法稍有不同。本次使用的是Python3中的urllib库。

pandas —— Python Data Analysis Library 或 pandas 是基于NumPy 的一种工具，该工具是为了解决数据分析任务而创建的。Pandas 纳入了大量库和一些标准的数据模型，提供了高效地操作大型数据集所需的工具。pandas提供了大量能使我们快速便捷地处理数据的函数和方法。你很快就会发现，它是使Python成为强大而高效的数据分析环境的重要因素之一。

