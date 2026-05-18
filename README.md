# interview — 录音/素材访谈官 Skill

> 拿到录音/素材之后，AI 不直接帮你写。先对你结构化访谈，再写。

## 是什么

一个 Claude Code Skill。

拿到一段录音转录、一堆素材、一段微信对话之后，
它不直接帮你写。
先对你结构化访谈，确认事实、时间线、数字、感受。
访谈完输出一份事实清单，
清单之外的话，初稿不能写。

## 为什么用

AI 最常见的坏习惯是「拿到素材就动笔」。
出来的东西要么是 AI 编的，
要么是把你的草稿改成 AI 腔。

interview 反过来——
它先问你 5 个问题，
你回答完才进下一轮，
全部确认完才允许输出事实清单。

## 如何安装

```bash
git clone https://github.com/duyi2076/duyi-interview ~/.claude/skills/interview
```

装完跟 Claude Code 说「这是我的素材，先访谈」即可触发。

## 详细规则

见 [SKILL.md](./SKILL.md) 和 [references/](./references/)。

## Maintainer

[@duyi2076](https://github.com/duyi2076)
