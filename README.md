# FastAPI Learning Journal

Personal notes and experiments while working through the [FastAPI User Guide](https://fastapi.tiangolo.com/learn/).

## What's This?

I'm going through the official FastAPI documentation and creating my own distilled notes as Jupyter notebooks. The goal is to have comprehensive, executable summaries I can reference later without having to dig through the full docs every time.

## Progress

- [x] [Python Types Intro](fastapi_python_types.ipynb) - Type hints, generics, Pydantic basics
- [x] [Concurrency and async/await](fastapi_async_await.ipynb)
- [x] [Environment Variables](fastapi_environment_variables.ipynb)
- [ ] Tutorial - User Guide
  - [ ] First Steps
  - [ ] Path Parameters
  - [ ] Query Parameters
  - [ ] Request Body
  - [ ] (and so on...)

## Structure

Each notebook covers one section from the docs with:
- Key concepts explained
- Working code examples
- My own notes and observations
- Practice exercises where useful

## Setup

Using `uv` for dependency management:

```bash
uv sync
```

Dependencies are in `pyproject.toml` - just FastAPI with the standard extras and ipykernel for Jupyter.


## Why?

Reading docs is fine, but having my own reference with examples I've actually run makes it way easier to remember and review later. Plus, typing things out helps me understand better than just reading.