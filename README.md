# Chaos Video

## Architecture Overview

```plain
video-player <---> chaos-proxy <---> blank-server <---> video-gen 生成的视频分块

Chaos-proxy 和 blank-server为项目中一部分
```

## Development Guide

* 先使用 venv 在项目目录里创建一个 virtual environment `python3 -m venv .venv`
* 而后激活虚拟环境 `source .venv/bin/activate` (Windows 可能要使用其他方法)
* 安装依赖 `pip install -r requirements.txt`

通过 `runserver.py` 同时启动 chaos-proxy, blank-server, 以及前端 (TBD)。
