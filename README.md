# codex-html-lab

> Codex 驱动的 HTML 小工具实验室：从规格到页面、从提示到组件。  
> Build tiny, useful web tools with natural-language specs.

![status](https://img.shields.io/badge/status-alpha-blue)
![license](https://img.shields.io/badge/license-MIT-green)
![pages](https://img.shields.io/badge/deploy-GitHub%20Pages-informational)

---

## ✨ What’s inside
- **Spec → App**：从自然语言规格生成可用 HTML 页面与组件
- **Prompt → HTML**：提示词到页面骨架与样式的快速落地
- **UI Bits**：可复用的微型组件（模态框、通知、表单校验等）
- **Playground**：在浏览器直接试验提示词与代码片段
- **Pass@K 对比（可选）**：将多次生成结果进行对比与验收

---

## 🧩 目录结构（建议）
````

.
├─ /apps               # 独立的小工具应用
│  └─ /playground      # 提示→HTML 在线实验页
├─ /components         # 可复用 UI 组件（纯原生/少依赖）
├─ /specs              # 自然语言规格、用例与验收标准
├─ /templates          # 页面/组件/文档 模板
├─ /public             # 静态资源
└─ index.html          # 入口（可用于 GitHub Pages）

````

---

## 🚀 快速开始
**本地：** 双击 `index.html` 或使用静态服务器（例如）：
```bash
npm i -g http-server
http-server . -p 5173
````

访问 [http://localhost:5173](http://localhost:5173)

**GitHub Pages：** Settings → Pages → Source: `Deploy from a branch`；选择 `main` 与根目录。

---

## 🧠 协作方式（Spec → App）

在 `specs/` 写**可执行规格**，然后在 Playground 中粘贴生成的 HTML 进行验收。示例模板见下文与页面左侧下拉框。

---

## ✅ 贡献指南（精简）

1. 先搜 Issue，没有则创建（Bug/Feature/Spec→App 模板）。
2. 新分支：`feat/*` / `fix/*`，提交以 `feat:`/`fix:`/`docs:` 开头。
3. PR 时附截图/GIF，确保页面本地可运行。

---

## 🪪 许可证

本项目采用 [MIT License](LICENSE)。

````
