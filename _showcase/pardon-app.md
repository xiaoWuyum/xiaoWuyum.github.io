---
title: "Pardon - 英语学习助手"
layout: showcase
venue: "个人项目"
date: 2024-03-19
---

这是一个基于 **Vite + React** 构建的现代化 Web 应用，旨在帮助用户在不同场景下学习地道的英语表达。项目利用 **shadcn/ui** 和 **Tailwind CSS** 搭建了美观且响应式的用户界面，并已成功部署在 Vercel 上。

### ✨ 主要功能:
*   **场景选择**: 用户可以选择不同的交流场景（如日常、商务、学术等）。
*   **风格定制**: 支持多种回答风格（如礼貌、口语、正式、幽默）。
*   **AI 驱动**: 集成 **Google Gemini** 大语言模型，根据用户输入的情境和问题，智能生成符合要求的英语问法和表达。

### 🚀 技术亮点:
*   **现代化前端架构**: 采用 **Vite** 作为构建工具，结合 **React** 与 **TypeScript**，提供了极致的开发体验和性能。
*   **精美的 UI 系统**: 基于 **Tailwind CSS** 和 **shadcn/ui** 组件库，实现了高度可定制化和视觉一致性的界面。
*   **前端 AI 集成**: 通过自定义 Hook (`useGemini.ts`) 直接在前端与 **Google Gemini API** 进行交互，实现了轻量、高效的 AI 对话功能。
*   **状态管理**: 使用自定义的 `useAppStore` Hook 进行全局状态管理，保证了应用数据的清晰流转。

---

<a href="https://github.com/xiaoWuyum/pardon" class="btn btn-outline-primary" target="_blank">GitHub 仓库</a>
<a href="https://pardon-eight.vercel.app/" class="btn btn-outline-primary" target="_blank">在线演示</a>
