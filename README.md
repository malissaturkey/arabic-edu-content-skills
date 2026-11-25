# Arabic Education Content Skills for Claude

Open-source [Claude skills](https://docs.claude.com) that help educational consultants, content creators and students produce **accurate, source-backed Arabic content** about studying abroad — starting with Turkey.

مهارات مفتوحة المصدر لـ Claude تساعد المستشارين التعليميين وصنّاع المحتوى والطلاب على كتابة **محتوى عربي دقيق وموثَّق** عن الدراسة في الخارج، بدءًا بتركيا.

---

## Why this exists | لماذا هذا المشروع؟

Official information about Turkish universities (admission rules, YKS, document requirements, residence permits) is published mostly in Turkish and scattered across many sites. Much of what circulates in Arabic on social media is outdated or wrong, and students make costly decisions based on it.

These skills make Claude:
- check claims against **official sources** (university sites, ÖSYM, YÖK, MEB, government portals) before writing,
- write clear, natural Arabic for students and parents,
- flag uncertainty instead of guessing,
- always include the source link.

المعلومات الرسمية عن الجامعات التركية منشورة غالبًا بالتركية ومتفرقة، وكثير مما يُتداول بالعربية قديم أو غير صحيح. هذه المهارات تجعل Claude يتحقق من المصادر الرسمية أولًا، ويكتب بعربية واضحة، ويذكر الرابط دائمًا، ويصرّح بعدم التأكد بدل التخمين.

## Skills | المهارات

| Skill | What it does |
|---|---|
| [`official-source-checker`](skills/official-source-checker/SKILL.md) | Verifies a claim about studying in Turkey against official sources and returns a verdict with links. |
| [`arabic-edu-content-writer`](skills/arabic-edu-content-writer/SKILL.md) | Turns verified information into Arabic social-media posts, carousels and reel scripts for students. |

## How to use | طريقة الاستخدام

1. Download the skill folder you need.
2. In Claude, add it as a skill (Settings → Capabilities → Skills), or place it in `.claude/skills/` for Claude Code.
3. Ask naturally, e.g. «تحقق من شروط القبول في جامعة … واكتب منشورًا عنها».

## Contributing | المساهمة

Contributions are welcome: new skills, support for other countries (Germany, Cyprus), corrections, and lists of official sources. Please open an issue or a pull request.

المساهمات مرحَّب بها: مهارات جديدة، دعم دول أخرى (ألمانيا، قبرص)، تصحيحات، وقوائم مصادر رسمية.

## Maintainer

Mohammed Al-Issa — educational consultant in Turkey (9 years of experience).

## License

MIT
