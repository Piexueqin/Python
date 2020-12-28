# Python
#jupyter 默认工作路径的修改
打开文件：jupyter_notebook_config   （路径可在控制台查看）
找到：#c.NotebookApp.notebook_dir ='',将其修改为：c.NotebookApp.notebook_dir = r'D:\...'
注意：删除#之后，c前面不能有空格 ；
     目录单引号前加 r
jupyter notebook快捷键的默认工作目录还没有改，删除最后的%...%即可。
