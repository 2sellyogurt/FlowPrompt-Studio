🎉 Initial Public Release
We are pleased to announce the official release of FlowPrompt Studio 1.0.0!
This is the first public version, featuring a complete engineering prompt workflow, deep integration with Trae CN, a code auditing engine, and a developer competency assessment system.
Core Philosophy: Make prompting more professional, make AI understand you better
✨ Key Features
🎯 Engineering Prompt Workbench
Guide developers through structured engineering prompting via a 5‑step form:
Context – Project type, tech stack, problem background
Troubleshooting Log – Record attempted solutions and outcomes
Core Problem Definition – Precisely define the core issue
Acceptance Criteria – Measurable success metrics
Functional/Technical Boundaries – Define scope and constraints
Highlights:
📊 Real‑time quality score (100‑point scale)
💾 Auto‑save & drafts (AES‑256 encrypted)
✅ One‑click standardized prompt generation
🔄 Real‑time input validation
🤖 Deep Trae CN Integration
Seamless connectivity with the Trae CN AI assistant:
🔍 Auto‑detect – Identify Trae CN installation status and version
🚀 One‑click send – Dispatch prompts directly to Trae CN
📝 Context sync – Maintain conversation continuity
🎨 Prompt formatting – Optimize format for Trae CN
🌐 Multi‑AI support – Compatible with Copilot, Cursor, etc.
🔍 Code Auditing Engine
Deep code analysis powered by Tree‑sitter:
🌳 AST analysis – Precise code structure & pattern recognition
🌍 10 languages supported – JavaScript/TypeScript/Python/Java/Go/C#/C++/Rust, etc.
⚠️ Real‑time issue detection – Code style, potential bugs, performance
💡 Smart fixes – Actionable remediation suggestions
📊 Issue categorization – Severity‑based prioritization
📊 Developer Competency Hub
Comprehensive engineering capability assessment:
📈 CI Index – Holistic engineering competency score
🎯 Competency Radar – Multi‑dimensional capability visualization
📊 Growth tracking – Capability improvement timeline
💪 Personalized coaching – Targeted improvement plans
🏆 Milestone system – Key achievement tracking
📦 Technical Specifications
System Requirements
表格
Item	Requirement
VS Code	^1.70.0
OS	Windows / macOS / Linux
Memory	Min. 512 MB available
Disk	50 MB free space
Bundle Optimization
plaintext
Current: 12.94 MB
Optimization: 85.7% (from 90.82 MB to 12.94 MB)
Optimizations:
✅ Removed dev dependencies (TypeScript, ESLint, Babel, etc.)
✅ Removed enterprise features (security audit, license management)
✅ Optimized dependency graph (core + optional)
✅ Compressed native modules
Language Support
Built‑in (included):
✅ JavaScript
✅ TypeScript
✅ Python
✅ Java
✅ Go
Optional (manual install required):
⚠️ C# – npm install tree-sitter-c-sharp
⚠️ C++ – npm install tree-sitter-cpp
⚠️ Rust – npm install tree-sitter-rust
Offline Installation
Download flowprompt-studio-1.0.0-full.vsix from this release
In VS Code, press Ctrl+Shift+P
Select Extensions: Install from VSIX...
Choose the downloaded file
📖 Getting Started
First Launch
1. Open the Workbench
Click the FlowPrompt Studio icon in the activity bar
Or press Ctrl+Shift+P → FlowPrompt: Open Engineering Prompt Workbench
2. Complete the 5‑step Form
plaintext
Step 1/5: Context
- Project type (Web frontend/backend/mobile, etc.)
- Tech stack (React, Vue, Spring Boot, etc.)
- Detailed problem background

Step 2/5: Troubleshooting Log
- Add attempted solutions
- Record outcome (success/failure)
- Paste error logs & stack traces

Step 3/5: Core Problem Definition
- One‑sentence core issue
- Constraints (performance, compatibility, etc.)

Step 4/5: Acceptance Criteria
- Measurable success metrics
- Example: Response time < 200ms, 1000 concurrent users

Step 5/5: Functional/Technical Boundaries
- Inclusions/exclusions
- Technical limits (browser versions, Node versions, etc.)
3. Generate the Prompt
Click Generate Prompt
Review the standardized output
Manually edit if needed
4. Send to AI
Click Send to Trae CN
Trae CN opens automatically with your prompt
Start your AI‑powered workflow
💡 Use Cases
1. Clarifying Vague Requirements
You have an idea but struggle to describe it clearly
✅ 5‑step form guides structured thinking
✅ Real‑time prompts for missing information
✅ Auto‑generate structured requirements
2. Breaking Down Complex Problems
Complex issues lead to AI misunderstanding
✅ Enforce complete context
✅ Avoid redundant attempts via troubleshooting log
✅ Reduce ambiguity with clear acceptance criteria
3. Streamlining AI Conversations
Inefficient back‑and‑forth with AI
✅ Provide full context upfront
✅ Standardized format improves AI comprehension
✅ Minimize follow‑up questions
4. Real‑time Code Auditing
Identify potential issues while coding
✅ Live code quality analysis
✅ Actionable fix suggestions
✅ Support for 10 programming languages
5. Developer Growth Tracking
Measure and improve your engineering skills
✅ Objective CI Index assessment
✅ Visual growth trajectory
✅ Personalized improvement recommendations
🐛 Known Issues
Minor
C#/C++/Rust require manual installation
Reason: Lower usage frequency; optional to reduce bundle size
Fix: Install dependencies as needed
bash
运行
npm install tree-sitter-c-sharp  # C# support
npm install tree-sitter-cpp      # C++ support
npm install tree-sitter-rust     # Rust support
ONNX AI calibration disabled by default
Reason: ONNX runtime is 210 MB
Impact: Calibration uses pure‑JS fallback
Fix: Install on demand
bash
运行
npm install onnxruntime-node
Roadmap
 Add more languages (Ruby, PHP, Swift)
 Local AI model deployment support
 Cloud sync (optional)
 Team collaboration features
 Custom form templates




[![License](https://img.shields.io/github/license/2sellyogurt/FlowPrompt-Studio)](https://github.com/2sellyogurt/FlowPrompt-Studio/blob/main/LICENSE)
[![Stars](https://img.shields.io/github/stars/2sellyogurt/FlowPrompt-Studio)](https://github.com/2sellyogurt/FlowPrompt-Studio/stargazers)
[![Release Downloads](https://img.shields.io/github/downloads/2sellyogurt/FlowPrompt-Studio/v1.0.0/total?label=v1.0.0%20downloads)](https://github.com/2sellyogurt/FlowPrompt-Studio/releases/tag/v1.0.0)
---
