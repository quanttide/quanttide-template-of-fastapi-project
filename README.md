# 量潮FastAPI项目模板

## 项目结构

- `app/`: 核心代码，主要使用FastAPI实现。
  - `models/`: ORM模型，主要使用SQLAlchemy。
  - `schemas/`: 领域模型，主要使用Pydantic实现。
  - `routers/`: 路由，主要使用FastAPI的`APIRouter`实现。
  - `dependencies/`: 依赖，主要使用FastAPI的依赖注入机制实现。
  - `config.py`: 配置，主要使用FastAPI-RESTful的[`APISettings`](https://fastapi-restful.netlify.app/user-guide/basics/api-settings/)实现。
- `tests`: 测试，主要使用Pytest实现。

## 创建新项目

1. 修改`pyproject.toml`文件。

## 迁移现有项目

```shell
poetry add fastapi uvicorn pydantic sqlalchemy fastapi-restful typing-inspect
poetry add pytest coverage pre-commit --group=dev
```
