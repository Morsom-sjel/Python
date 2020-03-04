# PyCharm安装第三方库

**推荐方法二**

## 更新pip

+ 查看版本

```
pip -v
```

+ `Terminal` 中，正常pip升级命令

```
python -m pip install --upgrade pip
```

### 更新失败，及有些第三方库更新失败原因及解决措施

+ 网速慢，由于超时失败，切换热点或换镜像源



+ 设置 pip 安装源为国内清华大学镜像（忘记这个是不是清华的，用就完事了）

```
https://mirrors.ustc.edu.cn/pypi/web/simple/
```

**此界面下方方法二有进入方法**

![第三方库更改镜像源](https://github.com/Morsom-sjel/Python-study/blob/master/picture/%E7%AC%AC%E4%B8%89%E6%96%B9%E5%BA%93%E6%9B%B4%E6%94%B9%E9%95%9C%E5%83%8F%E6%BA%90.jpg?raw=true)



+ （针对python中pip，cmd更新失败）

**报错：**

```
You are using pip version 9.0.1, however version 9.0.3 is available.

You should consider upgrading via the 'python -m pip install --upgrade pip' command
```

直接去官网（[点击打开链接](https://pypi.org/project/pip/)）下载最新的pip，如：pip-10.0.1.tar，然后在命令行输入：pip install pip-10.0.1.tar  大功告成！！（注意安装路径）



+ （针对python中pip，cmd更新失败）

按照路径，你房python的地方，`python/Lib/site-packages/`，删掉文件`pip-....dist-info`

如果仍然不行，可能网络有问题，用国内的更新源（本人在这成功了，douban就是快！！）

```
python -m pip install --upgrade pip -i https://pypi.douban.com/simple
```



## 方法一、Terminal安装

**点击左下角`Terminal`**

```
pip install 包名
```

![Terminal安装库](https://github.com/Morsom-sjel/Python-study/blob/master/picture/Terminal%E5%AE%89%E8%A3%85%E5%BA%93.jpg?raw=true)



## 方法二

+ 左上角，`File` ——> `settings`

![第三方库(1)](https://github.com/Morsom-sjel/Python-study/blob/master/picture/%E7%AC%AC%E4%B8%89%E6%96%B9%E5%BA%93(1).jpg?raw=true)

+ 弹出界面左边，Project: untitled ——> Project Interpreter

![第三方库(2)](https://github.com/Morsom-sjel/Python-study/blob/master/picture/%E7%AC%AC%E4%B8%89%E6%96%B9%E5%BA%93(2).jpg?raw=true)

+ 右边，`+` ，进入搜索第三方库的界面

![第三方库(3)](https://github.com/Morsom-sjel/Python-study/blob/master/picture/%E7%AC%AC%E4%B8%89%E6%96%B9%E5%BA%93(3).jpg?raw=true)

+ 在搜索框中搜索对应想安装的库或者模块，点击左下方“Install package”

![第三方库(4)](https://github.com/Morsom-sjel/Python-study/blob/master/picture/%E7%AC%AC%E4%B8%89%E6%96%B9%E5%BA%93(4).jpg?raw=true)



**注：** 如果安装完成，该库显示字体颜色会变成蓝色，并且在上一个界面罗列出你已安装的库







# 转载请注明出处