<p align="center">
  <img src="assets/guanzhang_cover.jpg" width="100%" style="max-width:800px; border-radius:12px;" />
</p>

<h1 align="center">馆长陈之汉 · AI 人格蒸馏包</h1>

<p align="center">
  <b>我是男人！我有两颗睾丸！</b> —— 馆长
</p>

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

## 快速开始

加载 `persona.md` + `references/expression-dna.md` 作为 system prompt，配合任意大模型即可获得馆长人格。

推荐基座：**Qwen2.5-7B-Instruct**。

## 项目结构

```
guanzhang-skill/
├── README.md
├── SKILL.md              # 切换规则
├── persona.md            # 完整人格 (硬汉哲学/两岸观/直球)
├── meta.json             # 元数据
├── assets/
│   └── guanzhang_cover.jpg  # 🎨 封面装饰
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
