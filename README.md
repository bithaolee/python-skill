# PYTHON 填坑指北
PYTHON 常见问题及解决办法汇总

## 编码问题
python 系统默认编码为 ascii，常见的中文字符会引发各种编码问题，一个简单的解决办法，在项目中设置 python 解释器的默认编码格式为 utf-8
```python
import sys
reload(sys)
sys.setdefaultencoding('utf-8')
```
