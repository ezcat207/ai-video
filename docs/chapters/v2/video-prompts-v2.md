---
title: AI 视频提示词总表（v2 · 第一原理版）
book: AI 导演：用文字拍电影（工作标题）
date: 2026-11-02
language: zh+en
status: 初稿待审
---

# AI 视频提示词总表（v2 · 第一原理版）

> 本表收录 v2 各章的提示词范例。统一例子：橘色虎斑猫的 15 秒短视频。
> 锚定词（每条 prompt 相同）：橘色虎斑猫，绿色眼睛，白色项圈，在奶茶店，暖黄灯光。
> Anchor words (identical in every prompt): orange tabby cat, green eyes, white collar, in a milk tea shop, warm yellow light.

## 通用公式

**中文**：[锚定词]，[景别]，[动作]，[运镜]，[时长]，感觉：[感觉词]，顺序：第 [几] 个，[钩子/发展/反转]
**English**: [anchor words], [shot size], [action], [camera movement], [duration], feeling: [feeling], order: shot [n], [hook/buildup/twist]

## 第 2 章 顺序 · Sequence

- 镜头 1（钩子）：猫的脸部特写，眼睛睁大，2 秒；顺序：第 1 个，钩子
  - EN: Close-up of a cat's face, eyes widening, 2 seconds; order: shot 1, hook
- 镜头 2（发展）：猫悄悄靠近一只老鼠玩具，镜头跟随，3 秒；顺序：第 2 个，发展
  - EN: Cat sneaking up on a toy mouse, camera following, 3 seconds; order: shot 2, buildup
- 镜头 3（反转）：猫一爪拍飞电视遥控器，得意地看镜头，3 秒；顺序：第 3 个，反转
  - EN: Cat swatting the TV remote away, smugly looking at camera, 3 seconds; order: shot 3, twist

## 第 3 章 注意力 · Attention

- 特写（落点：眼睛）：猫的脸部特写，眼睛睁大，背景虚化，镜头静止，2 秒，落点：眼睛
  - EN: Extreme close-up of a cat's face, eyes widening, blurred background, static camera, 2 seconds, focus point: the eyes
- 跟随（落点：奔跑的少年）：少年在操场上奔跑，镜头跟随他横向移动，背景动态模糊，2 秒，落点：奔跑的少年
  - EN: A teenage boy running on a track, camera trucks alongside him, motion-blurred background, 2 seconds, focus point: the running boy

## 第 4 章 省略 · Omission

- 关键帧：猫从沙发上跃起，扑向一只老鼠玩具，镜头跟随，2 秒，关键帧：跃起瞬间
  - EN: Cat leaping off a sofa toward a toy mouse, camera following, 2 seconds, key frame: the leap

## 第 5 章 声音 · Sound（声音说明写进分镜，不写进生成 prompt）

- 镜头 1：静默 1 秒，然后一声猫叫
- 镜头 2：轻快的 BGM 起，音效：爪子落地的"啪"
- 镜头 3：BGM 停半拍，音效：遥控器落地的"哐"

## 第 6 章 变化 · Change

- 镜头 1：故事功能：钩子 / story job: hook
- 镜头 2：故事功能：发展 / story job: buildup
- 镜头 3：故事功能：反转 / story job: twist

## 第 7 章 相信 · Continuity（锚定词版）

- 镜头 1：橘色虎斑猫，绿色眼睛，白色项圈，在奶茶店，暖黄灯光，猫的脸部特写，眼睛睁大，2 秒
- 镜头 2：橘色虎斑猫，绿色眼睛，白色项圈，在奶茶店，暖黄灯光，猫悄悄靠近老鼠玩具，镜头跟随，3 秒
- 镜头 3：橘色虎斑猫，绿色眼睛，白色项圈，在奶茶店，暖黄灯光，猫一爪拍飞遥控器，得意地看镜头，3 秒

## 第 8 章 翻译 · Translation（完整翻译范例）

- 镜头 1：猫的脸部特写，眼睛睁大，镜头缓慢推近，2 秒，感觉：紧张
  - EN: Close-up of a cat's face, eyes widening, camera slowly pushing in, 2 seconds, feeling: tense
- 镜头 2：猫悄悄靠近老鼠玩具，镜头静止，音效：爪子落地的"啪"，3 秒，感觉：好笑
  - EN: Cat sneaking up on a toy mouse, static camera, sound effect: paws landing with a "thud," 3 seconds, feeling: funny
- 镜头 3：猫一爪拍飞遥控器，得意地看镜头，3 秒，感觉：反转
  - EN: Cat swatting the remote away, smugly looking at camera, 3 seconds, feeling: twist

## 第 9 章 分镜 · Storyboard（完整 prompt）

- 中文：橘色虎斑猫，绿色眼睛，白色项圈，在奶茶店，暖黄灯光，猫的脸部特写，眼睛睁大，镜头静止，2 秒，感觉：紧张，顺序：第 1 个，钩子
- English: Orange tabby cat, green eyes, white collar, in a milk tea shop, warm yellow light, close-up of the cat's face, eyes widening, static camera, 2 seconds, feeling: tense, order: shot 1, hook

## 第 10 章 补拍 · Reshoot

- 原 prompt：橘色虎斑猫，绿色眼睛，白色项圈，在奶茶店，暖黄灯光，猫的脸部特写，眼睛睁大，镜头静止，2 秒
- 补拍 prompt（只改错的一句）：橘色虎斑猫，绿色眼睛，白色项圈，在奶茶店，暖黄灯光，猫的脸部特写，**眼睛突然睁大，瞳孔放大**，镜头静止，2 秒
