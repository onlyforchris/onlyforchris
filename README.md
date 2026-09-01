<div align="center">
  <img src="./assets/hello.svg" width="100%" alt="Chris — 做点有用的，留点好玩的。" />
</div>

### 你好，我是 Chris

喜欢把乱糟糟的问题理清楚，再做成顺手的产品和工具。<br />
这里没有固定赛道：工作里遇到真问题，就认真做一个能运行、能验证、能交接的答案。

### 这个月在做什么

<sub>更新于 2026-09-01</sub>

- 重做 [Agent Hub](https://github.com/onlyforchris/agent-hub)：Python、本地浏览器、SQLite 与 MCP，先把可运行边界做实。
- 维护 [DSH IM](https://github.com/onlyforchris/dsh-im) 与 [DSH Timer Agent](https://github.com/onlyforchris/dsh-timer-agent)：把真实故障修进插件和 Release。
- 恢复 [Blog](https://github.com/onlyforchris/blog) 发布：第一批三篇已上线，只写真实工程问题，不写工具清单和概念拼盘。

### 看得见的作品

<a href="https://github.com/onlyforchris/agent-hub">
  <img src="https://raw.githubusercontent.com/onlyforchris/agent-hub/main/docs/agent-hub-overview.png" width="100%" alt="Agent Hub 本地工作区界面" />
</a>

| 作品 | 解决什么 | 当前证据 |
| --- | --- | --- |
| [Agent Hub](https://github.com/onlyforchris/agent-hub) | 在本地组织企业 Agent 工作区，并通过 MCP 接入运行时 | 一条命令启动、真实界面、CI、首个 Release |
| [JD 简历画像匹配](https://github.com/onlyforchris/match-resumes-to-jd) | 从 JD 建立岗位画像，再按证据持续筛选简历 | 独立 Skill、安装说明、最小校验 |
| [WeChat Draft Publisher](https://github.com/onlyforchris/wechat-draft-publisher-skill) | 把 Markdown 安全转换为公众号草稿 | 草稿链路、最后一步人工确认 |
| [Bid Response Production](https://github.com/onlyforchris/bid-response-production) | 生成、审查并规范化中文投标材料 | 独立 Skill、审查规则与文档 |

### 用 HTML 做 Apple 风格 PPT

技术内容我常做成**可放映的幻灯片**，而不是 PPT：一个 HTML 文件，能全屏放映、目录跳页、自动播放。这是一套 Apple 发布会风格的演示：

[![Apple 风格演示预览](assets/apple-ppt-preview.png)](https://onlyforchris.github.io/blog/apple-demo.html)

- 🎞 [在线演示](https://onlyforchris.github.io/blog/apple-demo.html) —— 整套可放映的 Apple 风格 HTML PPT
- 🧩 [Skill：html-ppt-apple-style](https://github.com/onlyforchris/html-ppt-apple-style) —— 一键生成 Apple 发布会风格演示
- 📖 [博客演示目录](https://onlyforchris.github.io/blog/slideshows/) · [怎么用 HTML 写幻灯片](https://onlyforchris.github.io/blog/write-html-slides/)

### 从问题到结果

| 问题 | 没有停在 | 最后落到 |
| --- | --- | --- |
| 接口返回 HTTP 200，但平台业务码失败 | “请求成功” | 业务码判定、脱敏回执、失败测试与 [DSH IM Release](https://github.com/onlyforchris/dsh-im/releases) |
| 中文任务名触发跨平台传输故障 | 改成英文绕过去 | 编码链路修复、回归测试与 [Timer Agent Release](https://github.com/onlyforchris/dsh-timer-agent/releases) |
| 自动化走到不可逆发布步骤 | 让程序替人决定 | 草稿模式、显式确认与可恢复交接 |

### 开源维护线

- [DSH IM](https://github.com/onlyforchris/dsh-im)：9 个聊天渠道接入 DeepSeek Harness。
- [DSH Timer Agent](https://github.com/onlyforchris/dsh-timer-agent)：宿主内定时调度，驱动真实 Agent 会话。

### 最近写什么

[Blog](https://github.com/onlyforchris/blog) 已恢复发布，只写真实工程问题，不把选题冒充文章。这一批发了三篇：

1. [《为什么 200 OK 不等于事情做完了》](https://onlyforchris.github.io/blog/why-200-ok-is-not-done/)
2. [《一个中文任务名引发的跨平台故障》](https://onlyforchris.github.io/blog/chinese-task-name-transport-failure/)
3. [《自动化应该在哪一步停下来让人确认》](https://onlyforchris.github.io/blog/where-to-stop-and-ask-confirmation/)

### 几条小原则

- 结果比演示重要，能用比显得聪明重要。
- 先把事情想清楚，再决定要不要自动化。
- 代码够用、好懂、方便接手，就很好。

<details>
<summary>也写一点代码</summary>
<br />

常用 TypeScript、Python、Java，也会为了一个真实问题临时学点别的。

</details>

---

<div align="center">
  <sub>慢慢做，持续更新。</sub>
</div>
