# hey, I'm Vivek 👋

backend engineer. I build systems that have to work when things go wrong.

most of my work has been in fast-moving SaaS environments where I have worked directly with founders, owned systems end to end, and had to figure things out when they broke. no handholding, no lengthy specs, just a problem and the expectation that you ship something that works. that is the environment I do my best work in.

I started as a UI/UX designer, moved into engineering because I wanted to build the thing instead of just draw it, and never looked back. now I work at the intersection of backend systems and AI, and I think that is where the most interesting problems live right now.

---

### what I actually build

not todo apps. not tutorial projects.

systems that sync lakhs of user records across enterprise identity providers without losing data. workflow automation engines that let non-technical teams configure complex multi-step logic without writing a single line of code. market intelligence tools that scrape data from platforms actively trying to stop you, process it through a pipeline of local models and LLMs, and surface signals that actually mean something. the kind of systems where a silent failure at 2am is a real problem.

I have built across SaaS, fintech, HRIS, integrations, e-commerce, inventory, workflow automation and AI. I pick whatever database fits the problem. I have used PostgreSQL, MongoDB, CockroachDB, DynamoDB, Redis and Firebase in production and I have strong opinions about when to use each one.

---

### live projects

**[nocnse.lovable.app](https://nocnse.lovable.app)** — NSE F&O open interest dashboard that predicts Nifty 50 stock movements using buildup classification, absorption scoring, fut-spot spread Z-scores and multi-day streak detection. the data pipeline scrapes NSE via a residential proxy layer with real-time block detection and intelligent retry logic because NSE aggressively blocks cloud IPs and I was not going to let that stop me. backend fully mine. frontend by Lovable (no shame).

**[orange-swan-index-web.vercel.app](https://orange-swan-index-web.vercel.app)** — AI system that tracks a certain very online public figure's mood every 30 minutes using local HuggingFace models for signal extraction, Claude and GPT-4o for synthesis with automatic fallback, and pgvector for historical pattern matching that gets smarter over time. you will know who it is when you open it.

**personal finance analyser** — ingests your financial statements, detects recurring subscriptions you forgot about, categorises spending and tells you what your finances actually look like versus what you think they look like.

---

### the stack

```typescript
const vivek = {
  primary:      ["Node.js", "TypeScript", "Express.js"],
  databases:    ["PostgreSQL", "MongoDB", "CockroachDB", "DynamoDB", "Redis", "Firebase"],
  infra:        ["AWS (Lambda, SQS, ECS, S3, RDS)", "Docker", "Kafka", "RabbitMQ"],
  ai:           ["OpenAI API", "Claude", "HuggingFace", "pgvector", "RAG pipelines", "local LLMs"],
  frontend:     ["React", "React Native", "Flutter", "Lovable (for when I need UI fast)"],
  others:       ["GraphQL", "REST", "SOAP", "SCIM", "Prisma", "Hasura", "Python"],
  currently:    "building things that break interestingly in production"
}
```

---

### how I think about problems

I do not start with the tech. I start with what breaks and work backwards.

the NSE scraper did not need a fancier algorithm. it needed a system that could survive a hostile network environment and keep running without me babysitting it. the workflow engine did not need more features. it needed a data model flexible enough that non-technical ops teams could configure it without calling engineering. the AI mood tracker did not need a bigger model. it needed a cost architecture that could run forever on a small budget without sacrificing quality.

every constraint is just a problem that has not been solved yet. I enjoy solving them.

---

### a few things I believe

the best engineers I have met do not wait to be unblocked. they find a way or build one.

systems should fail loudly or not at all. silent failures are a form of lying.

the hardest part of any AI system is not the model. it is the plumbing around it, the cost management, the fallback logic, the evaluation, the part that keeps it working at 3am.

if you are not slightly embarrassed by your side projects, you are not building interesting enough things.

frontend is just backend with more opinions about spacing.

---

<p align="center">
  <img width="48%" src="https://github-readme-streak-stats.herokuapp.com/?user=fazenecture&theme=tokyonight" />
</p>

<p align="center">
  <a href="mailto:vivekkumarsingh2002@gmail.com">email</a> •
  <a href="https://linkedin.com/in/vivek-kumarsingh">linkedin</a> •
  <a href="https://twitter.com/fazenecture">twitter</a>
</p>
