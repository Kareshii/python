#在windows环境下安装python以及beautifulsoup4与lxml

#第一步 python
* https://www.python.org/ftp/python
* 注意勾选Add python path 环境变量

#第二步 beautifulsoups4
* https://www.crummy.com/software/BeautifulSoup/bs4/download/4.6/
* 解压安装包到python工作文件夹，如d:\python
* 在 Windows PowerShell里打开这个文件夹 cd d:\python\beautifulsoup4-4.4.1
* 最后输入：<br> python setup.py build <br> python setup.py install

#第三步 lxml
* 下载.whl包 http://www.lfd.uci.edu/~gohlke/pythonlibs/
* 输入：pip install wheel <br> pip install lxml_文件名.whl (注意文件名不能改！！！)
