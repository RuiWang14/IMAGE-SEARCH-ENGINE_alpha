# IMAGE-SEARCH-ENGINE_alpha

这是一个简单的图像搜索引擎实现。采用了分区域的色彩分布直方图的方式比较的方式，简单易懂。

现在整个项目还处在建设当中，如有不当之处，还望见谅。R

---
##示例搜索语句：

	$ python search.py --index index.csv --query queries/108100.png --result-path dataset

	$ python search.py --index index.csv --query queries/115100.png --result-path dataset

---
##系统要求：
python 2.7

opencv 2.4.x

---
##文件说明：
- dataset —— 数据库，约有1000张背景图片,现阶段未包含 
- pyimagesearch —— 内含描述器，搜索引擎
- queries —— 请求图片，现阶段未包含
- index.csv —— 索引库
- index.py —— 建立索引库的脚本
- search.py —— 搜索脚本