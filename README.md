# Python Tool Template

Python 工具库模板 - 适用于创建 pip 包、CLI 工具、函数库等 Python 项目。

## 📦 包含内容

- ✅ 完整项目结构
- ✅ pyproject.toml 配置
- ✅ pytest 测试框架
- ✅ Black + Ruff 代码规范
- ✅ Sphinx 文档生成
- ✅ GitHub Actions CI/CD
- ✅ 自动发布到 PyPI

## 🚀 快速开始

### 使用模板创建新项目

1. 点击 **"Use this template"** 按钮
2. 输入新项目名称
3. 修改 `pyproject.toml` 中的包名

### 本地开发

```bash
git clone https://github.com/h1s97x/python-tool-template.git
cd python-tool-template
pip install -e .
```

## 📁 项目结构

```
.
├── .github/
│   └── workflows/
│       ├── ci.yml
│       └── release.yml
├── src/
│   └── package_name/
│       ├── __init__.py
│       └── core.py
├── tests/
│   └── test_core.py
├── docs/
│   └── index.md
├── pyproject.toml
├── README.md
└── LICENSE
```

## 🛠️ 开发命令

```bash
pip install -e .           # 开发模式安装
pytest                      # 运行测试
black .                     # 格式化代码
ruff check .               # 代码检查
sphinx-build -b html docs docs/_build  # 生成文档
```

## 📝 License

MIT
