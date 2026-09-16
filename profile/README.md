# Java AI 实战派 · java-ai-in-action

> Java 工程师转 AI 应用开发的实战派阵地。10 篇长文配套代码仓库，每篇一个子仓，含一键 docker-compose 启动、真实业务数据、踩坑清单。
>
> **不写 Python 入门，不写 ChatGPT 科普。** 配套公众号「Java AI 实战派」不定时更新。

---

## 📚 系列目录（篇序即阅读顺序）

| 篇序 | 文章 | 代码仓库 | 状态 |
|---|---|---|---|
| 篇1 | 干了 13 年 Java，AI 时代我不是被淘汰，而是被重新定价 | roadmap | ✅ |
| 篇2 | Spring AI vs LangChain4j vs Spring AI Alibaba：2026 终极选型指南 | **framework-compare** | ✅ |
| 篇3 | Spring AI 2.0 GA 实战：从 0 到 1 搭建企业级 ChatClient | spring-ai-2-in-action | 🚧 规划中 |
| 篇4 | RAG 准确率从 32% 干到 89%：重写切片、混合检索与 Rerank | rag-in-action | 🚧 规划中 |
| 篇5 | 把 Spring AI 的 @Tool 一键暴露成 MCP Server | mcp-in-action | 🚧 规划中 |
| 篇6 | 我用 Spring AI Alibaba + Nacos 搭了个企业级 Multi-Agent | multi-agent-in-action | 🚧 规划中 |
| 篇7 | 别把 Agent 绑死在一个模型上：多模型路由与故障转移 | model-routing-in-action | 🚧 规划中 |
| 篇8 | 我的 AI Agent 半夜偷偷花了 3000 块 | observability-in-action | 🚧 规划中 |
| 篇9 | 上线 AI 客服 30 天，我们被薅了 12 万羊毛 | ai-security-in-action | 🚧 规划中 |
| 篇10 | 33 岁 Java 后端转 AI 应用开发，第 7 个月副业月入 4 万 | roadmap（更新） | 🚧 规划中 |

---

## 🚀 快速开始（以 framework-compare 为例）

```bash
git clone https://github.com/java-ai-in-action/framework-compare.git
cd framework-compare

# 1. 一键启动向量库等基础设施
docker-compose up -d

# 2. 配置你的 API Key（任选一家）
export SPRING_AI_OPENAI_API_KEY=sk-xxx
# 或 DEEPSEEK_API_KEY / DASHSCOPE_API_KEY

# 3. 跑任意一个 quickstart
cd spring-ai-quickstart && mvn spring-boot:run
```

---

## 🎯 每个仓库的标配

- **README**（中英双语，含架构图 + 快速开始）
- **docker-compose.yml**（一键起依赖：pgvector / Qdrant / Redis 8 等）
- **GitHub Actions CI**（push 自动跑测试）
- **压测 / 评估脚本**（benchmarks/ 目录）
- **踩坑清单**（每个仓库 README 的「Known Pitfalls」一节）

## 🧭 阅读路径

- 🟢 刚听说 AI 的 Java 工程师：先看篇1 文章 + `roadmap` 仓库
- 🟡 已经在写 AI 代码：直接进篇3 / 篇4 对应仓库
- 🔵 技术 Leader / 架构师：篇6 / 篇7 / 篇8 / 篇9 四件套
- 🟣 想转型的老 Java：篇1 + 篇10

## 📮 联系

- 公众号：**Java AI 实战派**（不定时更新，想发就发）
- Issue：任何仓库欢迎提 Issue，看到就回

## License

MIT
