# EveryMind

**AI output, shaped for every mind.**

AI assistants give every answer in one shape: dense paragraphs, long lists, unexplained jargon.
For millions of readers, that shape is the problem — not the content.

EveryMind is a pack of four small, free skills. Each one reshapes how your AI assistant writes, so the answer fits the mind reading it. The facts stay the same. The shape changes.

> 🇩🇿 **العربية في الأسفل** — قسم عربي كامل بعد القسم الإنجليزي.

## The four skills

| Skill | For whom | What changes |
|---|---|---|
| **dyslexia-friendly** | Readers with dyslexia | Short lines, no text walls, bold lead words, digits instead of number words, room to breathe |
| **plain-language** | Anyone reading in a language that is not their own | Everyday words, short sentences, no idioms or slang, hard words explained in brackets |
| **one-step-at-a-time** | Overwhelmed, exhausted, frozen readers | Exactly one small action per reply — the assistant holds the plan, you see only the next step |
| **clear-and-slow** | Older readers | Headings before every topic, one topic at a time, every abbreviation explained, a recap at the end |

Use one, or combine them — a reader can be all four at once.

## See the difference

**The question:** "How do I renew my passport?"

**Default shape:**

> To renew your passport: 1) Check the expiry date, 2) book an appointment online, 3) get a compliant photo taken, 4) fill in the renewal form, 5) gather your old passport and ID, 6) prepare the fee, 7) attend the appointment, 8) track the delivery. Start early because processing takes 6–8 weeks.

**With `one-step-at-a-time`:**

> That is a doable job, and I am holding the whole list so you do not have to look at it.
>
> **Next step: find your passport and check the expiry date on it.**

Same information. A shape a tired mind can actually start with. Every skill in this pack has a full before/after example inside its `SKILL.md`.

## Install

Each skill is one folder containing one `SKILL.md` file. No code, no accounts, nothing to run.

**Manual (works everywhere skills are supported):**

1. Download or clone this repository.
2. Copy the skill folder(s) you want into your skills directory:
   - Personal: `~/.claude/skills/`
   - Per project: `.claude/skills/` inside the project
3. Start a new conversation. Ask for the shape you need — "answer me dyslexia-friendly", "one step at a time, please" — or let the assistant pick the skill up from its description.

**With the skills CLI:**

```
npx skills add dagdog16-beep/everymind
```

## Honest notes

- These skills shape **output only**. They never change facts, numbers, code, or quoted text — each file says so, in hard rules.
- The idea that tiny output-shaping skills change lives was proven by the ADHD-mode skills that spread across this ecosystem in 2026. The four reader modes in this pack did not exist. Now they do.
- A skill is guidance for the assistant, not a guarantee: if an answer slips out of shape, say "back to the skill" and it will correct.

## Roadmap

More reader modes are planned. Requests welcome — open an issue and describe the mind the current shapes fail.

## Credit

Made by **dagdog.Tools** — TikTok: [@dagdog.tools](https://www.tiktok.com/@dagdog.tools) · GitHub: [dagdog16-beep](https://github.com/dagdog16-beep)

Free forever under the MIT License. If EveryMind helps you or someone you love, share it — that is the whole point.

---

# EveryMind — بالعربية

**مخرجات الذكاء الاصطناعي، على مقاس كل عقل.**

المساعدون الأذكياء يعطون كل جواب في قالب واحد: فقرات مكدّسة، قوائم طويلة، ومصطلحات بلا شرح.
وعند ملايين القرّاء، المشكلة هي القالب نفسه — مش المحتوى.

EveryMind حزمة من أربعة سكيلات صغيرة ومجانية. كل سكيل يعيد تشكيل طريقة كتابة مساعدك الذكي، باه الجواب يناسب العقل اللي يقراه. الحقائق تبقى هي هي. القالب هو اللي يتبدّل.

## السكيلات الأربعة

| السكيل | لمن | واش يتبدّل |
|---|---|---|
| **dyslexia-friendly** | قرّاء عسر القراءة | سطور قصيرة، لا جدران نص، كلمات مفتاحية عريضة، أرقام مش حروف، ومساحات للتنفس |
| **plain-language** | أي واحد يقرا بلغة مش لغتو | كلمات يومية، جمل قصيرة، بلا أمثال ولا مصطلحات، والكلمات الصعبة مشروحة بين قوسين |
| **one-step-at-a-time** | المُنهك والمضغوط والمتجمّد | فعل واحد صغير في كل رد — المساعد يشدّ الخطة كاملة، وانت تشوف غير الخطوة الجاية |
| **clear-and-slow** | كبار السن | عنوان قبل كل موضوع، موضوع واحد في كل مرة، كل اختصار مشروح، وخلاصة في الآخر |

استعمل واحد، ولا اجمع بيناتهم — القارئ الواحد يقدر يكون الأربعة في نفس الوقت.

## شوف الفرق

**السؤال:** "كيفاش نجدّد جواز السفر تاعي؟"

**القالب العادي:** قائمة من 8 خطوات مرة وحدة، مع تحذير في الآخر بلي المعالجة تاخذ 6–8 أسابيع.

**مع سكيل `one-step-at-a-time`:**

> هذي خدمة تتعمل، وأنا شادّ لك القائمة كاملة باه ما تضطرش تشوفها.
>
> **الخطوة الجاية: ألقى جواز سفرك وشوف تاريخ انتهاء الصلاحية تاعو.**

نفس المعلومات. بصح قالب يقدر عقل تعبان يبدا بيه. كل سكيل في الحزمة فيه مثال كامل قبل/بعد داخل ملفو.

## التثبيت

كل سكيل هو مجلد فيه ملف واحد `SKILL.md`. لا كود، لا حسابات، لا حتى شيء يتشغّل.

1. نزّل هذا المستودع ولا انسخو (clone).
2. انسخ مجلد السكيل اللي تبغيه إلى مجلد السكيلات:
   - شخصي: `~/.claude/skills/`
   - خاص بمشروع: `.claude/skills/` داخل المشروع
3. ابدا محادثة جديدة واطلب القالب اللي تحتاجو — "جاوبني بطريقة مريحة لعسر القراءة"، "خطوة بخطوة، وحدة برك" — ولا خلّي المساعد يلتقط السكيل من وصفو.

## ملاحظات صريحة

- هذي السكيلات تشكّل **المخرجات فقط**. ما تبدّلش الحقائق ولا الأرقام ولا الكود ولا النصوص المقتبسة — مكتوبة كقواعد صارمة داخل كل ملف.
- فكرة بلي سكيلات صغيرة لتشكيل المخرجات تبدّل حياة الناس تثبتت بسكيلات وضع ADHD اللي انتشرت في 2026. الأوضاع الأربعة في هذي الحزمة ما كانتش موجودة. دروك ولات موجودة.

## الاعتماد

من صنع **dagdog.Tools** — تيك توك: [@dagdog.tools](https://www.tiktok.com/@dagdog.tools) · غيت هب: [dagdog16-beep](https://github.com/dagdog16-beep)

مجانية للأبد برخصة MIT. إذا فادتك EveryMind ولا فادت واحد تحبو، شاركها — هذي هي الغاية كاملة.
