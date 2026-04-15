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

### 🛠️ 兴趣与相关作品

*   🚀 **Prism — 高性能协程代理引擎** (主项目)
    *   [Prism](https://github.com/Hatedatastructures/Prism.git) : 基于 `C++23` 纯协程架构的服务端代理引擎，PMR 内存池实现热路径零堆分配。
        *   **架构**：`co_await` 全异步无回调 + Per-worker 独占 `io_context` 无锁设计，吞吐量随 CPU 核心线性扩展。
        *   **五协议**：HTTP (正向代理 / CONNECT 隧道)、SOCKS5 (RFC 1928 TCP+UDP)、Trojan (TLS + SHA224)、VLESS (UUID 认证)、SS2022 (AEAD + BLAKE3 密钥派生)，支持首包协议自动嗅探 + TLS 透明剥离。
        *   **伪装层**：Reality TLS 指纹伪装，X25519 密钥交换，可叠加任意内层协议。
        *   **多路复用**：smux v1 / yamux 流控复用，兼容 Mihomo 内核客户端。
        *   **网络栈**：Happy Eyeballs (RFC 8305) 多 IP 竞速、七级 DNS 管线 (UDP/TCP/DoT/DoH + 缓存 + 规则)、加权负载均衡 + 过载反压。
        *   **连接池**：线程级连接复用 + 健康检查 + 自动回收。

*   📦 **自定义库 (手工核心)**
    *   [Custom-libraries](https://github.com/Hatedatastructures/Custom-libraries.git) : 从零构建的高性能基础库集合，以此磨练对底层原理的极致掌控。
        *   🛠️ **容器 (STL 风格)**: **纯手工实现**的标准容器库，接口设计对齐 STL 标准。
            *   **序列容器**: `Vector`, `List`, `Deque`, `String`, `Queue`
            *   **关联容器**: `RBTree` (红黑树), `AVLTree`, `HashMap` (哈希表)
            *   **工具容器**: `PriorityQueue` (优先级队列), `Bitmap` (位图)
        *   ⚡ **并发模块**: 线程安全的数据结构封装与并发基元。
        *   ⚙️ **调度器**: 支持动态扩缩容的任务调度器与线程池模板。
        *   🕸️ **网络模块**: 基于 `Boost.Asio` 封装的高效会话管理与协议处理组件。

*   💻 **算法与练习**
    *   [question](https://github.com/Hatedatastructures/question.git) : 数据结构与算法修炼场。
        *   覆盖 `LeetCode` 高频题解，注重边界处理与代码鲁棒性，沉淀通用的解题范式。

*   🧩 **其他语言练习**
    *   [CodeLab-MultiLang](https://github.com/Hatedatastructures/CodeLab-MultiLang.git) : 多语言技术栈的试验田。
        *   记录 `C`, `Go`, `Python` 等语言在后端场景下的特性探索与 Demo 实现，保持对不同技术栈的敏锐度。

---

<p align="center">
  Building <a href="https://github.com/Hatedatastructures/Prism">Prism</a> with <code>C++23</code> · Coroutine-First · Zero Alloc
</p>
