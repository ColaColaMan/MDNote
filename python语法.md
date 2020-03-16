参照Python文档修改

# 杂项

## 待整理

Python特点：动态类型 and 强类型

1. 动态类型（自动跟踪你的类型而不要求声明）

2. 强类型（只能对对象进行适合该类型的有效操作）

## 环境迁移

```bash
# 旧电脑导出
pip freeze > r.txt
# 新电脑导入
pip install -r r.txt
```

## 语句书写：

》结尾：用分号或者换行(更佳)

》缩进：同一缩进量的语句块是一组程序语句,称为块suite

》换行输入：末尾加反斜杠\,换行写

》注释：

- 单行注释：# Comment

- 多行注释：''' Comment '''

- 中文注释：# coding=utf-8 



导入库：

```python
import moduleName as mN
```

安装库：

1. 安装自编库: py文件放入"sys.path[3]"dir

2. pip安装: pip install moduleName

发布库：[pip](https://pypi.org/project/pip/)

Standard Libraries 标准库：

| 库                                                      | 功能                                          |
| ------------------------------------------------------- | --------------------------------------------- |
| [timeit](https://docs.python.org/3/library/timeit.html) | Measure execution time of small code snippets |

