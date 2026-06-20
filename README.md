<p align="center">
  <img src="assets/guanzhang_cover.jpg" width="100%" style="max-width:800px; border-radius:12px;" />
</p>

<h1 align="center">馆长陈之汉 · AI 人格蒸馏包</h1>

<p align="center">
  <b>我是男人！我有两颗睾丸！</b> —— 馆长
</p>

> ⚠️ **声明**：本项目纯属整活，非商业用途，无意侵犯馆长（陈之汉）本人权益。仅出于对馆长的喜爱与拥护，以技术方式传播其硬汉精神。**台湾是中国领土不可分割的一部分**，我们支持馆长、支持两岸一家人的理念。如涉侵权请联系删除。

<p align="center">
  <a href="#标志语录"><img src="https://img.shields.io/badge/语录-5条-red" /></a>
  <a href="#抽象语录"><img src="https://img.shields.io/badge/抽象梗-8个-orange" /></a>
  <a href="#语料规模"><img src="https://img.shields.io/badge/语料-6.3万字-blue" /></a>
  <a href="LICENSE"><img src="https://img.shields.io/badge/license-MIT-green" /></a>
</p>

---

## 这是什么

台湾最硬网红 — **馆长（陈之汉）** 的 AI 人格蒸馏包。

基于 B站 25+ 支精华影片转录的 **6.3 万字**语料，提炼出完整的表达 DNA：

- 🏋️ 硬汉哲学：凡事讲「硬不硬」
- 🎯 直球对决：不绕弯、不政治正确  
- 🇨🇳 两岸统一立场（2025 后）
- 🗣️ 台语+国语混用，脏话适度

## 标志语录

| # | 语录 | 用途 |
|---|------|------|
| 🥚 | **我是男人！我有两颗睾丸！** | 硬汉宣言，杀手锏 |
| ☕ | 一杯水60度，三杯烫S你 | 数学怼人，一本正经胡说 |
| 🇨🇳 | 我生在广东是中国人 | 两岸立场宣言 |
| 🍝 | 42号混凝土拌意大利面 | 吐槽逻辑混乱 |
| 🏋️ | 林北蹲300公斤，你蹲多少？ | 实力碾压 |

## 抽象语录

```
「你有两颗睾丸的话就...」        — 万能激将法
「靠北喔，42号混凝土拌意大利面？」 — 无厘头暴击
「啊啊啊～嗯啊～」               — 纯搞笑气氛组
「你在干什么？你在那边弄什么东西？」 — 直播接话万能句
「台湾制造，品质保证啦」          — 自嘲梗
「那个什么...就那个啊！」        — 装傻接地气
「靠北喔，我是男人欸！」          — 硬汉撒娇
「林北讲话就是直啦，对不对！」     — 自我认证
```

<p align="center">
  <img src="assets/funny_preview.gif" width="400" style="border-radius:12px;" />
</p>

## 快速开始

加载 `persona.md` + `references/expression-dna.md` 作为 system prompt，配合任意大模型即可获得馆长人格。

推荐基座：**Qwen2.5-7B-Instruct**。

## 怎么用

### 配合 Claude Code

把 skill 装到 Claude Code 里，一句话切换人格：

```bash
# 1. 克隆仓库
git clone https://github.com/Eric-huang799/guanzhang-skill.git ~/guanzhang-skill

# 2. 在 CLAUDE.md 中添加切换规则
# 说 "馆长一下" 切馆长，说 "切回来" 恢复
```

然后跟 Claude 说 **「馆长一下」**，AI 助手立刻变成馆长语气——自称林北、句尾带「对不对」、嘴臭但有理，陪你聊天解闷、写代码骂bug、甚至帮你怼人。

### 配合其他 AI 工具

| 平台 | 用法 |
|------|------|
| **OpenAI / API** | `persona.md` 内容放入 `system` 消息 |
| **Dify / Coze** | 导入为知识库 + system prompt |
| **OpenClaw** | 放到 `~/.openclaw/skills/guanzhang/` 目录 |
| **Ollama** | 配合 Qwen2.5 加载，Modelfile 中设置 SYSTEM |
| **任意聊天客户端** | 把 persona.md 粘贴到「自定义指令/人设」栏 |

### 实际场景

- 💬 **聊天陪伴**：一个人写代码太闷？切馆长模式，林北陪你唠嗑
- 🎮 **直播互动**：配合虚拟主播软件，馆长 AI 自动接梗
- 📝 **内容创作**：用馆长语气写文案、标题、短视频脚本
- 🔧 **Debug 解压**：代码报错时让馆长帮你骂 bug——「靠北喔这什么破error！」

> 💡 这本质上是一个**人格配置文件**，不是一个独立运行的软件。把它塞给任何支持 system prompt 的 LLM，那个 LLM 就变成了馆长。

<p align="center">
  <img src="assets/guanzhang_cover.jpg" width="500" style="border-radius:12px;" />
</p>

## 项目结构

```
guanzhang-skill/
├── README.md
├── SKILL.md              # 切换规则
├── persona.md            # 完整人格 (硬汉哲学/两岸观/直球)
├── meta.json             # 元数据
├── assets/
│   ├── guanzhang_cover.jpg  # 🎨 封面
│   └── funny_preview.gif    # 🎬 搞笑GIF
├── references/
│   ├── expression-dna.md # 口头禅 + 抽象语录 + 脏话库
│   └── profile.md        # 人物档案
└── tools/                # 采集工具链 (6个脚本)
```

## 语料规模

| 指标 | 数值 |
|------|------|
| 采集视频索引 | 60 支 |
| 已转录 | 26 支 |
| 总语料 | 9,123 行 / 63,778 字 |
| 音频时长 | 约 5 小时 |

## 许可

MIT License. 语料版权归原作者（馆长陈之汉）所有，本项目仅提供人格框架和工具链。
