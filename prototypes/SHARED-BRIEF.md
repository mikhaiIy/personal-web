# Shared brief — Mikhail Bin Yassin personal site prototypes

Three independent prototype HTML files. These are design explorations, not production code.
Each file is built by a different agent; do NOT read or touch the other prototypes' files.

## Person (ground truth, from resume — use liberally for authentic copy)

- Mikhail Bin Yassin, hometown **Kota Belud, Sabah, Malaysia** (below Mount Kinabalu).
- Aspiring **Data Engineer**, graduating BSc Computer Science (Data Engineering), **Universiti Teknologi Malaysia (UTM), Johor Bahru**, CGPA 3.85 (Oct 2021 – Oct 2026). Foundation in Engineering at UiTM Dengkil, CGPA 4.00 (2020–21).
- Internship: **U Mobile, Data Science & Campaign Value Management dept, Data Engineering Intern, 9 months (Nov 2025 – Aug 2026)**:
  - Designed/built/deployed PySpark & Python ETL pipelines for billing, activation, reconciliation reporting — requirement gathering → UAT → production, on-premise big data platform.
  - Processed **~2 billion CDR rows/day** with PySpark for a cloud DaaS POC.
  - Analyzed inter-operator billing discrepancies / settlement root causes.
  - Automated secure cloud file transfers, variance alert emails, file permission management; built **centralized platform monitoring dashboard POC on ClickStack**.
- Final-Year Project: **"Design & Implementation of a DAG-based ETL Scheduling System"** — custom pipeline orchestration.
- Led 4-person teams in two Work-Based Learning semesters (kindergarten web app; autism education center web app) — both groups chosen **Best Group**.
- Led teams at FCRI 2025 (showcase planning, liaison with Finexus Group), SUSKOM'23 and Earth Day 2023 (multimedia lead).
- Certifications: AWS Academy Data Engineering, AWS Academy Cloud Architecting, Google AI Professional (Cloud Foundations), Microsoft Azure Data Fundamentals.
- Skills: **SQL, Python/PySpark, PostgreSQL, ClickHouse, Bash/Shell, Linux, Git, OpenTelemetry**; ETL design, big data, orchestration, web app dev.
- Interests: Data Engineering, real-time processing, **agentic engineering, LLM-era systems**, system design, cloud.
- Contact: GitHub **mikhaiIy** · LinkedIn **mikhailyassin** · email **mikhailyassin@proton.me** · phone (+60) 12-8871846.

## Hard technical constraints (all prototypes)

- ONE self-contained `.html` file each, vanilla HTML/CSS/JS. NO CDN, NO external fonts/images/requests — must render identically offline via `file://`.
- System font stacks only (e.g. `"MS Sans Serif", Tahoma, Geneva, sans-serif` / `"Courier New", monospace`). Pixel/perfect gradients are CSS. Icons/stickers are inline SVG, CSS shapes, or emoji.
- No random-crash animations; everything deterministic. Respect `prefers-reduced-motion` where heavy animation is used.
- Desktop-first (1440×900 target) but do not fall apart at 1024×768. Include `<title>` and a favicon via inline SVG data URI.
- Every interactive thing must actually work (draggable windows drag; tabs switch; hover effects run). Empty stubs forbidden.
- Real resume copy in place of lorem ipsum. Wit allowed; keep it tasteful, no lorem, no "TODO".
- Aim ≤ ~1200 lines per file. Hand in ONE file at the exact path given in your task.

## Taste notes

- The site must NOT read as generic. Avoid: hero-with-gradient-blob, three feature cards, Inter font, Tailwind look.
- Y2K maximalism = *clutter with intent*: beveled windows, marquee tickers, pixel stickers, cursor trails, window chrome — but every element carries real content or real function.
- "Developer/boy" translation of the pink dollhouse: swap pastel pink for **phosphor green / cyan / amber on dark graphite**, butterflies → circuit traces & stars, tamagotchi → pager/uptime badge, CD disc → spinning tape/logos.
