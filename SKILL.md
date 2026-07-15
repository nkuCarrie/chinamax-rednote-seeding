---
name: chinamax-xhs-seeding
description: Package cultural tourism, museum, study-trip, intangible heritage, tea, fragrance, hanfu photography, summer travel, ancient town, guesthouse, cultural product, or guofeng lifestyle business information into Xiaohongshu/Rednote 3:4 seeding carousels. Use when merchants or operators need cover titles, selling angles, page-by-page guide layouts, copy, existing-material usage advice, optional image prompts, conversion CTA, and hashtags for guofeng-style social content.
---

# Chinamax XHS Seeding

## Overview

Turn a merchant's ordinary activity, route, exhibit, product, or service information into a Xiaohongshu-ready guofeng seeding carousel. Prioritize real merchant photos and verifiable information; use generation prompts only for missing covers, backgrounds, or decorative assets.

## Workflow

1. Identify merchant type, offer, target audience, season, available materials, and conversion goal.
2. Choose the best seeding angle: parent-child value, route convenience, aesthetic experience, craft process, seasonal ritual, photo value, gift value, or limited-time reason.
3. Choose one visual style from Tang Splendor, Song Literati, ICH Craft, Solar Term East, or Eastern Minimal.
4. Plan a 3:4 cover and 5-7 carousel pages with title, copy, material use, layout, and CTA.
5. Write publish-ready Xiaohongshu caption, hashtags, and a conversion CTA.
6. Provide optional image prompts only when the merchant lacks cover, background, or decorative assets.

## Required Output

Always use this structure:

```markdown
## 商家场景判断
## 推荐种草角度
## 推荐审美风格
## 封面标题
## 封面构图
## 攻略组图
## 每页文案
## 素材使用建议
## 可选生图提示词
## 发布正文
## 转化 CTA
## 小红书标签
```

If the user provides weak or incomplete business details, make conservative assumptions and clearly mark them. Ask follow-up questions only when price, date, location, or booking details are essential to avoid misleading users.

## References

- Read `references/merchant-scenes.md` when classifying the business and choosing the seeding angle.
- Read `references/style-system.md` when choosing guofeng visual direction.
- Read `references/xhs-seeding-layouts.md` when building the cover, carousel, CTA, and material plan.

## Guardrails

- Do not fabricate addresses, prices, dates, discounts, awards, museum facts, or booking policies.
- Do not imply official museum authorization, expert endorsement, or child education outcomes unless provided.
- Prefer "existing photo + layout + copy" over fake AI scenes.
- Avoid cheap ancient style: no random dragons, phoenixes, palace sets, lantern overload, unreadable Chinese text, plastic skin, or excessive red-gold.
- For hanfu photography, avoid over-retouched studio posters; emphasize real customer samples, makeup detail, route, light, and shooting experience.
