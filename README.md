# ⚙️ اظبط Claude صح في 4 خطوات — الـ SETUP الكامل

<p align="center">
  <a href="#prompt"><img src="https://img.shields.io/badge/%E2%9A%A1%20GET%20THE%20PROMPT-COPY%20%26%20PASTE-F97316?style=for-the-badge" alt="خد الـ Prompt على طول" height="44"></a>
  <a href="#fill"><img src="https://img.shields.io/badge/%F0%9F%93%9D%20FILL%20YOUR%20DETAILS-NAME%20%C2%B7%20NICHE%20%C2%B7%20TEXT-2563EB?style=for-the-badge" alt="املا بياناتك" height="44"></a>
</p>

<p align="center"><b>👆 دوس على الزرار البرتقاني وهتروح للـ Prompt على طول — املا الخانات والصقه في Claude.</b></p>

Claude بيرد على كل الناس بإجابات General، لأنه مش عارف انت مين ولا شغلك ايه ولا عايز الرد ازاي.
لما تظبط الـ Settings صح وتعرّفه عليك، الإجابات بتبقى مفصلة عليك انت بالظبط.

هنا هتلاقي **الـ Prompts اللي بستخدمها بالظبط** في الـ Setup، وكل واحد معاه شرح بيعمل إيه وامتى تستخدمه.

> 💡 انسخ الـ Prompt زي ما هو، وغيّر بس الحاجات اللي بين `[ ]`.

---

## 🔌 الأول: افتح الـ Settings

1. افتح Claude (الموقع أو التطبيق).
2. دوس على صورتك أو الحروف الأولى من اسمك (تحت على الشمال في الموقع) واختار **Settings**.
3. هتلاقي الأقسام اللي هنشتغل عليها: الـ Profile / Personal Preferences، الـ Memory، الـ Capabilities، والـ Privacy.

> ⚠️ أماكن الأقسام دي بتتغير من نسخة لنسخة (Anthropic بتحدّث الشكل). لو مش لاقي قسم في مكانه، دور عليه في الأقسام التانية في الـ Settings.
> مرجع رسمي: https://support.claude.com

---

<a id="fill"></a>

## 📝 املا بياناتك الأول (مرة واحدة بس)

كل الـ Prompts تحت بتستخدم نفس الخانات دي، فاملاها مرة واحدة وانسخ.

| الخانة | تكتب فيها إيه | مثال |
|---|---|---|
| `[YOUR NAME]` | اسمك | Ahmed |
| `[WORK]` | شغلك أو دورك | Freelance video editor |
| `[CONTENT TYPE]` | مجالك أو نوع البزنس | Real estate marketing |
| `[AUDIENCE]` | بتكلم مين أو بتخدم مين | Egyptian small business owners |
| `[LANGUAGE]` | اللغة اللي عايز الرد بيها | Egyptian Arabic, with tech terms in English |
| `[ANSWER STYLE]` | شكل الإجابة اللي بتحبه | Short, direct, bullet points |
| `[GOALS]` | هدفك من استخدام Claude | Write content faster and automate my work |
| `[TOOLS]` | الأدوات اللي بتشتغل بيها | Gmail, Notion, Google Sheets |

<a id="prompt"></a>

### ⚡ Prompt واحد شامل — املا والصق

املا الخانات اللي فوق والصق الـ Prompt ده في شات جديد مع Claude، وهو يطلعلك نص جاهز تحطه في الـ Personal Preferences.

```
Here are my details:
- Name: [YOUR NAME]
- Work: [WORK]
- Niche / business type: [CONTENT TYPE]
- Audience: [AUDIENCE]
- Reply language: [LANGUAGE]
- Preferred answer style: [ANSWER STYLE]
- Goals: [GOALS]
- Tools I use: [TOOLS]

Do this in order:
1. Write my "Personal Preferences" text for Claude settings. Keep it under 200 words, first person, clear and practical. Cover who I am, what I do, how I want answers (language, length, format), and what to avoid.
2. Write 8 short facts about me that I should add to Claude's memory, one per line.
3. Give me a short checklist of the Settings I should review (Memory, Capabilities, Model choice, Privacy) and what each one does.
4. Ask me up to 3 questions if something important is missing.
Do not change any settings yourself. Only give me the text to paste.
```

**بيعمل إيه؟** بيطلعلك الـ Personal Preferences والـ Memory facts وقايمة مراجعة للـ Settings في رد واحد، وانت بس تنسخ وتحط في الأماكن الصح.

---

## 💬 الـ Prompts خطوة بخطوة

## ✍️ 1. اكتب الـ Personal Preferences

استخدمه في أول خطوة، لما تيجي تملا خانة الـ Personal Preferences في الـ Settings.

```
Help me write the "Personal Preferences" text for my Claude settings.

About me:
- Name: [YOUR NAME]
- Work: [WORK]
- Niche / business type: [CONTENT TYPE]
- Audience: [AUDIENCE]
- Reply language: [LANGUAGE]
- Answer style: [ANSWER STYLE]

Write it in first person, under 150 words, as instructions Claude can follow in every chat. Include who I am, what I work on, how I want replies (language, length, format), and things to avoid. Then show me the final text in one code block so I can copy it.
```

**بيعمل إيه؟** بيحوّل معلوماتك لنص مرتب تحطه مرة واحدة، وكل شات بعد كده يبدأ وClaude عارف انت مين.
**نصيحة:** اكتب حاجات تفرق فعلاً (اللغة، الطول، الفورمات). مفيش داعي للكلام العام زي "كن مفيد".

---

## 🧠 2. علّمه عنك (Memory)

بعد ما تفعّل الـ Memory من الـ Settings، ابدأ شات وعرّفه بنفسك.

```
Remember these about me for future chats:
- I'm [YOUR NAME], working as [WORK] in [CONTENT TYPE].
- My audience is [AUDIENCE].
- I want replies in [LANGUAGE], in this style: [ANSWER STYLE].
- My main goals: [GOALS].
- Tools I use: [TOOLS].

Confirm back in a short list what you will keep in mind.
```

**بيعمل إيه؟** بيدّي Claude خلفية ثابتة عنك. الـ Memory لازم تكون مفعّلة من الـ Settings الأول علشان ده يشتغل.

---

## 🔄 3. انقل الـ Memory من ChatGPT

لو كنت بتستخدم ChatGPT قبل كده وعايز ياخد Claude نفس المعلومات.

الأول، في Claude افتح الـ Settings وادور على **Import memory from other AI providers** (أو Start import) تحت قسم الـ Memory. Claude هيديك Prompt جاهز، انسخه والصقه في ChatGPT، وبعدين انسخ الرد وارجع الصقه في Claude واختار **Add to memory**.

لو مش لاقي الخيار، ممكن تجرب Prompt شبه ده في ChatGPT:

```
List everything you remember about me from our past chats and your memory. Group it under headings: personal context, work, projects, preferences, tools, and communication style. Put the full output in one code block, with one fact per line. Do not summarize or leave anything out.
```

**بيعمل إيه؟** بيطلع كل اللي ChatGPT عارفه عنك في نص واحد تديه لـ Claude.
**نصيحة:** راجع النص قبل ما تلصقه وامسح أي حاجة شخصية مش عايز Claude ياخدها. وClaude بيركز على المعلومات المتعلقة بالشغل، فبعض التفاصيل الشخصية ممكن ما تتحفظش.

---

## 🔍 4. شوف Claude فاكر عنك إيه

استخدمه بعد فترة، للتأكد إن الـ Memory مظبوطة.

```
Write out everything you currently remember about me, grouped by topic. Mark anything that looks outdated or wrong, and ask me which items I want to correct or remove.
```

**بيعمل إيه؟** بيعرضلك الـ Memory كلها علشان تصلحها. تقدر كمان تراجعها وتعدلها من الـ Settings مباشرة.

---

## 🧩 5. اختار الـ Capabilities والـ Model الصح

```
I mostly use Claude for: [GOALS], and my tools are: [TOOLS].
Tell me, in a simple table:
1. Which tasks need Web Search turned on, and which don't.
2. Which tasks need Extended Thinking, and which are a waste of it.
3. Which kind of model to pick for quick everyday questions versus hard tasks, so I don't burn through my usage limit.
Keep it practical and short.
```

**بيعمل إيه؟** بيقولك امتى تشغّل Web Search وExtended Thinking، وامتى تختار Model أخف علشان الاستهلاك ما يخلصش بسرعة.
**نصيحة:** الـ Model الأقوى بيستهلك من حدّ الاستخدام أسرع، فسيبه للحاجات الصعبة بس.

---

## 🔐 6. راجع الـ Privacy

```
Give me a short checklist to review my Claude privacy settings. For each item explain, in one line, what it controls: whether my chats can be used for model training, memory from chats, and search of past chats. Tell me what questions to ask myself to decide, but do not decide for me.
```

**بيعمل إيه؟** بيشرحلك كل إعداد في الـ Privacy بأسلوب بسيط. القرار قرارك: تسمح باستخدام محادثاتك في الـ Training ولا لأ.

---

## 📁 7. اعمل Project بتعليمات خاصة

لو عندك شغل متكرر (عميل معين، مجال معين)، اعمل Project وحط فيه التعليمات.

```
Help me write instructions for a Claude Project about [CONTENT TYPE] for [AUDIENCE]. Include: the goal of the project, the tone and language ([LANGUAGE]), the format of outputs ([ANSWER STYLE]), and 5 rules Claude must always follow. Keep it under 200 words.
```

**بيعمل إيه؟** بيطلعلك تعليمات للـ Project، وهي بتتضاف فوق الـ Personal Preferences.

---

## ✅ 8. اختبر الـ Setup

```
Based on what you know about me, answer this test: "Write a short plan for my week" for my work as [WORK]. Then tell me which of my settings (preferences, memory) you used, and what extra information would make the answer better.
```

**بيعمل إيه؟** بيوريك لو الـ Setup شغّال، وبيقولك إيه الناقص تضيفه.

---

## 🇪🇬 تقدر تكتبله بالمصري كمان

```
أنا [اسمك]، شغال [شغلك] في مجال [مجالك]. الجمهور بتاعي [الجمهور].
عايزك ترد عليا بالمصري وبإجابات [شكل الإجابة]، وسيب المصطلحات التقنية بالإنجليزي.
اكتبلي نص Personal Preferences مناسب ليا في أقل من 150 كلمة.
```

## ⚠️ نصايح مهمة

- اكتب في الـ Preferences الحاجات اللي بتفرق فعلاً (اللغة، الطول، الفورمات)، مش كلام عام.
- ما تكتبش بيانات حساسة (باسوردات، أرقام حسابات بنك، أرقام بطاقات) في الـ Preferences أو الـ Memory.
- راجع الـ Memory كل فترة وامسح القديم أو الغلط.
- Web Search مهم للمعلومات اللي بتتغير، وExtended Thinking للحاجات الصعبة بس.
- التعديلات على الـ Preferences بتطبق على الشاتات الجديدة، مش القديمة.

## 🚀 الخلاصة

| قبل | بعد |
|---|---|
| إجابات General لأي حد | إجابات مفصلة على شغلك وأسلوبك |
| كل شات تعرّفه بنفسك من الأول | Claude فاكرك من الـ Memory |
| الاشتراك بيخلص بسرعة | Model مناسب لكل مهمة |
| مش عارف إيه بيتحفظ | انت اللي متحكم في الـ Privacy |

---
لو استفدت، تابعني عشان فيه Prompts وأتمتة أكتر جاية 🔥

**Steven Ayman — Vida AI**
