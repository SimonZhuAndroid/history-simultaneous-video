# history-simultaneous-video

Cursor Agent Skill：按「与此同时」方法生成历史科普视频素材包。

先锚定**好奇起点**与**认知起点**，再按同一时刻做中外对照，产出方案、对照表、讲解脚本、分镜与素材清单。

方法提炼自 [Jenny木妈 · 我用 AI 做的历史视频播放过万](https://mp.weixin.qq.com/s/EzepAh8gYjS8A_yPbsb82Q)。

## 安装

### Cursor / Agent Skills

把本仓库放到个人 skills 目录：

```bash
git clone https://github.com/SimonZhuAndroid/history-simultaneous-video.git \
  ~/.agents/skills/history-simultaneous-video
```

或（若你使用 `~/.cursor/skills`）：

```bash
git clone https://github.com/SimonZhuAndroid/history-simultaneous-video.git \
  ~/.cursor/skills/history-simultaneous-video
```

用 [skills CLI](https://skills.sh/) 时：

```bash
npx skills add SimonZhuAndroid/history-simultaneous-video
```

## 调用

```text
用 history-simultaneous-video：我是历史小白，好奇每个时期中国在干什么、世界在干什么；
喜欢许倬云「世界当中的中国史」；做给家长和初中生看的讲解视频脚本。
```

## 文件

| 文件 | 说明 |
|------|------|
| [SKILL.md](SKILL.md) | 触发、参数、流程、质量门禁 |
| [prompts.md](prompts.md) | P0–P6 核心提示词 |
| [templates.md](templates.md) | brief → assets 产物模板 |

## License

MIT
