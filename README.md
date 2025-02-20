<h1 align="center">📔 note-fastapi</h1>

<p align="center">
<a target="_blank" href="https://github.com/zhouboyi1998/note-fastapi"> 
<img src="https://img.shields.io/github/stars/zhouboyi1998/note-fastapi?logo=github">
</a>
<a target="_blank" href="https://opensource.org/licenses/MIT"> 
<img src="https://img.shields.io/badge/license-MIT-red"> 
</a>
<img src="https://img.shields.io/badge/Python-3.9.6-blue">
<img src="https://img.shields.io/badge/FastAPI-0.115.8-darkcyan">
<img src="https://img.shields.io/badge/Uvicorn-0.34.0-royalblue">
</p>

### 📖 语言

简体中文 | [English](./README.en.md)

### ⌛ 开始

#### 创建虚拟环境

* 在根目录下创建虚拟环境

#### 安装第三方库

```
pip install fastapi==0.115.8 -i https://pypi.tuna.tsinghua.edu.cn/simple

pip install uvicorn==0.34.0 -i https://pypi.tuna.tsinghua.edu.cn/simple
```

#### pip 国内镜像源

```
# 清华大学
https://pypi.tuna.tsinghua.edu.cn/simple

# 中国科学技术大学
https://pypi.mirrors.ustc.edu.cn/simple

# 阿里云
https://mirrors.aliyun.com/pypi/simple

# 豆瓣
https://pypi.douban.com/simple
```

#### 运行

###### 开发模式

```bash
uvicorn main:app --port 18072 --reload
```

###### 生产模式

```bash
uvicorn main:app --host 0.0.0.0 --port 18072
```

### 📜 开源协议

[MIT License](https://opensource.org/licenses/MIT) Copyright (c) 2022 周博义
