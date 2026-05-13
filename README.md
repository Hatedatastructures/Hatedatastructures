<!-- <p align="center">
  <img src="github-metrics.svg" alt="Metrics" width="100%">
</p> -->

<h1 align="center">Hi 👋, I'm Frieren</h1>
<h3 align="center">C++ Mage & Backend Engineer</h3>

<p align="center">
  <em> Core C++ · Polyglot (C / Go / Python) · System Architecture</em>
</p>

<p align="center">
  <em> Currently a pure backend developer </em>
</p>

---

### 🛠️ 项目

*   🚀 **[Prism](https://github.com/Hatedatastructures/Prism.git)** — 高性能协程代理网关
    C++23 纯协程架构，PMR 内存池热路径零堆分配，per-worker 独占 `io_context` 无锁设计。
    *   **协议**：HTTP / SOCKS5 / Trojan / VLESS / SS2022，首包自动嗅探 + TLS 透明剥离
    *   **伪装与复用**：Reality TLS 指纹伪装 + smux/yamux 流控复用，兼容 Mihomo 客户端
    *   **网络栈**：Happy Eyeballs 多 IP 竞速、七级 DNS 管线、加权负载均衡、线程级连接池

*   📚 **[PrismWiki](https://github.com/Hatedatastructures/PrismWiki.git)** — Prism 项目知识库
    Obsidian 格式的完整技术文档，基于 Prism C++ 源码分析撰写，67 个文档页面。
    *   **模块**：agent / channel / crypto / memory / multiplex / protocol / pipeline / stealth 等 16 个核心模块
    *   **协议**：HTTP / SOCKS5 / Trojan / VLESS / Shadowsocks 2022，协议格式与实现细节
    *   **伪装**：Reality / ShadowTLS / Restls / AnyTLS / TrustTunnel / ECH 深度分析
    *   **周边**：mihomo 客户端对接、性能基准、调试排障、开发笔记
    
*   🤖 **[Nexus](https://github.com/Hatedatastructures/Nexus.git)** — 自进化 AI 代理运行时
    Go 实现的 AI Agent 框架，支持多 LLM 后端与丰富的工具生态。
    *   **多后端**：OpenAI / Anthropic / Gemini / AWS Bedrock，28+ 内置工具
    *   **消息网关**：Telegram / Discord / Slack / WhatsApp / 微信 / 飞书 / 钉钉
    *   **能力**：MCP 协议集成、子代理委派、上下文压缩、Prompt 注入防护、凭证池

*   📦 **[Custom-libraries](https://github.com/Hatedatastructures/Custom-libraries.git)** — 高性能基础库集合 (wan)
    C++20 头文件为主的基础组件库，重构为 `wan` 统一库，`#include "wan.hpp"` 一站式引入。
    *   **容器**：模拟实现 STL (vector/list/map/set/queue/tree 等)，接口一致可替换
    *   **并发**：标准容器的线程安全封装 (`concurrent_vector` 等)，读共享写独占，支持只读快照
    *   **调度**：线程池 + 动态扩缩容 + 多策略队列 (FIFO/优先级/自适应)，任务编排与健康监控
    *   **网络**：Boost.Asio 异步 I/O，TCP/SSL 会话管理，HTTP/HTTPS 代理转发，对称/非对称加密封装


---

<p align="center">
  Building <a href="https://github.com/Hatedatastructures/Prism">Prism</a> with <code>C++23</code> · Coroutine-First · Zero Alloc
</p>
