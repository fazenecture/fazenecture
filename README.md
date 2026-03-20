<div align="center">

# hey, I'm Vivek 👋

**backend engineer. I build systems that have to work when things go wrong.**

[![LinkedIn](https://img.shields.io/badge/linkedin-vivek--kumarsingh-blue?style=flat-square&logo=linkedin)](https://linkedin.com/in/vivek-kumarsingh)
[![Twitter](https://img.shields.io/badge/twitter-fazenecture-1DA1F2?style=flat-square&logo=twitter)](https://twitter.com/fazenecture)

</div>

---

most of my work has been in fast-moving SaaS environments where I have worked directly with founders, owned systems end to end, and had to figure things out when they broke. no handholding, no lengthy specs, just a problem and the expectation that you ship something that works. that is the environment I do my best work in. 🔧

I started as a UI/UX designer 🎨, moved into engineering because I wanted to build the thing instead of just draw it, and never looked back. now I work at the intersection of backend systems and AI 🤖, and I think that is where the most interesting problems live right now.

---

### 🚫 what I actually build

not todo apps. not tutorial projects.

systems that sync lakhs of user records across enterprise identity providers without losing data 🔄. workflow automation engines that let non-technical teams configure complex multi-step logic without writing a single line of code ⚙️. market intelligence tools that scrape data from platforms actively trying to stop you, process it through a pipeline of local models and LLMs, and surface signals that actually mean something 📈. the kind of systems where a silent failure at 2am is a real problem 🚨.

I have built across SaaS, fintech, HRIS, integrations, e-commerce, inventory, workflow automation and AI. I pick whatever database fits the problem. strong opinions about when to use each one.

---

### 🚀 currently building

| project | what it does |
|---|---|
| **[🟢 NSE OI Dashboard](https://nocnse.lovable.app)** | predicts Nifty 50 stock movements using OI buildup classification, absorption scoring and spread Z-scores. data pipeline scrapes NSE via residential proxies with real-time block detection because NSE aggressively blocks cloud IPs and I was not going to let that stop me. backend mine, frontend by Lovable (no shame). |
| **[🦢 Mood Tracker](https://orange-swan-index-web.vercel.app)** | tracks a certain very online public figure's mood every 30 minutes using local HuggingFace models, Claude and GPT-4o with automatic fallback, and pgvector for historical pattern matching. you will know who it is when you open it. |
| **[💸 Finance Analyser](/#)** | ingests your financial statements, detects subscriptions you forgot about, categorises spending and tells you what your finances actually look like versus what you think they look like. |

---

### 🛠️ the stack

```typescript
const vivek = {
  primary:      ["Node.js", "TypeScript", "Express.js"],
  databases:    ["PostgreSQL", "MongoDB", "CockroachDB", "DynamoDB", "Redis", "Firebase"],
  infra:        ["AWS (Lambda, SQS, ECS, S3, RDS)", "Docker", "Kafka", "RabbitMQ"],
  ai:           ["OpenAI API", "Claude", "HuggingFace", "pgvector", "RAG pipelines", "local LLMs"],
  frontend:     ["React", "React Native", "Flutter", "Lovable (for when I need UI fast)"],
  others:       ["GraphQL", "REST", "SOAP", "SCIM", "Prisma", "Hasura", "Python"],
  currently:    "building things that break interestingly in production 🔥"
}
```

---

### 🧠 how I think about problems

I do not start with the tech. I start with what breaks and work backwards.

> the NSE scraper did not need a fancier algorithm. it needed a system that could survive a hostile network environment and keep running without me babysitting it 🤝

> the workflow engine did not need more features. it needed a data model flexible enough that non-technical teams could configure complex logic without calling engineering 🧩

> the AI mood tracker did not need a bigger model. it needed a cost architecture that could run forever on a small budget without sacrificing quality 💡

every constraint is just a problem that has not been solved yet. I enjoy solving them.

---

### 💭 a few things I believe

🔊 **systems should fail loudly or not at all.** silent failures are a form of lying.

🤖 **the hardest part of any AI system is not the model.** it is the plumbing around it. the cost management, the fallback logic, the evaluation, the part that keeps it working at 3am.

⚡ **the best engineers do not wait to be unblocked.** they find a way or build one.

😅 **if you are not slightly embarrassed by your side projects**, you are not building interesting enough things.

🎨 **frontend is just backend with more opinions about spacing.**

---

### 📊 stats

<p align="center">
  <img width="48%" src="https://github-readme-streak-stats.herokuapp.com/?user=fazenecture&theme=tokyonight" />
  <img width="48%" src="https://github-readme-stats.vercel.app/api?username=fazenecture&show_icons=true&theme=tokyonight&hide_border=true" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=fazenecture&layout=compact&theme=tokyonight&hide_border=true" />
</p>

---

<div align="center">

*building in public. breaking things privately. figuring it out either way.* 🛠️

</div>
