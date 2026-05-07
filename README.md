# 🎉 FlowPrompt Studio 1.0.0

> **English**: Make prompting more professional, make AI understand you better  
> **中文**: 让提示词更专业，让 AI 更懂你

---

## 📌 这是什么？| What is this?

**FlowPrompt Studio** 是一个 VS Code 扩展，帮你把模糊的想法变成 AI 能精准理解的提示词。

> **FlowPrompt Studio** is a VS Code extension that helps you transform vague ideas into precise prompts that AI can understand.

### 解决什么问题？| What problems does it solve?

| 场景 Scenario | 痛点 Pain Point | 解决方案 Solution |
|-------------|----------------|-----------------|
| 你有想法但说不清楚 | AI 反复问"你想做什么" | 5步表单引导你结构化表达 |
| You have an idea but can't articulate it | AI keeps asking "what do you want" | 5-step form guides structured expression |
| 问题很复杂 | AI 理解偏差，给出错误答案 | 强制完整上下文，减少歧义 |
| Complex problems | AI misunderstands, gives wrong answers | Enforces complete context, reduces ambiguity |
| 和 AI 来回沟通效率低 | 说了10轮还没进入正题 | 一次性提供完整背景，标准化格式 |
| Inefficient back-and-forth | 10 rounds and still not on topic | Provide full context upfront, standardized format |

---

## ✨ 核心功能 | Key Features

### 🎯 工程化提示词工作台 | Engineering Prompt Workbench

通过 **5 步表单** 把你的需求变成专业提示词：  
Transform your requirements into professional prompts through a **5-step form**:

```
Step 1: 上下文 Context
        → 项目类型、技术栈、问题背景
        → Project type, tech stack, problem background

Step 2: 排查记录 Troubleshooting Log  
        → 你尝试过什么、结果如何
        → What you've tried and the results

Step 3: 核心问题 Core Problem
        → 一句话精准定义问题
        → One-sentence precise problem definition

Step 4: 验收标准 Acceptance Criteria
        → 怎样算"做好了"？可量化的指标
        → What counts as "done"? Measurable metrics

Step 5: 边界定义 Boundaries
        → 做什么、不做什么、技术限制
        → What's in/out, technical constraints
```

**亮点 | Highlights:**
- 📊 实时质量评分 (0-100分) | Real-time quality score
- 💾 自动保存草稿 (AES-256加密) | Auto-save drafts
- ✅ 一键生成标准化提示词 | One-click standardized prompt generation

---

### 🤖 深度集成 Trae CN | Deep Trae CN Integration

- 🔍 自动检测 Trae CN 安装状态 | Auto-detect Trae CN installation
- 🚀 一键发送提示词到 Trae CN | One-click send to Trae CN
- 📝 保持对话连续性 | Maintain conversation continuity
- 🎨 自动优化提示词格式 | Auto-optimize prompt formatting

---

### 🔍 代码审计引擎 | Code Auditing Engine

基于 Tree-sitter 的实时代码分析：  
Real-time code analysis powered by Tree-sitter:

- 🌳 AST 语法树分析 | AST analysis
- 🌍 支持 10 种语言 | 10 languages supported (JS/TS/Python/Java/Go/C#/C++/Rust...)
- ⚠️ 实时检测代码问题 | Real-time issue detection
- 💡 智能修复建议 | Smart fix suggestions

---

### 📊 开发者能力中心 | Developer Competency Hub

- 📈 CI 指数 - 综合能力评分 | CI Index - comprehensive competency score
- 🎯 能力雷达图 - 多维度可视化 | Competency radar - multi-dimensional visualization
- 📊 成长追踪 - 能力提升时间线 | Growth tracking - improvement timeline

---

## 📦 安装 | Installation

### 系统要求 | System Requirements

| 项目 Item | 要求 Requirement |
|----------|-----------------|
| VS Code | ^1.70.0 |
| 操作系统 OS | Windows / macOS / Linux |
| 内存 Memory | 最低 512 MB 可用 |
| 磁盘 Disk | 50 MB 可用空间 |

### 离线安装 | Offline Installation

1. 下载 `flowprompt-studio-1.0.0-full.vsix`
2. VS Code 中按 `Ctrl+Shift+P`
3. 选择 `Extensions: Install from VSIX...`
4. 选择下载的文件

---

## 🚀 快速开始 | Quick Start

### 第一步：打开工作台 | Step 1: Open Workbench

点击左侧活动栏的 FlowPrompt Studio 图标，或按 `Ctrl+Shift+P` → `FlowPrompt: Open Engineering Prompt Workbench`

Click the FlowPrompt Studio icon in the activity bar, or press `Ctrl+Shift+P` → `FlowPrompt: Open Engineering Prompt Workbench`

### 第二步：填写 5 步表单 | Step 2: Complete the 5-Step Form

按照引导填写每个步骤，系统会实时评分并提示你补充缺失信息。

Fill in each step as guided. The system scores in real-time and prompts you to fill in missing information.

### 第三步：生成并发送 | Step 3: Generate & Send

点击 `Generate Prompt` 生成提示词，确认无误后点击 `Send to Trae CN`。

Click `Generate Prompt` to create your prompt, then click `Send to Trae CN` when ready.

---

## 💡 使用场景 | Use Cases

### 场景 1：明确模糊需求 | Clarifying Vague Requirements

**问题 | Problem:**  "我想做个用户系统" → AI 不知道你要什么

**解决 | Solution:** 
- 表单引导你思考：用户类型？登录方式？权限系统？
- 生成完整需求文档，AI 一次理解到位

---

### 场景 2：解决复杂 Bug | Solving Complex Bugs

**问题 | Problem:** 报错信息发给 AI，AI 给通用方案，不适用你的项目

**解决 | Solution:**
- 记录你已尝试的方案（避免重复建议）
- 说明技术栈和约束条件
- AI 给出针对性解决方案

---

### 场景 3：代码审查 | Code Review

**问题 | Problem:** 写完代码不知道有没有问题

**解决 | Solution:**
- 实时分析代码结构和潜在问题
- 给出具体修复建议
- 支持 10 种编程语言

---

## 🐛 已知问题 | Known Issues

### 可选语言需手动安装 | Optional Languages Require Manual Install

C#、C++、Rust 支持需要额外安装：  
C#, C++, Rust support requires additional installation:

```bash
npm install tree-sitter-c-sharp  # C# 支持
npm install tree-sitter-cpp      # C++ 支持  
npm install tree-sitter-rust     # Rust 支持
```

> 原因：使用频率较低，默认不包含以减少体积  
> Reason: Lower usage frequency, excluded by default to reduce bundle size

### ONNX AI 校准默认关闭 | ONNX AI Calibration Disabled by Default

如需启用，安装：  
To enable, install:

```bash
npm install onnxruntime-node
```

> 原因：ONNX 运行时 210 MB，体积过大  
> Reason: ONNX runtime is 210 MB, too large for default inclusion

---

## 🗺️ 路线图 | Roadmap

- [ ] 更多语言支持 (Ruby, PHP, Swift)
- [ ] 本地 AI 模型部署支持
- [ ] 云端同步（可选）
- [ ] 团队协作功能
- [ ] 自定义表单模板

---

## 📄 许可证 | License

[![License](https://img.shields.io/github/license/2sellyogurt/FlowPrompt-Studio)](https://github.com/2sellyogurt/FlowPrompt-Studio/blob/main/LICENSE)
[![Stars](https://img.shields.io/github/stars/2sellyogurt/FlowPrompt-Studio)](https://github.com/2sellyogurt/FlowPrompt-Studio/stargazers)
[![Release Downloads](https://img.shields.io/github/downloads/2sellyogurt/FlowPrompt-Studio/v1.0.0/total?label=v1.0.0%20downloads)](https://github.com/2sellyogurt/FlowPrompt-Studio/releases/tag/v1.0.0)

---

## 📦 技术规格 | Technical Specifications

**包体积优化 | Bundle Optimization:**
- 当前体积：12.94 MB
- 优化幅度：85.7% (从 90.82 MB 压缩到 12.94 MB)
- 优化措施：移除开发依赖、企业功能，压缩原生模块

**内置语言支持 | Built-in Language Support:**
✅ JavaScript / TypeScript / Python / Java / Go  
⚠️ C# / C++ / Rust（需手动安装）
