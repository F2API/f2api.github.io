# F2API

## 📖 简介
🌐 **官网地址**: [https://f2api.com](https://f2api.com)

**F2API** 是一个聚合AI网关，旨在简化大语言模型（LLM）的接入与管理。它作为一个统一的代理层，将 OpenAI、Anthropic (Claude)、Google (Gemini) 等全球主流 AI 供应商聚合到一个**完全兼容 OpenAI 协议**的接口中。

🚀 **支持国内直接访问**，并完美兼容 **CherryStudio, NextChat, LobeChat, BotGem, OpenCat, Claude Code** 等大多数 AI 客户端。

无论您是构建企业内部 AI 中台，还是面向公众的 AI 服务，F2API 都能提供您所需的关键基础设施：智能负载均衡、计费系统、用户管理和安全防护。

## ✨ 核心特性

- **🚀 多模型聚合**: 通过一个 API Key 即可访问 OpenAI, Anthropic, Google, DeepSeek, Qwen 等全球主流大模型。
- **🔌 兼容 OpenAI**: 完全兼容 OpenAI API 格式。可直接接入 NextChat, LobeChat, Cherry Studio 等现有应用，无需修改代码。
- **⚖️ 高可用架构**: 内置智能负载均衡、失败自动重试、熔断机制，确保服务的高可用性和稳定性。
- **💰 计费与配额**: 完善的积分扣费系统，精确到 Token 的用量统计。
- **🛡️ 企业级安全**: 支持 API Key 管理（额度/过期时间）、IP 审计、请求日志记录，保障数据安全。
- **📊 可视化面板**: 提供直观的仪表盘，实时监控请求量、消费金额、模型分布等关键指标。


## 📚 常见问题指南

### 🔑 常用模型 API Key 获取教程

#### Gemini API Key 怎么获取
前往 Google AI Studio (aistudio.google.com)，登录 Google 账号即可免费申请。注意：Google 服务通常需要特定网络环境。

#### Claude API Key 如何申请
访问 Anthropic Console (console.anthropic.com)，注册账号并绑定支持美元支付的信用卡（如 Visa/MasterCard）后即可创建 Key。

#### OpenAI API Key 获取
登录 OpenAI Platform (platform.openai.com)，在 API Keys 页面生成。OpenAI 账号注册及充值通常需要海外手机号和信用卡。

#### DeepSeek API Key 哪里领
访问 DeepSeek 开放平台 (platform.deepseek.com)，手机号注册即可获取 API Key。目前 DeepSeek 性价比极高，是开发者的热门选择。

### 🛠️ 接口配置与使用指南

#### OpenAI 接口转发/中转服务
如果您在国内网络环境下无法直接连接 OpenAI，或者没有海外信用卡，可以使用 F2API 提供的接口转发服务。我们完全兼容 OpenAI 官方协议，只需将接口地址（Base URL）替换为 `https://api.f2api.com/v1` 即可。

#### 国内如何使用 ChatGPT API
由于网络限制，国内开发者直接调用 ChatGPT API 经常遇到连接超时或 IP 封禁问题。通过 F2API 聚合网关，您可以直接在国内网络环境下稳定调用 GPT-4o, Claude 3.5 Sonnet, Gemini 1.5 Pro 等前沿模型，无需配置复杂的代理网络。

#### NextChat / LobeChat 接口地址怎么填
在 NextChat (ChatGPT-Next-Web)、LobeChat、Cherry Studio 等开源客户端中，找到“自定义接口”或“OpenAI 设置”：
- **接口地址 (Base URL)**: 填写 `https://api.f2api.com/v1`
- **API Key**: 填写在 F2API 获取的 `sk-` 开头的密钥

> 💡 **省心推荐**：官方渠道申请门槛较高且容易封号。使用 **F2API**，无需魔法、无需海外卡，一站式接入上述所有模型，稳定可靠！


# 📖 Introduction
🌐 **Official Website**: [https://f2api.com](https://f2api.com)

**F2API** is an aggregated AI gateway designed to simplify the integration and management of Large Language Models (LLMs). Acting as a unified proxy layer, it aggregates major global AI providers like OpenAI, Anthropic (Claude), and Google (Gemini) into a single interface **fully compatible with the OpenAI protocol**.

🚀 **Supports direct access from China**, and is perfectly compatible with most AI clients such as **CherryStudio, NextChat, LobeChat, BotGem, OpenCat, Claude Code**, etc.



Whether you are building an internal enterprise AI platform or a public-facing AI service, F2API provides the critical infrastructure you need: intelligent load balancing, billing systems, user management, and security protection.

## ✨ Core Features

- **🚀 Multi-Model Aggregation**: Access major global large models like OpenAI, Anthropic, Google, DeepSeek, and Qwen with a single API Key.
- **🔌 OpenAI Compatibility**: Fully compatible with the OpenAI API format. Directly integrate with existing applications like NextChat, LobeChat, and Cherry Studio without code modifications.
- **⚖️ High Availability Architecture**: Built-in intelligent load balancing, automatic retry on failure, and circuit breaker mechanisms ensure high service availability and stability.
- **💰 Billing & Quotas**: Comprehensive credit deduction system with precise token-level usage statistics.
- **🛡️ Enterprise-Grade Security**: Supports API Key management (quotas/expiration), IP auditing, and request logging to ensure data security.
- **📊 Visual Dashboard**: Provides an intuitive dashboard for real-time monitoring of key metrics such as request volume, consumption amount, and model distribution.
