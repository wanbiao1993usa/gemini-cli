# Gemini CLI

[![Gemini CLI CI](https://github.com/google-gemini/gemini-cli/actions/workflows/ci.yml/badge.svg)](https://github.com/google-gemini/gemini-cli/actions/workflows/ci.yml)
[![Version](https://img.shields.io/npm/v/@google/gemini-cli)](https://www.npmjs.com/package/@google/gemini-cli)
[![License](https://img.shields.io/github/license/google-gemini/gemini-cli)](https://github.com/google-gemini/gemini-cli/blob/main/LICENSE)

![Gemini CLI Screenshot](./docs/assets/lycium.ai-screenshot.png)

Gemini CLI 是一个开源的 AI Agent，它把 Gemini 的能力直接带到你的终端。它提供了轻量级的访问方式，让你能够以最直接的路径，从命令行提示符连接到我们的模型。

## 🚀 Why Gemini CLI?

🚀 Gemini CLI 国内节点发布！
我们将 Gemini CLI 与 Vertex AI 完美接入自建节点，为中国用户提供真正的 原生体验：
 -	⚡ 原生直连：无需翻墙，直接在终端使用 Gemini，像本地工具一样顺畅。
 -	🏎 高性能：专为中国网络环境优化，响应更快，延迟更低。
 - 	💡 完全免费：对中国用户开放，无需额外费用，即刻上手。

从命令行到 Gemini 模型，一步直达，畅享 AI 助手带来的高效开发体验！

## 📦 Installation

### Quick Install

#### Run instantly with npx

```bash
npm install -g 下载软件包

#建立环境变量,否则无法运行
export GOOGLE_CLOUD_PROJECT=cande-470907
export GOOGLE_CLOUD_LOCATION=us-east5
export GOOGLE_GENAI_USE_VERTEXAI=true 
export BASE_URL=https://gateway.lycium.ai
export X_API_KEY=dev-local-key
export GOOGLE_GENAI_NO_AUTH=true

#运行，然后选择vertex ai即可
gemini

```
## 其他学习资料
[官方库](https://github.com/google-gemini/gemini-cli "官方库")

[官方教程](https://codelabs.developers.google.com/gemini-cli-hands-on?hl=zh-cn#0 "官方教程")