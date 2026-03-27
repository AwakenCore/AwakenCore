# AwakenCore Cloud

云端服务，提供语音识别、大模型意图解析、API 接口。

## 技术栈

- Python 3.10+
- FastAPI
- WebSocket

## 目录结构

```
cloud/
├── api/            # FastAPI 路由
├── services/       # 业务逻辑
├── models/         # 数据模型
└── config/         # 配置文件
```

## 快速开始

```bash
cd cloud
pip install -r requirements.txt
uvicorn main:app --reload
```
