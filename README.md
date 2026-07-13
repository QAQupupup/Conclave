# Conclave

**Conclave** 是一个多智能体会议系统，基于 LLM 驱动的结构化辩论框架，用于议题澄清、团队内协作、跨团队协商与最终决策产出。

## 开源版本

本仓库是 Conclave 的开源发布版本，核心算法逻辑以 Cython 编译的二进制扩展形式提供，Pydantic 数据模型保持源码形式。

版本自动从私有开发仓库 [Conclave-internal](https://github.com/QAQupupup/Conclave-internal) 通过 CI/CD 流水线同步到 `auto-sync` 分支。

## 快速开始

```bash
git clone https://github.com/QAQupupup/Conclave.git
cd Conclave
docker compose up -d
```

访问 `http://localhost:5174` 打开前端界面。

## 技术栈

- 后端: Python 3.12, FastAPI, gRPC
- 前端: React, TypeScript, Vite
- 数据库: PostgreSQL + pgvector, Redis, Qdrant
- 部署: Docker Compose

## 许可证

MIT License
