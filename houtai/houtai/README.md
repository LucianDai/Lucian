manage.py  项目的管理，启动项目、创建app、数据管理
asgi.py  接受网络请求（异步式）
wsgi.py  接受网络请求（同步式）
urls.py  URL和函数的对应关系
settings.py  项目的配置文件
__pycache__ 文件夹是 Python 解释器在执行模块导入时自动生成的一个特殊文件夹。它用于存储编译后的字节码文件（.pyc 文件），以便提高后续导入相同模块时的执行速度。
init.py"文件是一个特殊的文件，用于指示一个目录是一个 Python 包。当导入一个包时，Python 解释器会查找并执行该包目录中的 "init.py" 文件。这使得包可以执行一些初始化操作、定义包级别的变量或者包级别的导入语句。