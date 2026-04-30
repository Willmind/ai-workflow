---
theme: default
title: mix_fe_plus 的 AI 探索与工作流实践
info: |
  mix_fe_plus（Vue 3.5 + TS + Vite）AI 工作流分享（20–30 分钟版）
layout: cover
class: cover-slide
css: styles.css
---

<div class="cover-shell">
  <div class="cover-copy">
    <div class="eyebrow">AI WORKFLOW PRACTICE</div>
    <h1>mix_fe_plus 的 AI 探索与工作流实践</h1>
    <p class="cover-lead">把「需求 → 澄清 → 计划 → 实现 → 审查 → 提交」变成可重复、可审计、可复用的交付流程。</p>
    <div class="cover-chip-row">
      <span class="ai-toolchain-badge"><span class="dot"></span>superpowers / OpenSpec / Project Rules / AI Commit / Figma MCP</span>
    </div>
    <div class="cover-metrics">
      <span>20–30 分钟</span>
      <span>Vue 3.5 + TS + Vite</span>
      <span>流程化分享</span>
    </div>
  </div>
  <div class="cover-rail">
    <div class="cover-card primary">
      <div class="cover-card-title">交付链路</div>
      <div class="cover-card-steps">clarify → plan → spec → code → review → commit</div>
    </div>
    <div class="cover-focus">
      不是炫工具，而是沉淀一套 Cursor / Codex 都能复用的流程
    </div>
  </div>
</div>

<!--
口播（30s）：
- 今天不做“炫技”，讲的是我们怎么把 AI 变成流程
- 目标是交付更快，同时可控、可复用
-->

---
layout: default
class: pain-slide
---

## 1. 背景：效率卡在哪

<div class="hero-intro">
  <div class="eyebrow">WHY NOW</div>
  <div class="hero-copy">问题不是“代码写得慢”，而是流程里有太多反复确认和上下文切换。</div>
</div>

<div class="feature-grid three">
  <div class="feature-card tint-violet">
    <div class="feature-kicker">01</div>
    <div class="feature-title">需求澄清</div>
    <div class="feature-body">理解偏差导致返工，方案常常做到一半才发现前提不一致。</div>
  </div>
  <div class="feature-card tint-blue">
    <div class="feature-kicker">02</div>
    <div class="feature-title">上下文切换</div>
    <div class="feature-body">查文档、找接口、对齐设计来回切，开发节奏被不断打断。</div>
  </div>
  <div class="feature-card tint-green">
    <div class="feature-kicker">03</div>
    <div class="feature-title">Review & 收尾</div>
    <div class="feature-body">检查遗漏、写提交信息、补验收动作，最后一公里最容易松散。</div>
  </div>
</div>

<div class="statement-panel">
  <span class="statement-dot"></span>
  提效不靠“更快敲代码”，而是减少返工、减少沟通成本、减少漏项。
</div>

<!--
口播（1min）：
- 这些问题都不是“能力问题”，是流程问题
- 所以我们做的是：把关键步骤流程化，让 AI 帮忙“做规范动作”
-->

---
layout: default
class: principles-slide
---

## 2. 目标与原则：快，但要可控

<div class="two-panel">
  <div class="goal-panel">
    <div class="eyebrow">GOAL</div>
    <div class="goal-title">交付更快</div>
    <div class="goal-body">探索更短、返工更少、收尾更快。</div>
    <div class="metric-strip">
      <span>探索更短</span>
      <span>返工更少</span>
      <span>收尾更快</span>
    </div>
  </div>
  <div class="principles-panel">
    <div class="principle-item">
      <div class="principle-index">01</div>
      <div>
        <div class="principle-title">可重复</div>
        <div class="principle-body">新人照着流程走，也能产出一致结果。</div>
      </div>
    </div>
    <div class="principle-item">
      <div class="principle-index">02</div>
      <div>
        <div class="principle-title">可审计</div>
        <div class="principle-body">为什么这样做、改了什么，之后都能回看。</div>
      </div>
    </div>
    <div class="principle-item">
      <div class="principle-index">03</div>
      <div>
        <div class="principle-title">可控风险</div>
        <div class="principle-body">敏感信息、质量门禁、权限边界都要有护栏。</div>
      </div>
    </div>
  </div>
</div>

<!--
口播（1min）：
- “快”是结果，不是手段；手段是流程
- 接下来用一张图把工具链放到同一条链路上
-->

---
layout: default
class: overview-slide
---

## 3. 工具链全景（把 AI 变成流水线）

<div class="hero-intro">
  <div class="eyebrow">OVERVIEW</div>
  <div class="hero-copy">把工具放回交付链路里理解：从需求澄清、规范沉淀，到编码、评审、提交，每个环节都有不同的协作重点。</div>
</div>

<div class="overview-grid">
  <div class="overview-card violet">
    <div class="overview-index">01</div>
    <div class="overview-title">superpowers</div>
    <div class="overview-body">把探索 / 计划 / 验证结构化，先把问题想清楚。</div>
  </div>
  <div class="overview-card green">
    <div class="overview-index">02</div>
    <div class="overview-title">OpenSpec</div>
    <div class="overview-body">接口规范驱动，减少对齐成本和字段理解偏差。</div>
  </div>
  <div class="overview-card blue">
    <div class="overview-index">03</div>
    <div class="overview-title">Project Rules</div>
    <div class="overview-body">把项目规范变成 AI 的默认行为，减少风格漂移和执行偏差。</div>
  </div>
  <div class="overview-card cyan">
    <div class="overview-index">04</div>
    <div class="overview-title">AI Commit</div>
    <div class="overview-body">把收尾动作自动化，让提交信息和历史更稳定。</div>
  </div>
  <div class="overview-card mint">
    <div class="overview-index">05</div>
    <div class="overview-title">Figma MCP</div>
    <div class="overview-body">设计上下文直连实现建议，减少来回确认。</div>
  </div>
</div>

<div class="statement-panel" style="margin-top: 1rem">
  <span class="statement-dot"></span>
  这 5 个点不是并列的“工具”，而是一条开发链路上的 5 个站点。
</div>


<!--
口播（2min）：
- 这 5 个点不是并列的“工具”，而是一条链路上的“站点”
- 下一步我们从“需求文档扔进去”开始讲真实流程
-->

---
layout: center
class: toolchain-visual-slide
---

<img src="/toolchain.svg" alt="AI 工具链全景图" class="toolchain-visual" />

<!--
口播（30s）：
- 这一页只看全景图，不讲细节
- 从左到右是一条链路：输入上下文 → 探索计划 → 规范对齐 → 编码护栏与收尾 → 设计对齐
-->

---
layout: default
class: impact-slide token-slide
---

## 4. 先用比喻记住：一个帮你想清楚，一个帮你写清楚

<div class="feature-grid three">
  <div class="feature-card tint-violet">
    <div class="feature-kicker">superpowers</div>
    <div class="feature-title">像开工前的任务教练</div>
    <div class="feature-body">先陪你把任务理解清楚、顺序排清楚、风险看清楚，再决定怎么做。</div>
  </div>
  <div class="feature-card tint-green">
    <div class="feature-kicker">OpenSpec</div>
    <div class="feature-title">像共享说明书框架</div>
    <div class="feature-body">把需求、接口、边界条件写进一份后面还能继续复用的结构化说明里。</div>
  </div>
  <div class="feature-card tint-blue">
    <div class="feature-kicker">结论</div>
    <div class="feature-title">一个帮你想清楚，一个帮你写清楚</div>
    <div class="feature-body">两者分工不同：superpowers 管流程推进，OpenSpec 管规范沉淀。</div>
  </div>
</div>

<div class="statement-panel">
  <span class="statement-dot"></span>
  superpowers 负责把事情想清楚，OpenSpec 负责把需求和接口写清楚。
</div>

<!--
口播（1min）：
- 这页的目标是让第一次听的人 10 秒内记住这两个角色
- 你只要记住一句话：一个帮你想清楚，一个帮你写清楚
-->

---
layout: default
class: prompt-example-slide
---

## 5. 真实需求示例：先澄清，再整理成结构化说明

<div class="prompt-card-grid">
  <div class="prompt-card primary">
    <div class="feature-kicker">开场约束</div>
    <div class="feature-title">请先不要直接写代码</div>
    <div class="feature-body">先按“先澄清、再计划、再验证”的方式处理，然后再整理成结构化说明。</div>
  </div>
  <div class="prompt-card">
    <div class="feature-kicker">需求背景</div>
    <div class="feature-title">【环境管理】列表页优化</div>
    <div class="feature-body">当前列表页无法直接看到浏览器环境的 WebRTC 配置，希望减少进入新增 / 编辑页查看的成本。</div>
  </div>
  <div class="prompt-card">
    <div class="feature-kicker">改动要求</div>
    <ul>
      <li>表头【名称】后新增【WebRTC】列</li>
      <li>数据来源于新增 / 编辑浏览器的 WebRTC 字段</li>
      <li>使用项目现有 i18n 翻译文案</li>
      <li>尽量不影响现有列表布局和交互</li>
    </ul>
  </div>
  <div class="prompt-card">
    <div class="feature-kicker">验收标准</div>
    <ul>
      <li>列位置在【名称】之后</li>
      <li>每行展示对应 WebRTC 字段值</li>
      <li>文案不写死，接入现有 i18n</li>
      <li>不影响渲染、分页、筛选和其他交互</li>
    </ul>
  </div>
  <div class="prompt-card wide">
    <div class="feature-kicker">要求 AI 先输出</div>
    <div class="prompt-chip-row">
      <span>澄清问题</span>
      <span>实施计划</span>
      <span>主要风险点</span>
      <span>验证和回归清单</span>
      <span>结构化说明</span>
    </div>
  </div>
</div>

<!--
口播（1min）：
- 这页就是现场可以直接贴进去的 prompt
- 重点是“先不要写代码”，先让 AI 帮我们把需求变成可执行输入
-->

---
layout: default
class: impact-slide
---

## 6. superpowers：真实需求里的第一轮产出

<div class="feature-grid three">
  <div class="feature-card tint-violet">
    <div class="feature-kicker">澄清</div>
    <div class="feature-title">先把问题问出来</div>
    <div class="feature-body">比如：WebRTC 展示原始值还是翻译标签？空值显示什么？接口是否已返回？</div>
  </div>
  <div class="feature-card tint-blue">
    <div class="feature-kicker">计划</div>
    <div class="feature-title">再把实施步骤排出来</div>
    <div class="feature-body">先找列表列定义，再确认字段映射，再处理 i18n 和空值兜底，最后做自测。</div>
  </div>
  <div class="feature-card tint-green">
    <div class="feature-kicker">风险 / 验证</div>
    <div class="feature-title">最后把回归点列出来</div>
    <div class="feature-body">自定义列兼容、多语言、空值显示、分页筛选不受影响，都要提前放进 checklist。</div>
  </div>
</div>

<div class="statement-panel">
  <span class="statement-dot"></span>
  superpowers 的核心价值，是先产出“问题清单 + 计划 + 风险 + 验证项”，再进入编码。
</div>

<!--
口播（1min）：
- 这一页最好结合刚才的 WebRTC 小需求讲
- 让听众知道它不是抽象概念，而是第一轮就能产出非常实用的中间物
-->

---
layout: center
class: toolchain-visual-slide
---

<div class="visual-frame">
  <img src="/superpowers-first-output.svg" alt="superpowers 第一轮产出示意图" class="toolchain-visual" />
</div>

---
layout: default
class: impact-slide
---

## 7. OpenSpec：真实需求里的规范沉淀

<div class="feature-grid three">
  <div class="feature-card tint-green">
    <div class="feature-kicker">背景</div>
    <div class="feature-title">为什么要改</div>
    <div class="feature-body">环境管理列表页看不到 WebRTC，需要进入编辑页查看，查询成本高。</div>
  </div>
  <div class="feature-card tint-blue">
    <div class="feature-kicker">规则</div>
    <div class="feature-title">把实现约束写清楚</div>
    <div class="feature-body">名称后新增列、字段已返回、展示翻译标签、空值为 <code>-</code>、复用现有 i18n。</div>
  </div>
  <div class="feature-card tint-violet">
    <div class="feature-kicker">验收</div>
    <div class="feature-title">把完成标准写清楚</div>
    <div class="feature-body">列出现、位置正确、值正确、影响面可回看，原列表分页筛选不受影响。</div>
  </div>
</div>

<div class="statement-panel">
  <span class="statement-dot"></span>
  OpenSpec 不是增加聊天长度，而是把口头对齐沉淀成可回看的规范输入。
</div>

<!--
口播（1min）：
- 这一页讲完，听众应该能明白：OpenSpec 产出的不是灵感，而是以后还能接着用的变更说明
-->

---
layout: center
class: toolchain-visual-slide
---

<div class="visual-frame">
  <img src="/openspec.svg" alt="OpenSpec 工作流全景图" class="toolchain-visual" />
</div>

---
layout: default
class: process-slide
---

## 8. Project Rules：让规范“默认发生”

<div class="process-layout">
  <div class="process-summary blue">
    <div class="eyebrow">PROJECT RULES</div>
    <div class="process-title">把团队经验，变成 AI 的默认动作。</div>
    <div class="process-body">规则入口可以很简单。Cursor 可以放在 `.cursor/rules/*.mdr`，Codex 可以沉淀到 `AGENTS.md` 或仓库说明里；关键不是放哪，而是把“大家平时口头提醒的事”固化成默认约束。</div>
    <div class="process-highlight">规则把经验变成默认行为，减少返工。</div>
  </div>
  <div class="process-steps">
    <div class="process-step">
      <div class="process-index">01</div>
      <div>怎么跑项目：`dev / build / lint / precheck`</div>
    </div>
    <div class="process-step">
      <div class="process-index">02</div>
      <div>提交前要做哪些检查</div>
    </div>
    <div class="process-step">
      <div class="process-index">03</div>
      <div>提测前怎么做 AI Review</div>
    </div>
    <div class="process-step">
      <div class="process-index">04</div>
      <div>把“先澄清、再计划、后编码”的顺序写成默认工作流</div>
    </div>
  </div>
</div>

<!--
口播（2min）：
- 这里可以展示一下 `.cursor/rules/workflow.mdr` 的关键段落
- 如果换成 Codex，本质上只是规则载体不同，流程本身不变
- 核心句：规则把“经验”变成“默认行为”，减少返工
-->

---
layout: default
class: impact-slide
---

## 9. Cursor / Codex：方法共用，载体不同

<div class="feature-grid three">
  <div class="feature-card">
    <div class="feature-kicker">共用</div>
    <div class="feature-title">输入上下文</div>
    <div class="feature-body">需求、OpenSpec、设计稿、验收标准，这些在两个工具里完全一致。</div>
  </div>
  <div class="feature-card">
    <div class="feature-kicker">共用</div>
    <div class="feature-title">流程顺序</div>
    <div class="feature-body">先澄清，再计划，再编码，再 review / commit，这一套顺序不依赖工具品牌。</div>
  </div>
  <div class="feature-card">
    <div class="feature-kicker">区别</div>
    <div class="feature-title">规则载体</div>
    <div class="feature-body">Cursor 更像 rules 文件驱动；Codex 更适合仓库说明、命令约定和固定工作流提示。</div>
  </div>
</div>

<div class="statement-panel">
  <span class="statement-dot"></span>
  工具会变，方法可以复用：上下文组织、步骤拆解、验证节奏，才是可以迁移的能力。
</div>

<div class="statement-panel" style="margin-top: 0.8rem">
  <span class="statement-dot"></span>
  superpowers / OpenSpec 更像两类工作方法：一个帮助推进执行，一个帮助沉淀规范，不必绑定到某个固定入口或单一工具链。
</div>

<!--
口播（1min）：
- 这一页是为了回答“换工具怎么办”
- 我们沉淀的是流程，不是某个 IDE 上的肌肉记忆
-->

---
layout: default
class: demo-slide
---

## 10. AI Review：基于 diff，固定结构输出

<div class="demo-layout">
  <div class="demo-command">
    <div class="demo-label">Review 指令</div>
    <pre><code>请基于当前 diff 做一次 review。
按下面结构输出：
1. 改动概括
2. 潜在风险
3. 验证建议
4. 是否还需要补充测试或边界处理</code></pre>
  </div>
  <div class="demo-points">
    <div class="demo-point">
      <div class="demo-point-title">Review 重点</div>
      <ul>
        <li><strong>改动概括</strong>：是什么 / 为什么</li>
        <li><strong>风险点</strong>：bug / 兼容 / 安全 / 可维护性</li>
        <li><strong>验证建议</strong>：怎么验证、要不要补测试、要不要拆分</li>
      </ul>
    </div>
    <div class="demo-note">基于 diff 能减少无关上下文；固定结构能让 review 更稳定。</div>
  </div>
</div>

<!--
口播（1–1.5min）：
- 这页直接展示现场可复制的 review 指令
- 重点是基于 diff 和固定结构，这样输出更稳定，也更省 token
- 若现场输出不理想，直接切录屏；不要现场“调 prompt”
-->

---
layout: default
class: process-slide
---

## 11. 自动 AI Commit：收尾更快、历史更清晰

<div class="process-layout">
  <div class="process-summary cyan">
    <div class="eyebrow">AI COMMIT</div>
    <div class="process-title">解决的不是“写一句话”，而是让历史更清晰。</div>
    <div class="process-body">把 diff 转成结构一致的 commit message，让后续追溯、定位和回看都更省心。</div>
    <div class="process-highlight">对管理：减少流程摩擦。对技术：历史更清晰，排查更快。</div>
  </div>
  <div class="process-steps">
    <div class="process-step">
      <div class="process-index">01</div>
      <div>信息结构一致，遵守 Conventional Commits</div>
    </div>
    <div class="process-step">
      <div class="process-index">02</div>
      <div>基于当前 diff 提炼 scope、type 和 subject</div>
    </div>
    <div class="process-step">
      <div class="process-index">03</div>
      <div>提交前人工确认语义，避免把无关改动写进同一条提交</div>
    </div>
  </div>
</div>

<!--
口播（2min）：
- 对管理：减少流程摩擦，开发更专注
- 对技术：历史更清晰，排查更快
-->

---
layout: default
class: process-slide
---

## 12. Figma MCP：设计进入上下文

<div class="process-layout">
  <div class="process-summary mint">
    <div class="eyebrow">FIGMA MCP</div>
    <div class="process-title">让设计上下文直接进入实现讨论。</div>
    <div class="process-body">价值不是一键生成全部 UI，而是减少来回确认，把设计信息更早、更准地带进开发上下文。</div>
    <div class="process-highlight">设计信息更早进入实现讨论，后续确认成本更低。</div>
  </div>
  <div class="process-steps">
    <div class="process-step">
      <div class="process-index">01</div>
      <div>读取设计上下文：布局 / 组件 / 状态 / 尺寸</div>
    </div>
    <div class="process-step">
      <div class="process-index">02</div>
      <div>提取关键 token：颜色 / 字体 / 间距</div>
    </div>
    <div class="process-step">
      <div class="process-index">03</div>
      <div>输出实现建议：组件结构 / 交互状态 / 边界条件</div>
    </div>
  </div>
</div>

<!--
口播（2min）：
- 强调：MCP 的价值是“减少沟通与反复确认”，不是一键生成全部 UI
-->

---
layout: default
class: impact-slide
---

## 13. 省 token：不是少说话，而是少给无关上下文

<div class="token-compact">
<div class="feature-grid three">
  <div class="feature-card">
    <div class="feature-kicker">习惯 1</div>
    <div class="feature-title">先说目标和约束</div>
    <div class="feature-body">先说明改什么、在哪改、有哪些限制，避免直接贴入全项目上下文。</div>
  </div>
  <div class="feature-card">
    <div class="feature-kicker">习惯 2</div>
    <div class="feature-title">先定位，再展开</div>
    <div class="feature-body">先找相关文件，再按需读取局部代码，减少无关内容进入上下文。</div>
  </div>
  <div class="feature-card">
    <div class="feature-kicker">习惯 3</div>
    <div class="feature-title">一轮只做一件事</div>
    <div class="feature-body">澄清、实现、review、commit 分开做，比一条长 prompt 更省。</div>
  </div>
</div>

<div class="feature-grid three" style="margin-top: 0.75rem">
  <div class="feature-card">
    <div class="feature-kicker">习惯 4</div>
    <div class="feature-title">Review 基于 diff</div>
    <div class="feature-body">实现后直接基于 diff 做 review，避免重新读取整份代码库。</div>
  </div>
  <div class="feature-card">
    <div class="feature-kicker">习惯 5</div>
    <div class="feature-title">规则前置固化</div>
    <div class="feature-body">把长期不变的规范放进 Cursor Rules / AGENTS.md，减少重复输入。</div>
  </div>
  <div class="feature-card">
    <div class="feature-kicker">习惯 6</div>
    <div class="feature-title">话题切换开新线程</div>
    <div class="feature-body">避免无关历史一直累积，减少污染，也更容易聚焦当前任务。</div>
  </div>
</div>

<div class="statement-panel">
  <span class="statement-dot"></span>
  省 token 的关键：少给无关上下文，多给结构化上下文。
</div>
</div>

<!--
口播（1min）：
- 真正省 token 的方法不是“少打一半字”
- 而是先缩小问题，再逐步展开，把重复规则固化掉
-->

---
layout: center
class: ending-slide
---

<div class="ending-shell">
  <div class="eyebrow">THANK YOU</div>
  <h1>把 AI 用成流程，而不只是工具</h1>
  <p class="ending-lead">谢谢。也欢迎一起交流，怎么把 AI 更稳地嵌进团队的日常交付流程。</p>
  <div class="ending-tags">
    <span>clarify</span>
    <span>plan</span>
    <span>spec</span>
    <span>code</span>
    <span>commit</span>
    <span>design</span>
  </div>
  <div class="ending-note">Q&amp;A</div>
</div>
