# Java + Python AI 应用开发学习仓库（备战 2027 金三银四）

本仓库记录完整学习过程：每周代码、学习笔记/博客、算法练习与项目实战，按 P0 → P1 → P2 优先级推进。配套飞书「督学」在线文档记录学习计划与进度（链接见协作说明）。

## 一、学习主线（目标导向，最重要的先学深）

- **P0 保命层（最先最深，不可压缩）**：Java 基础（集合/并发/JVM）→ MySQL → Redis → 消息队列 → SpringBoot/MyBatis 与 Spring Cloud 核心 → Git/Linux/Docker → 算法 Hot100 → 项目 J1（金融业务后端：状态机/幂等/缓存/MQ）。
- **P1 差异化层（P0 达基线后立即上）**：Spring AI、LangChain4j/LangGraph4j、RAG 全链路、Agent、向量检索（pgvector/Milvus/ES）、Python FastAPI 辅助、金融三性基础 → 项目 J2（Java×AI 的 RAG 重构）。
- **P2 弹性层（出简历初版后按目标 JD 灵活补）**：微服务深化、金融三性深化、需求工程、旗舰项目 J3、RAGAS/vLLM/Dify 等。

关键时间门：2026-11 月下旬完成 P0（具备 Java 后端就业兜底）；2027-01 上旬出简历初版并对照 JD 查漏；2027-02 下旬—04 金三银四投递。

## 二、目录结构

| 目录 | 内容 |
|---|---|
| `p0-java-core/` | P0：Java 基础/并发/JVM、MySQL、Redis、MQ、Spring、微服务核心的练习与小实验 |
| `p1-java-ai/` | P1：Spring AI / LangChain4j、RAG、Agent、向量检索相关代码 |
| `projects/` | 项目 J1（Java 业务后端）、J2（Java×AI RAG）、J3（旗舰，弹性） |
| `leetcode/` | 算法刷题，按题型分目录，题号-题名命名 |
| `notes/` | 每周至少一篇学习总结/博客（较大知识点学完即输出） |
| `weekly/` | 每周计划与复盘（Wxx.md） |

## 三、提交与命名规范

- 提交信息：`feat(p0-jvm): GC 与内存区域练习` / `fix(projects/j1): 幂等拦截` / `docs(notes): W6 MySQL MVCC 总结`，格式 `type(scope): 中文说明`。
- 练习代码必须本人可独立复现；重点内容需有「闭卷复写」版本（目录内以 `closed-book/` 标注）。
- 每个较大知识点完成后，在 `notes/` 输出一篇总结（原理 + 自己的话 + 踩坑 + 面试追问）。
- 每周日在 `weekly/Wxx.md` 写复盘：计划 vs 实际、产出、达标自测、提前/落后、下周计划。

## 四、当前进度（概要，明细以飞书进度文档为准）

- 已掌握：Python 核心/OOP、SQL（CRUD/JOIN/子查询/CTE）。
- 进行中：P0 阶段 A（Java 内核 + 工程地基）。
