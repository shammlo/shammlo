Hi, I'm Shamlo, aka Zoth <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="25px" height="25px">
========================

**Full-stack engineer with a QA lead's instincts.** I build products end to end: architecture, backend, UI, deployment, and the tests that keep them honest.

--------------------------

I've been building full-stack for years, including through a Senior QA Lead role, and I still build like a tester: strict types at the boundaries, failure modes designed in rather than discovered in production. These days I build vertical SaaS products for businesses in Kurdistan, mostly on Next.js, NestJS, and PostgreSQL, from my terminal in Neovim.

### 🧱 What I'm building

Each one links to a full case study: the architecture, the decisions, and the ones I got wrong.

- **[Dentra](https://shamlo.dev/projects/healthcare-management-platform)** — Clinic platform, in production. One fully isolated deployment per customer: separate container, separate database, separate object storage, because a tenancy bug in a system holding patient records is a breach rather than a bug. 27 backend modules, 70 test suites, five gates that refuse to boot on an unsafe config.
- **[Atlas](https://shamlo.dev/projects/property-management-platform)** — Real-estate operations platform, and the oldest codebase in the family. Its commercial model lives inside the transactions: plan limits and capability tiers enforced under row locks in the same transaction as the write, not checked on a billing page. Ships in Kurdish, Arabic and English, two of them right to left.
- **[ZothKit](https://shamlo.dev/projects/zothkit)** — The shared foundation under those products: auth, permissions, translations, audit, storage, settings. Extracted too early, which is its own lesson, and now extracted only once real duplication exists and the copies it replaced are deleted.
- **[Jinara](https://shamlo.dev/projects/agency-operations-platform)** — Internal agency operations: clients, contracts, payments, responsibilities.
- **[Azoth](https://shamlo.dev/engineering)** — My engineering platform: what I've learned across software engineering, written in public. Architecture, testing, tooling, and the reasoning behind the decisions.
- **[zoth-skills](https://github.com/shammlo/zoth-skills)** — Open-source Claude Code skills for developers, including Dev Council, a multi-advisor architecture review.
- **[Spectarum](https://shamlo.dev/projects/spectarum-playwright-automation-framework)** — Playwright automation framework that treats quality engineering as infrastructure. A module declares its schema and endpoints; the framework generates the CRUD suite, resolves IDs at runtime, and cleans up what it created.

> The products are private, so the case studies are the code review: what was built, what broke, and what I would do differently.

### 🧭 How I work

- **Make the unsafe state unrepresentable, not forbidden.** A convention you have to remember gets forgotten. A system that refuses to boot on a single-bucket storage config, or a permission check that fails closed on an empty requirement list, does not.
- **Enforce at the layer that cannot be bypassed.** Entitlement checks run inside the transaction under a row lock, not in a button's disabled state. Public projections are built up from what is safe to show, never down from the internal record, because subtraction fails open the day someone adds a column.
- **Validate everything before writing anything.** Bulk imports report every problem across the whole file before a single row lands, because the person fixing it wants the list, not the first error.
- **Write down what was rejected and why.** A deferral without stated reopening criteria is indistinguishable from an oversight six months later.

### 📫 Find me

* 🌍  Based in Erbil, Kurdistan
* 🖥️  <a href="https://shamlo.dev">shamlo.dev</a> — projects, docs, tools, and writing
* 📄  Resume: <a href="https://shamlo.dev/resume" target="_blank">PDF</a>
* ✉️  [zothstic@gmail.com](mailto:zothstic@gmail.com)
* 💼  [LinkedIn](https://www.linkedin.com/in/shamlo-ameer-126289142/) · [X](https://www.twitter.com/Shamlo_)
* 🦀  Currently learning Rust
* 🤝  Open to collaborating on TypeScript, Next.js, and NestJS projects
* 🧘  Off the keyboard: reading, meditation, philosophy, and worldbuilding

---

### 🛠️ Skills

#### Programming Languages
<p>
  <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" title="JavaScript"><img src="https://go-skill-icons.vercel.app/api/icons?i=javascript" width="40" /></a>
  <a href="https://www.typescriptlang.org/" title="TypeScript"><img src="https://go-skill-icons.vercel.app/api/icons?i=typescript" width="40" /></a>
  <a href="https://nodejs.org/" title="Node.js"><img src="https://go-skill-icons.vercel.app/api/icons?i=nodejs" width="40" /></a>
  <a href="https://bun.sh/" title="Bun.js"><img src="https://go-skill-icons.vercel.app/api/icons?i=bun" width="40" /></a>
  <a href="https://www.lua.org/" title="Lua"><img src="https://go-skill-icons.vercel.app/api/icons?i=lua" width="40" /></a>
  <a href="https://developer.mozilla.org/en-US/docs/Web/HTML" title="HTML"><img src="https://go-skill-icons.vercel.app/api/icons?i=html" width="40" /></a>
  <a href="https://developer.mozilla.org/en-US/docs/Web/CSS" title="CSS"><img src="https://go-skill-icons.vercel.app/api/icons?i=css" width="40" /></a>
  <a href="https://sass-lang.com/" title="SCSS / SASS"><img src="https://go-skill-icons.vercel.app/api/icons?i=scss" width="40" /></a>
  <a href="https://www.gnu.org/software/bash/" title="Bash"><img src="https://go-skill-icons.vercel.app/api/icons?i=bash" width="40" /></a>
</p>

#### Frontend: Frameworks, Libraries & Services
<p>
  <a href="https://reactjs.org/" title="React"><img src="https://go-skill-icons.vercel.app/api/icons?i=react" width="40" /></a>
  <a href="https://reactnative.dev/" title="React Native"><img src="https://go-skill-icons.vercel.app/api/icons?i=reactnative" width="40" /></a>
  <a href="https://nextjs.org/" title="Next.js"><img src="https://go-skill-icons.vercel.app/api/icons?i=nextjs" width="40" /></a>
  <a href="https://tailwindcss.com/" title="Tailwind CSS"><img src="https://go-skill-icons.vercel.app/api/icons?i=tailwindcss" width="40" /></a>
  <a href="https://redux.js.org/" title="Redux"><img src="https://go-skill-icons.vercel.app/api/icons?i=redux" width="40" /></a>
  <a href="https://tanstack.com/query/latest" title="React Query"><img src="https://go-skill-icons.vercel.app/api/icons?i=reactquery" width="40" /></a>
  <a href="https://www.chartjs.org/" title="Chart.js"><img src="https://go-skill-icons.vercel.app/api/icons?i=chartjs" width="40" /></a>
  <a href="https://authjs.dev/" title="Auth.js"><img src="https://go-skill-icons.vercel.app/api/icons?i=authjs" width="40" /></a>
  <a href="https://www.apollographql.com/" title="Apollo"><img src="https://go-skill-icons.vercel.app/api/icons?i=apollo" width="40" /></a>
  <a href="https://zustand-demo.pmnd.rs/" title="Zustand"><img src="https://go-skill-icons.vercel.app/api/icons?i=zustand" width="40" /></a>
  <a href="https://ui.shadcn.com/" title="Shadcn"><img src="https://go-skill-icons.vercel.app/api/icons?i=shadcn" width="40" /></a>
</p>

#### Backend: Frameworks, Databases, Libraries & Services
<p>
  <a href="https://expressjs.com/" title="Express.js"><img src="https://go-skill-icons.vercel.app/api/icons?i=expressjs" width="40" /></a>
  <a href="https://nestjs.com/" title="NestJS"><img src="https://go-skill-icons.vercel.app/api/icons?i=nestjs" width="40" /></a>
  <a href="https://developer.mozilla.org/en-US/docs/Web/API/WebSockets_API" title="WebSockets"><img src="https://go-skill-icons.vercel.app/api/icons?i=websocket" width="40" /></a>
  <a href="https://kafka.apache.org/" title="Apache Kafka"><img src="https://go-skill-icons.vercel.app/api/icons?i=kafka" width="40" /></a>
  <a href="https://www.rabbitmq.com/" title="RabbitMQ"><img src="https://go-skill-icons.vercel.app/api/icons?i=rabbitmq" width="40" /></a>
  <a href="https://www.postgresql.org/" title="PostgreSQL"><img src="https://go-skill-icons.vercel.app/api/icons?i=postgresql" width="40" /></a>
  <a href="https://www.mongodb.com/" title="MongoDB"><img src="https://go-skill-icons.vercel.app/api/icons?i=mongodb" width="40" /></a>
  <a href="https://www.prisma.io/" title="Prisma ORM"><img src="https://go-skill-icons.vercel.app/api/icons?i=prisma" width="40" /></a>
  <a href="https://mongoosejs.com/" title="Mongoose"><img src="https://go-skill-icons.vercel.app/api/icons?i=mongoose" width="40" /></a>
  <a href="https://orm.drizzle.team/" title="Drizzle ORM"><img src="https://go-skill-icons.vercel.app/api/icons?i=drizzle" width="40" /></a>
  <a href="https://graphql.org/" title="GraphQL"><img src="https://go-skill-icons.vercel.app/api/icons?i=graphql" width="40" /></a>
  <a href="https://socket.io/" title="Socketio"><img src="https://go-skill-icons.vercel.app/api/icons?i=socketio" width="40" /></a>
</p>

#### General Tooling & DevOps
<p>
  <a href="https://pnpm.io/" title="pnpm"><img src="https://go-skill-icons.vercel.app/api/icons?i=pnpm" width="40" /></a>
  <a href="https://neovim.io/" title="Neovim"><img src="https://go-skill-icons.vercel.app/api/icons?i=neovim" width="40" /></a>
  <a href="https://www.linux.org/" title="Linux"><img src="https://go-skill-icons.vercel.app/api/icons?i=linux" width="40" /></a>
  <a href="https://www.postman.com/" title="Postman"><img src="https://go-skill-icons.vercel.app/api/icons?i=postman" width="40" /></a>
  <a href="https://www.docker.com/" title="Docker"><img src="https://go-skill-icons.vercel.app/api/icons?i=docker" width="40" /></a>
  <a href="https://kubernetes.io/" title="Kubernetes"><img src="https://go-skill-icons.vercel.app/api/icons?i=kubernetes" width="40" /></a>
  <a href="https://www.jenkins.io/" title="Jenkins"><img src="https://go-skill-icons.vercel.app/api/icons?i=jenkins" width="40" /></a>
  <a href="https://git-scm.com/" title="Git"><img src="https://go-skill-icons.vercel.app/api/icons?i=git" width="40" /></a>
  <a href="https://nginx.org/" title="NGINX"><img src="https://go-skill-icons.vercel.app/api/icons?i=nginx" width="40" /></a>
  <a href="https://webpack.js.org/" title="Webpack"><img src="https://go-skill-icons.vercel.app/api/icons?i=webpack" width="40" /></a>
</p>

#### Testing & Quality Assurance
<p>
  <a href="https://jestjs.io/" title="Jest"><img src="https://go-skill-icons.vercel.app/api/icons?i=jest" width="40" /></a>
  <a href="https://www.cypress.io/" title="Cypress"><img src="https://go-skill-icons.vercel.app/api/icons?i=cypress" width="40" /></a>
  <a href="https://playwright.dev/" title="Playwright"><img src="https://go-skill-icons.vercel.app/api/icons?i=playwright" width="40" /></a>
  <a href="https://testing-library.com/" title="Testing Library"><img src="https://go-skill-icons.vercel.app/api/icons?i=testinglibrary" width="40" /></a>
  <a href="https://www.selenium.dev/" title="Selenium"><img src="https://go-skill-icons.vercel.app/api/icons?i=selenium" width="40" /></a>
  <a href="https://pptr.dev/" title="Puppeteer"><img src="https://go-skill-icons.vercel.app/api/icons?i=puppeteer" width="40" /></a>
  <a href="https://mochajs.org/" title="Mocha"><img src="https://go-skill-icons.vercel.app/api/icons?i=mocha" width="40" /></a>
</p>

---

### 📊 GitHub Stats

![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=shammlo&stroke=ffffff&background=000000&ring=10b981&fire=10b981&currStreakNum=ffffff&currStreakLabel=10b981&sideNums=ffffff&sideLabels=ffffff&dates=ffffff&hide_border=true)

![My GitHub Game](game.gif)
