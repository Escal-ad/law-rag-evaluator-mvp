# 法律 RAG 评测工作台 MVP

一个纯静态的法律模型评测展示页，使用 HTML 与 CSS 编写，不依赖 JavaScript、构建工具或后端。

## 本地预览

直接在浏览器打开 `index.html` 即可。

## 功能范围

- 展示项目指标摘要、法律问答评测样例和人工判定依据。
- 使用 CSS 单选控件筛选 Bad Case。
- 展示数据处理流程、质量维度、评测检查清单及演示版版本记录。
- 页面不调用模型、不保存数据、不接收用户上传，也不构成法律意见。
- 样例和版本记录均为演示内容；项目指标摘要只转录方案中已有的简历数据。

## GitHub Pages

仓库创建并推送后，在仓库 `Settings → Pages` 中将部署来源设为 `Deploy from a branch`，选择 `main` 分支和 `/(root)` 目录并保存。部署完成后，GitHub Pages 会提供公开访问地址。

若仓库为 `https://github.com/<用户名>/law-rag-evaluator-mvp`，默认站点地址通常为 `https://<用户名>.github.io/law-rag-evaluator-mvp/`。