<!-- ========= 顶部横幅 ========= -->
<p align="center">
  <img src="assets/Python.png" width="12000">
  <br>
  <strong>Training_Programme</strong>
  <br>
  <em>一站式 Python 训练脚本模板 | 开箱即用 · 持续集成 · 文档友好</em>
</p>

<!-- ========= 徽章一行 ========= -->
<p align="center">
  <img src="https://img.shields.io/github/license/llh21/Training_Programme" alt="License"/>
  <img src="https://img.shields.io/github/stars/llh21/Training_Programme" alt="Stars"/>
  <img src="https://img.shields.io/badge/python-3.10-blue" alt="Python"/>
  <img src="https://github.com/llh21/Training_Programme/workflows/CI/badge.svg" alt="CI"/>
</p>

<!-- ========= 目录（折叠） ========= -->
<details>
<summary>📙 目录</summary>

- [🚀 快速开始](#-快速开始)
- [📂 项目结构](#-项目结构)
- [📸 效果预览](#-效果预览)
- [🛠️ 本地开发](#️-本地开发)
- [🤝 参与贡献](#-参与贡献)
- [📄 开源协议](#-开源协议)
</details>

---

## 🚀 快速开始
```bash
git clone https://github.com/llh21/Training_Programme.git
cd Training_Programme
pip install -r requirements.txt
python examples/quick_start.py
```
---

## 📂 项目结构
```bash
Training_Programme
├── src/                 # 核心源码
├── examples/            # 可运行示例
├── tests/               # 单元测试
├── docs/                # 详细文档
├── assets/              # README 图片 / GIF
├── .github/             # GitHub Actions
├── requirements.txt
├── .gitignore
└── README.md
```

## 📸 效果预览
```bash
| CLI 运行                                                                                                 | Web Demo                                                                                               |
| ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------ |
| <img src="https://raw.githubusercontent.com/llh21/Training_Programme/main/assets/cli.gif" width="400"> | <img src="https://raw.githubusercontent.com/llh21/Training_Programme/main/assets/web.png" width="400"> |
```

## 🛠️ 本地开发
```bash
| 命令                               | 说明                             |
| -------------------------------- | ------------------------------ |
| `python examples/quick_start.py` | 跑通最小示例                         |
| `pytest tests/`                  | 运行全部测试                         |
| `mkdocs serve`                   | 本地预览文档（需 `pip install mkdocs`） |
```

## 🤝 参与贡献
```bash
Fork 本仓库
新建分支 feat/xxx
提交 PR → CI 通过后合并
🎉 你的名字将出现在贡献者列表！
```

## 📄 开源协议
```bash
MIT © 2024 llh21
```
