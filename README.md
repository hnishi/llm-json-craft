# llm-json-craft

WIP project

## Development

```bash
poetry run pytest
```

## Publish

```bash
poetry publish -r testpypi --build
```

## Test Published Package

```bash
pip install llm-json-craft --extra-index-url https://test.pypi.org/simple
```

```py
import llm_json_craft

result = llm_json_craft.hello_world()
print(result)
```

## References

- https://zenn.dev/atu4403/articles/howto-poetry-dev
- https://kk6.hateblo.jp/entry/2018/12/20/124151
