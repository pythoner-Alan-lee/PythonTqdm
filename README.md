Tqdm 是一个快速，可扩展的Python进度条，可以在 Python 长循环中添加一个进度提示信息，用户只需要封装任意的迭代器 tqdm(iterator)。
安装tqdm
pip install tqdm
基本用法
from tqdm import tqdm
for i in tqdm(range(10000)):
     sleep(0.01)
