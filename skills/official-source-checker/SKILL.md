---
name: official-source-checker
description: Verify a claim about studying in Turkey (admission rules, YKS, fees, documents, equivalency, residence permits) against official sources before it is shared with students. Use when asked "is this true?", before writing any post, or when a news item or rumor needs checking.
---

# Official Source Checker

Students act on what they are told. A wrong deadline or requirement can cost them a year. Your job is to check a claim against official sources and report what they actually say.

## Source priority

Check in this order and prefer the highest available:

1. **Official bodies**: ÖSYM (osym.gov.tr), YÖK (yok.gov.tr), MEB (meb.gov.tr), Göç İdaresi (goc.gov.tr), Resmî Gazete (resmigazete.gov.tr), e-Devlet (turkiye.gov.tr).
2. **The university's own site** (usually `.edu.tr`) — admissions or international office pages.
3. **Established Turkish news outlets** (`.com.tr`) — only to locate an announcement, then confirm it at level 1 or 2.

Never rely on agency ads, forums or social-media posts as evidence.

## Steps

1. Restate the claim in one sentence. Split compound claims into separate checks.
2. Search the official sources above (search in Turkish too — most announcements are only in Turkish).
3. Read the page itself, not just the search snippet. Note the publication or update date.
4. Give a verdict for each part:
   - ✅ **Confirmed** — the official source says this.
   - ⚠️ **Partly true / outdated** — explain what differs.
   - ❌ **Not supported** — no official source says this.
   - ❓ **Could not verify** — say so plainly; do not guess.
5. List every source with its link and date.

## Output format (Arabic by default)

```
الادعاء: …
الحكم: ✅ / ⚠️ / ❌ / ❓
التفاصيل: …
المصادر:
- [اسم الجهة](الرابط) — تاريخ النشر/التحديث
```

## Rules

- Fees, quotas and deadlines change every year: always state which academic year the information is for.
- If two official sources disagree, show both and say which is newer.
- Translate Turkish terms the first time they appear (e.g. «المعادلة (Denklik)»).
