# detail_zol_spyder
仅供学习参考，爬取中关村手机信息评价、品牌、价格等存入数据库或存入json文件等供数据分析使用
- 功能
爬取中关村的手机信息, 并存至数据库或text文件或者json文件， 数据分析代码无法使用，更新了作者BlueDamage大部分代码, 部分bs代码来自rovo98，代码仅供参考学习使用。
- 运行： `python 手机小虫.py`
- 生成：手机小虫.db 文件，可用navicat打开连接查看数据库内容
- 生成:  json_test.txt文件，可直接查看爬取内容，每一样都是一个字典，可以按行读取查看
- 依赖环境： 安装以下依赖包，python3.8
```python
re
os
time
random
pickle
sqlite3
requests
bs4
json
```
