---
title: Claude Code 源码泄露事件
published: 2026-04-02
description: Anthropic 难道真的比 OpenAI 更开源...
tags: [News, Claude Code]
category: 技术
draft: false
---

4月1日，Claude Code 51 万行源码泄露。首先由 Chaofan Shou 发现，公布在推特上，并很快引起了爆火，源码传遍了整个互联网。

泄露的原因很简单，Anthropic 在通过 npm 发布 2.1.88 版本时，忘记删除了 Source Map 文件。这相当于给了别人一个“翻译对照表”，能还原出原始代码。

这么低级的错误，都让人怀疑是不是故意的...这就是 Anthropic 的开源精神嘛。

这次泄露的是客户端的源码，没有服务端的模型训练代码，最近正在准备 AI HACK，有时间去学习一下。