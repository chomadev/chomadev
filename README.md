<h1>Hey, I'm Marcos Braga Choma 👋</h1>

<div>
Developer based in São Paulo, Brazil, with almost 25 years of experience across a wide range of stacks —
from industrial equipment monitoring in C#/WPF to AI-integrated SaaS products and local-first AI tooling.
These days I'm especially into wiring LLMs (local and hosted) into real, working software rather than demos.
</div>

<br />
<div align="center">
  <img src="https://skillicons.dev/icons?i=dotnet,cs,ts,js,react,nextjs,angular,postgres,docker,aws,azure,git,express,tailwind,supabase" />
</div>
<br />

## Featured projects

**[file-analysis](https://github.com/chomadev/file-analysis)** — A local-first file indexing and cleanup CLI. Scans a directory
tree, analyzes file content with a local Ollama model (nothing leaves the machine), and stores everything in
PostgreSQL + pgvector for full-text and semantic search. Includes an AI-assisted directory survey that flags
junk/build folders before indexing, and a human-approved cleanup workflow (duplicate + staleness detection,
quarantine-based removal — never a silent delete). Exposed to Claude via an MCP server.

**[FinanceHelper2](https://github.com/chomadev/FinanceHelper2)** — Personal finance analyzer built with a proper
hexagonal/ports-and-adapters architecture (.NET, EF Core, PostgreSQL). Parses Nubank and C6 bank statement
exports, sends transactions to Google Gemini for categorization in batches, and aggregates recurring vs.
one-off spending by category.

**Industrial monitoring suite** — [MachineMonitor](https://github.com/chomadev/MachineMonitor) (WPF/MVVM desktop app) tracks
production equipment status — laser cutters, inkjet printers, scales, barcode readers — alongside standard
host metrics (CPU/memory/TCP ports). [MachineMonitorWeb](https://github.com/chomadev/MachineMonitorWeb) is the Angular
companion dashboard for the same machine data. [CPUTempConsole](https://github.com/chomadev/CPUTempConsole) is a
lighter standalone: a Windows tray utility reading real hardware temperatures via OpenHardwareMonitor.

**choma.dev** — A talent-matching SaaS connecting Brazilian developers with international companies: automated
PDF résumé parsing, a gamified profile-quality score, and a candidate-matching pipeline. Built as a Turborepo
monorepo (Next.js 14, tRPC, Supabase, Vitest + Playwright, Docker-based CI/CD). Currently private while it's
still an active build.

## Other things I've built

[weatherapi](https://github.com/chomadev/weatherapi) · [employees](https://github.com/chomadev/employees) (.NET + React) ·
[crazy-orders](https://github.com/chomadev/crazy-orders) (C#) · [quiz-generator](https://github.com/chomadev/quiz-generator)
(Next.js + ChatGPT API) · [share-songs](https://github.com/chomadev/share-songs) · [cd.ddd](https://github.com/chomadev/cd.ddd)
(DDD sample) · [todo-react-native](https://github.com/chomadev/todo-react-native)

<br />
<div align="center">
  <a href="mailto:marcos@choma.dev">
    <img src="https://img.shields.io/badge/Gmail-333333?style=for-the-badge&logo=gmail&logoColor=red" />
  </a>
  <a href="https://linkedin.com/in/marcosbragachoma" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank" />
  </a>
  <a href="https://choma.dev" target="_blank">
     <img src="https://img.shields.io/badge/website-FF5722?style=for-the-badge&logo=todoist&logoColor=white" target="_blank" />
  </a>
</div>
