# 托福精听比对系统 (TOEFL Dictation Comparison System)

[![Spark API](https://img.shields.io/badge/Powered%20by-Spark%20AI-blueviolet)](https://www.xfyun.cn/spark)
[![Tech Stack](https://img.shields.io/badge/Tech-HTML%2FCSS%2FJS-orange)](https://developer.mozilla.org/)
[![License](https://img.shields.io/badge/License-MIT-green)](./LICENSE)

**一个智能、高效的托福听写练习与分析工具，旨在帮助托福考生精准定位听写问题，并通过AI智能评语快速提升。**

---

## ✨ 功能亮点

- **📝 智能文本比对**:
  - **高亮显示**: 自动标记<span style="color:red;">**错误**</span>、<span style="color:orange;">**遗漏**</span>和<span style="text-decoration:line-through;">**多余**</span>的单词。
  - **逐字分析**: 精准定位每一个听写差异。

- **📊 多维度统计分析**:
  - **核心数据**: 提供正确率、错误数、多余字数等关键指标。
  - **可视化图表**: 通过甜甜圈图直观展示错误类型分布（拼写、遗漏、多余）。

- **🤖 AI智能评语 (Powered by Spark API)**:
  - **自动生成**: 比对完成后自动触发，无需手动操作。
  - **专业建议**: 模拟托福听力教师，从整体表现、具体问题、改进建议和练习方法四个方面提供专业反馈。
  - **一键复制**: 方便保存和分享AI评语。

- **🚀 便捷的导出与分享**:
  - **TXT报告**: 一键导出包含统计信息、比对详情和AI评语的完整TXT报告。
  - **精准截图**: 截取核心比对结果区域，方便分享和记录。
  - **快速复制**: 支持一键复制比对结果或统计信息。

- **⌨️ 高效的快捷键支持**:
  - `Cmd/Ctrl + Enter`: 开始比对
  - `Cmd/Ctrl + Shift + C`: 复制比对结果
  - `Cmd/Ctrl + Shift + E`: 导出TXT报告
  - `Cmd/Ctrl + Shift + S`: 截图下载
  - `Esc`: 清空所有内容

- **📱 响应式与用户友好设计**:
  - **跨设备使用**: 完美适配桌面和移动设备。
  - **自动隐藏说明**: 首次使用后，使用说明会自动收起，保持界面整洁。
  - **模态框交互**: "联系我们"和"历史记录"功能使用体验友好的模态框。

---

## 🛠️ 技术栈

- **前端**: HTML, CSS (Tailwind CSS), JavaScript
- **图表**: [Chart.js](https://www.chartjs.org/)
- **截图**: [html2canvas](https://html2canvas.hertzen.com/)
- **AI能力**: [科大讯飞星火认知大模型 (Spark API)](https://www.xfyun.cn/spark)

---

## 🚀 如何使用

1.  **访问在线网站**:
    
    您可以直接访问我们的在线网站: [https://tfjt.netlify.app](https://tfjt.netlify.app)

    > 免责声明：本站托管于Netlify的免费服务器上，可能会出现访问速度慢或者暂时无法访问的情况。如遇此类情况，请稍后再试。
2.  **配置API (重要)**:
    - 打开 `init-spark.js` 文件。
    - 将您的星火大模型 `APPID`, `APISecret`, 和 `APIKey` 填入相应位置。
3.  **打开页面**:
    - 在浏览器中直接打开 `index.html` 文件即可开始使用。

---

## 展望未来

我们致力于持续改进此工具，未来计划开发以下功能：

- **📈 历史记录与进度追踪**:
  - 保存每一次的比对历史。
  - 生成学习曲线和错误趋势分析报告。
  - 帮助用户更科学地追踪自己的进步。

---

## 📧 联系我们

如果您在使用过程中遇到任何问题，或有任何宝贵的建议，欢迎通过以下方式联系我们：

- **邮箱**: `smtoffice@yeah.net`

---

## 📄 开源许可

该项目采用 [MIT License](./LICENSE) 开源。