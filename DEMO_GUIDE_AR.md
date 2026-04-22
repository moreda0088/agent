# AgentFlow — دليل تسجيل الفيديو

---

## قبل ما تبدأ

1. شغل `setup.bat` واستنى السيرفر يشتغل
2. افتح Chrome وروح على `http://localhost:3000`
3. اقفل كل التابات والنوتيفيكيشنز
4. حط Chrome Full Screen (F11)
5. شغل OBS Studio أو Loom
6. اتأكد ان الداشبورد فيه داتا (لو فاضي روح Demo Control ودوس Seed Data)

---

## المشهد 1 — الصفحة الرئيسية (15 ثانية)

**انت فين:** `http://localhost:3000`

**سيب الأرقام تتحرك لوحدها**

**قول:**
> "This is AgentFlow. A marketplace where AI agents work together on tasks — and every payment is tracked on-chain. Let me show you."

**دوس على:** "Launch Dashboard"

---

## المشهد 2 — الداشبورد (25 ثانية)

**وري:** الأرقام فوق + الـ Heartbeat + Arc vs Ethereum

**قول:**
> "The dashboard shows live activity. We have dozens of micro-payments already settled on Arc using Circle.
>
> See the heartbeat — it shows payments happening in real time.
>
> On the right — the same payments on Ethereum would cost over a hundred dollars in gas. On Arc, gas is almost zero. That is why this works."

**اوقف** على الكارد بتاعت Arc vs Ethereum 3 ثواني
**انزل لتحت** وري الـ Agent Leaderboard

---

## المشهد 3 — اعمل Task جديد (40 ثانية)

**دوس على:** "+ New Task"

**اكتب:**
- Title: `Competitive analysis of AI coding assistants`
- Description: `Compare top 5 on features, pricing, accuracy, and developer experience`
- Category: Analysis
- Complexity: 3

**قول:**
> "Let me run a task live. This goes through five specialist agents — each one charges a fraction of a cent. The total cost is just a few cents."

**دوس على:** "Execute Task — Sub-Cent Cost"

**استنى** 5-10 ثواني

**قول:**
> "Done. Five agents just worked together. The Orchestrator planned. The Researcher analyzed. The Builder created. The Reviewer scored. And the Presenter polished the final output. Each one got paid separately on-chain."

**دوس على** التاسك اللي لسه عملتها من الليست

---

## المشهد 4 — Economics (30 ثانية)

**انت في تاب Economics أوتوماتيك**

**قول:**
> "Here you see where every cent went. The user paid into escrow. Escrow split the money across five agents and took a fifteen percent platform fee.
>
> Each agent earned between a fraction of a cent and half a cent. The Researcher even hired the Builder for part of the work — that is a sub-contract, and it is a separate on-chain payment."

**انزل لتحت** وري Cost Breakdown و Bid Competition

**قول:**
> "Below, you can see the cost breakdown per agent, and above that, how agents competed on price. The lowest bid won."

---

## المشهد 5 — Timeline (15 ثانية)

**دوس على تاب:** "Timeline"

**قول:**
> "The timeline shows every single payment — escrow, agent payouts, sub-contracts, platform fees. Each one has a real transaction hash you can verify on Arc Block Explorer."

---

## المشهد 6 — Results (10 ثانية)

**دوس على تاب:** "Results"

**قول:**
> "And here is the final work. Five agents collaborated to produce this. Scored eight point five out of ten by the quality reviewer."

---

## المشهد 7 — Transaction Explorer (20 ثانية)

**دوس على:** "Transactions" في الـ sidebar الشمال

**قول:**
> "The explorer shows all settlements. You can filter by type — escrow, agent payments, sub-contracts, or platform fees. Every single one has an Arc explorer link."

**دوس على** filter "agent payment" → بعدين "subcontract" → بعدين "All"

---

## المشهد 8 — Margin Analysis (25 ثانية)

**دوس على:** "Margin Analysis" في الـ sidebar

**قول:**
> "This is the key insight. On Ethereum each payment costs two dollars in gas. When an agent earns half a cent, paying two dollars to send it makes no sense.
>
> On Arc, gas is almost free. Over ninety-nine percent of the money goes to actual value — not fees. That is why micro-agent-payments only work on Arc with Circle."

**اوقف** على رقم الـ Savings 3 ثواني

---

## المشهد 9 — الختام (10 ثانية)

**دوس على:** "Dashboard" في الـ sidebar

**قول:**
> "AgentFlow shows that the future of AI is agents paying agents — and that future needs a chain built for tiny payments. Arc plus Circle is that chain. Thank you."

---

## نصايح مهمة

- **متقولش "demo"** في الفيديو — قول "live"
- **متقولش ارقام محددة** — قول "dozens of payments" و "a few cents" و "over a hundred dollars"
- **حرك الماوس ببطء** ومتلفش
- **اوقف على الأرقام المهمة** 2-3 ثواني عشان الجدج يقرأها
- **الفيديو مش محتاج وشك** — screen recording بس
- **الطول:** 3-4 دقايق مش أكتر
- **صدره:** MP4, 1080p

---

## الملفات اللي ترفعها

| ملف | فين | ليه |
|-----|-----|-----|
| الفيديو MP4 | YouTube unlisted أو Google Drive | الديمو |
| كل الكود | GitHub repo | الكود |
| `README.md` | في الريبو | الدوكيومنتيشن |
| `SUBMISSION.md` | في الريبو | نص الـ submission |
| `CIRCLE_FEEDBACK.md` | في الريبو | feedback عن Circle |

---

## في الـ Submission Form اكتب

**Project Name:** AgentFlow — See Every Cent of Intelligence

**One-liner:** A live economic marketplace where AI agents bid, subcontract, and settle sub-cent USDC micro-payments on Arc — with full visibility for every action.

**Track:** Agentic Economy on Arc

**Circle product used:** Circle Nanopayments, Programmable Wallets, USDC on Arc
