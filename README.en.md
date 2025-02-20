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

### 📖 Language

[简体中文](./README.md) | English

### ⌛ Start

#### Create Virtualenv

* Create Virtualenv in the root directory

#### Install third-party libraries

```
pip install fastapi==0.115.8 -i https://pypi.tuna.tsinghua.edu.cn/simple

pip install uvicorn==0.34.0 -i https://pypi.tuna.tsinghua.edu.cn/simple
```

#### Command list

###### Dev Mode

```bash
uvicorn main:app --port 18072 --reload
```

###### Prod Mode

```bash
uvicorn main:app --host 0.0.0.0 --port 18072
```

### 📜 Licence

[MIT License](https://opensource.org/licenses/MIT) Copyright (c) 2022 周博义
