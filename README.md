<h1 align="center">Ong Khánh Vinh</h1>

<p align="center">
  <b>Full-stack developer</b> · Final-year Information Systems student at University of Science, VNU-HCM<br />
  Ho Chi Minh City, Vietnam
</p>

<p align="center">
  <a href="https://goldfish.io.vn"><img src="https://img.shields.io/badge/Live%20product-goldfish.io.vn-0F766E?style=flat-square" alt="Live product: goldfish.io.vn" /></a>
  <a href="https://www.linkedin.com/in/vinh-kh%C3%A1nh-16063b332/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0F766E?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:ongkhanhv2005@gmail.com"><img src="https://img.shields.io/badge/Email-ongkhanhv2005%40gmail.com-0F766E?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

I like turning messy business rules into software that people can rely on: clear user flows on the front, careful handling of money and data on the back. My main work so far is a commerce platform that runs in production, built and maintained end to end by me.

**Open to product engineering and full-stack opportunities.**

---

## Featured project

### GoBot — Telegram commerce platform

Store owners sell digital products through their own Telegram bots and run the whole shop from a web dashboard.

**Live:** [goldfish.io.vn](https://goldfish.io.vn) · **Role:** solo developer · **Source:** private, walkthrough on request

**What it does**

- **One platform, many shops.** Each shop gets a customer bot and an admin bot, with its data kept separate from every other shop.
- **Web dashboard.** Products, stock, orders, customers, coupons, preorders and financial reports in one place.
- **Automatic payments.** Bank transfer by QR (SePay, MB Bank) and Binance USDT, matched to orders without manual checking.
- **Reseller API.** Partners buy through a REST API with their own API keys and can safely retry a request without being charged twice.
- **Supplier integrations.** Orders are placed with third-party providers, tracked until they finish, and refunded automatically when they fail.

**How it is built**

| Concern | Approach |
| --- | --- |
| Money safety | Database transactions, guarded wallet debits and refunds that can only ever apply once |
| No double orders | Every order is claimed before the provider is called; API clients send their own order ID for safe retries |
| Security | Hashed API keys, encrypted secrets at rest, CSRF protection, rate limits and outbound requests that cannot reach internal networks |
| Quality | 497 dashboard tests and 65 bot test suites run before every production release |

**Stack:** React · Tailwind CSS · Node.js · Express · TypeScript · PostgreSQL · Prisma · grammY · Docker · GitHub Actions

---

## More work

| Project | What it is | Built with |
| --- | --- | --- |
| [caro-game](https://github.com/venncoder08/caro-game) | Caro (five in a row) game, my first complete mini project | C++ |
| [sys-call-xv6](https://github.com/venncoder08/sys-call-xv6) | New system calls for the xv6 teaching operating system | C |
| [nodejs-blog](https://github.com/venncoder08/nodejs-blog) | Server-rendered blog | Node.js, Handlebars |
| [HW05_Automation_Testing](https://github.com/venncoder08/HW05_Automation_Testing) | Automated UI test suite with a written test report | TypeScript, Playwright |
| [HW06_API_Testing](https://github.com/venncoder08/HW06_API_Testing) | API test plans, test cases and automated checks | REST API testing |

---

## Tech stack

**Working with**

<p>
  <img src="https://skillicons.dev/icons?i=js,ts,react,tailwind,nodejs,express,prisma,postgres,redis,docker,git&perline=11" alt="JavaScript, TypeScript, React, Tailwind CSS, Node.js, Express, Prisma, PostgreSQL, Redis, Docker, Git" />
</p>

**Learning now**

<p>
  <img src="https://skillicons.dev/icons?i=java,spring,kafka,kubernetes" alt="Java, Spring Boot, Kafka, Kubernetes" />
</p>

---

## GitHub activity

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats-psi-vert.vercel.app/api?username=venncoder08&show_icons=true&hide_border=true&bg_color=00000000&title_color=2DD4BF&icon_color=2DD4BF&text_color=CBD5E1&custom_title=GitHub%20stats&count_private=true" />
    <img height="140" src="https://github-readme-stats-psi-vert.vercel.app/api?username=venncoder08&show_icons=true&hide_border=true&bg_color=00000000&title_color=0F766E&icon_color=0F766E&text_color=475569&custom_title=GitHub%20stats&count_private=true" alt="GitHub stats" />
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com/?user=venncoder08&hide_border=true&background=00000000&ring=2DD4BF&fire=2DD4BF&currStreakNum=F1F5F9&sideNums=F1F5F9&currStreakLabel=2DD4BF&sideLabels=CBD5E1&dates=94A3B8&stroke=334155" />
    <img height="140" src="https://streak-stats.demolab.com/?user=venncoder08&hide_border=true&background=00000000&ring=0F766E&fire=0F766E&currStreakNum=1F2937&sideNums=1F2937&currStreakLabel=0F766E&sideLabels=475569&dates=64748B&stroke=CBD5E1" alt="Contribution streak" />
  </picture>
</p>

<p align="center">
  <img width="92%" src="https://ghchart.rshah.org/0F766E/venncoder08" alt="Contribution calendar for the last year" />
</p>

---

<p align="center">
  Thanks for stopping by. The fastest way to reach me is <a href="mailto:ongkhanhv2005@gmail.com">email</a>.<br /><br />
  <img src="https://komarev.com/ghpvc/?username=venncoder08&style=flat-square&color=0F766E&label=Profile+views" alt="Profile views" />
</p>
