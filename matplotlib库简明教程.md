# Matpoltlib Pyplot
使用方法：
要使用Matplotlib的Pypolt子库，我们首先需要将其导入到代码文档中：
```python
import matplotlib.pypolt as plt     # 导入Pypolt子库并设置别名为“plt”
```
这样我们就可以使用`plt`来调用Pypolt包的方法

**常用的Pypolt函数**：
|     函数     |            用途            |
| :----------: | :------------------------: |
|   `plot()`   |      绘制线图和散点图      |
| `scatter()`  |         绘制散点图         |
|   `bar()`    | 绘制垂直条形图和水平条形图 |
|   `hist()`   |         绘制直方图         |
|   `pie()`    |          绘制饼图          |
|  `imshow()`  |          绘制图像          |
| `subpolts()` |          创建子图          |

例：
```python
import numpy as np
import matplotlib.pyplot as plt

x = np.array([0,100])
y = np.array([0,20])

plt.plot(x,y)
plt.show()
``` n