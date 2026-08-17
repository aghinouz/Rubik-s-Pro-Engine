<div align="right">
  <a href="README.md">🇬🇧 English</a> | <strong>🇨🇳 简体中文</strong>
</div>

# Rubik's Pro Engine: 3D-2D Topological Simulation 🧊

一个极致纯净、高性能的 N 阶魔方拓扑学可视化引擎。无需安装任何依赖，单文件直接运行。

## ✨ 核心特性

*   **无限阶泛化支持**：支持任意阶无缝切换与渲染。
*   **极致性能 (GPU Instancing)**：底层采用 Three.js 的 `InstancedMesh` 重构。无论魔方阶数多高，Draw Call 始终死锁为 2 次，消灭渲染瓶颈。
*   **连续拓扑映射**：左侧 2D 拓扑图严格基于三维极坐标焦点运算，实时完美映射 3D 视角的空间偏折。
*   **WCA 代数引擎**：原生支持标准 Singmaster 公式解析（支持 `U`, `M`, `3Rw`, `2L'`, `x` 等），支持输入框异步队列盲打，动画期间永不失去焦点。
*   **可逆编辑模式**：内置支持滑动操作的涂色板，并附带严密的拓扑物理校验（总数守恒、面色互斥、对立色互斥）。
*   **历史与因果回溯**：支持完整的双向时间轴（撤销 Undo / 重做 Redo），支持符合 WCA 标准的一键极速打乱。

## 🚀 快速体验

本项目已部署至 GitHub Pages，点击即玩：
**[👉 在线体验地址](https://aghinouz.github.io/Rubik-s-Pro-Engine/)**

## 🛠️ 本地运行

纯前端单文件结构，零依赖。直接 clone 本仓库，在任意现代浏览器中双击打开 `index.html` 即可运行。

## 📄 开源协议

本项目基于 [GPLv3 License](LICENSE) 协议开源。

## ☕ 赞助与支持
如果您觉得这个脚本节省了您的时间，或者单纯想支持一下开发工作，欢迎通过以下方式请作者喝杯咖啡：
*   [**爱发电 (Afdian)**](https://afdian.com/a/aghinouz) | [**Ko-fi**](https://ko-fi.com/aghinouz) | [**Patreon**](https://patreon.com/aghinouz)
