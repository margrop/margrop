# Margrop

**AI Platform & Distributed Systems Engineer** · Shanghai · [blog.margrop.net](https://blog.margrop.net)

我关注把模型、Agent、设备和分布式基础设施做成可运行、可观测、可恢复的系统；业余时间把这些能力落到家庭场景里，做成开箱即用的自托管工具。

## Focus

- Robotics cloud platforms and device-facing distributed systems
- Model gateway、Agent runtime、memory、evaluation and cost control
- WebSocket/streaming workflows、observability and reliability engineering
- Self-hosted apps for family learning and smart home（Home Assistant）

## Now Building

### [`wrong-notebook`](https://github.com/margrop/wrong-notebook) · 智能错题本

[![Stars](https://img.shields.io/github/stars/margrop/wrong-notebook?logo=github)](https://github.com/margrop/wrong-notebook/stargazers) [![Release](https://img.shields.io/github/v/release/margrop/wrong-notebook?include_prereleases)](https://github.com/margrop/wrong-notebook/releases) [![npm downloads](https://img.shields.io/npm/d18m/wrong-notebook?label=npm%20downloads&logo=npm)](https://www.npmjs.com/package/wrong-notebook)

AI 错题本：拍照识题、解答、知识点标签、举一反三、组卷打印与掌握度跟踪。Fork 自 [`wttwins/wrong-notebook`](https://github.com/wttwins/wrong-notebook)，在此基础上持续迭代：

- 多 AI 提供商（Gemini / OpenAI / Azure / Anthropic，以及 MiniMax、GLM、DeepSeek、Kimi 等国产模型），支持 MiniMax 免费账号 OAuth 登录
- 多平台安装：Docker（amd64 / arm64）、npm、Windows / macOS / Linux 桌面版、飞牛OS、Android 单机版与客户端版
- Vitest + Playwright E2E + CodeQL 的 CI，预览版 / 正式版分级发布

[项目主页](https://blog.margrop.net/wrong-notebook-github-pages/) · [在线演示](https://wrong-notebook-demo.vercel.app) · [介绍文章](https://blog.margrop.net/post/wrong-notebook-ai-family-learning/)

### Home Assistant 集成

- [`ha-china-mobile`](https://github.com/margrop/ha-china-mobile)：中国移动集成，只读获取话费余额、本月消费、套餐流量和积分
- [`telecom-phone-device-id-tools`](https://github.com/margrop/telecom-phone-device-id-tools)：本地运行的中国电信 DeviceId 授权工具，解决 `china_telecom` 集成登录返回 3006「设备未信任」的问题；仅直连官方接口，凭证不落盘

## Selected Work

### [`coding-plan-dashboard`](https://github.com/margrop/coding-plan-dashboard)

Self-hosted quota and cost dashboard for AI coding plans（Codex、Volcengine、Kimi、LongCat、Qianwen、Google AI），with Docker deployment and provider adapters.

### [`ai-video-studio`](https://github.com/margrop/ai-video-studio)

Provider-neutral AI content pipeline with planning、queue、worker recovery、MCP、TTS、storage、rate limiting and cost boundaries.

### [`margrop-labs`](https://github.com/margrop/margrop-labs)

Reproducible engineering labs for incident diagnosis、metrics、logs、token workflows and safe local experiments.

## Account Note

`XingP14` is my second GitHub account.

Projects maintained there are linked as second-account work, not presented as `margrop` originals.

- [`woclaw`](https://github.com/XingP14/woclaw)：WebSocket relay hub for OpenClaw multi-agent communication
- [`llm-benchmark`](https://github.com/XingP14/llm-benchmark)：Local LLM benchmarking across multiple models and providers
- [`openclaw-config-doctor`](https://github.com/XingP14/openclaw-config-doctor)：Diagnose and fix common OpenClaw configuration problems

`XingP14/claude-code` is not included in the selected work list or job-search portfolio.

## Writing

- Blog: https://blog.margrop.net
- Portfolio: https://blog.margrop.net/career/

## Principles

- Secrets stay outside repositories、logs and URLs.
- Experiments are labeled as experiments，not presented as production scale.
- Every automation path has an explicit permission boundary、failure mode and rollback path.
