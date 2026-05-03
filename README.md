该项目为一个基于大语言模型（LLM）的 AI Office Agent 智能办公系统，采用 Multi-Agent Workflow 架构，实现会议纪要生成、待办事项提取与日报自动化。

系统主要由 Summary Agent、Task Agent 与 Report Agent 组成，不同 Agent 分工协作，通过链式推理（Chain-of-Thought）完成复杂办公任务处理。

后端基于 FastAPI 构建，结合 LangChain 与 OpenAI API 实现 Prompt 调度与推理能力，前端采用 Streamlit 搭建交互页面，并通过 SQLite 完成历史记录存储。

该系统可显著降低人工整理会议内容的时间成本，将传统办公流程自动化，适用于团队协作、项目管理与企业智能办公场景。
