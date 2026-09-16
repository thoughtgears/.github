# Thoughtgears

**Platform engineering and cloud architecture for startups and scale-ups.**

Thoughtgears is Jens Skott — 25+ years across development, devops, sysops and
platform engineering. When you hire Thoughtgears, I am who does the work. There
is no account layer between you and the person writing the code.

Most of what I build runs on **Google Cloud**, and GCP customers are who I
prefer to work with. It isn't a limit — AWS, Cloudflare and hybrid estates are
all in scope — but if you're a GCP shop, the depth here is unusual.

<p align="center">
  <a href="https://thoughtgears.co.uk"><img src="https://img.shields.io/badge/Website-thoughtgears.co.uk-1F6FEB?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Website"></a>
  <a href="https://jensskott.com/cv/"><img src="https://img.shields.io/badge/CV-jensskott.com%2Fcv-22C55E?style=for-the-badge&logo=read-the-docs&logoColor=white" alt="CV"></a>
  <a href="https://www.linkedin.com/company/thoughtgears"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
</p>

---

## What I do

<table>
<tr>
<td width="50%" valign="top">

### Platform engineering
Internal developer platforms that speed a team up without trading away security
or compliance.

- Golden paths and self-service infrastructure
- Developer experience as a product
- Paved roads, not guardrails nobody uses

</td>
<td width="50%" valign="top">

### Cloud architecture
Designs that stay affordable as they scale, on GCP and beyond.

- Event-driven and serverless patterns
- Multi-region and disaster recovery
- Cost control and FinOps

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Fractional CTO and advisory
For companies growing faster than their architecture.

- Technical due diligence
- Team structure and hiring
- Build-vs-buy, honestly assessed

</td>
<td width="50%" valign="top">

### DevOps and SRE
Production CI/CD, observability, and infrastructure as code.

- GitOps and deployment strategy
- Security automation
- SRE practice and incident response

</td>
</tr>
</table>

---

## Open source

The tools I use daily, given away. Apache 2.0 or MIT.

| Repository | | What it is |
|---|---|---|
| **[docker-firebase-emulator](https://github.com/thoughtgears/docker-firebase-emulator)** | ⭐ 54 · 15 forks · `v1.1.0` | Modular Firebase emulator image. Multi-arch (amd64 + arm64), firebase-tools 15, Java 21 |
| **[firebase-emulator-demo](https://github.com/thoughtgears/firebase-emulator-demo)** | JavaScript | A full multi-container app built on that image — the worked example, and its integration test |
| **[the-slashinator](https://github.com/thoughtgears/the-slashinator)** | TypeScript | Cloud Function that disables billing when a GCP budget alert fires. 100% test coverage |
| **[firestore-backup](https://github.com/thoughtgears/firestore-backup)** | Go | Backup and restore Firestore collections, tested against the emulator above in CI |
| **[cloud-run-dbt](https://github.com/thoughtgears/cloud-run-dbt)** | Terraform | dbt on Cloud Run, scheduled, with the infrastructure to run it |
| **[taxmate](https://github.com/thoughtgears/taxmate)** | TypeScript | UK contractor tax calculator, inside and outside IR35. 184 tests |

---

## How I work

- **Business logic ships with tests, or it isn't done.** Engines, pricing rules
  and data transforms get the test first, and they live in pure functions — not
  buried inside a view where nothing can reach them.
- **One owner per resource.** Terraform owns durable infrastructure; deploy
  tooling owns runtime. Two systems writing the same record fight each other,
  and one of them loses quietly.
- **The least backend the problem needs.** A server is justified by shared or
  server-authoritative state, not by habit.
- **Least privilege, no long-lived keys.** Workload Identity Federation over
  service-account JSON, everywhere.

---

## Talk to me

Whether you're a founder building your first platform, a CTO whose architecture
stopped keeping up, or a team whose cloud bill has become a monthly surprise.

<p align="center">
  <a href="mailto:jens.skott@thoughtgears.co.uk">
    <img src="https://img.shields.io/badge/Email-jens.skott%40thoughtgears.co.uk-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
  </a>
  <a href="https://thoughtgears.co.uk">
    <img src="https://img.shields.io/badge/Book_a_Discovery_Call-Schedule_Now-1F6FEB?style=for-the-badge" alt="Book a Call">
  </a>
</p>
