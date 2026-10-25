# Portfolio Index

Public index of my technical development projects.
Focus areas: Python, QA automation, agentic systems, APIs, data quality, desktop apps, and testable architecture.

**Latest update:** the portfolio now includes the Agentic QA Triage application and a clearer
verification path for every technical repository. See [the changelog](CHANGELOG.md).

## Professional Profile
- Python / QA Automation developer with hands-on testing and automation mindset.
- Building deterministic, testable applications instead of black-box demos.
- Comfortable with data validation, API testing workflows, agentic application boundaries, desktop tooling, and CI.
- Secondary track: Blender 3D portfolio for visual design execution and presentation quality.

## Quick Review Path (15 Minutes)
1. [Agentic QA Triage](https://github.com/teogame3d-alt/agentic-qa-triage) - structured agent workflow, approval gates, persistence, usage tracking, and CI.
2. [Python Live QA Studio](https://github.com/teogame3d-alt/pylive-qa-studio) - live diagnostics, traceback explanation, syntax learning coach, privacy-safe output.
3. [QA Automation API Suite](https://github.com/teogame3d-alt/qa-automation-api-suite) - dedicated API automation tests with CI.
4. [AI Agent Text RO](https://github.com/teogame3d-alt/ai-agent-text-ro) - user-trainable RO/EN agent, SQLite memory, PyQt6 UI.
5. [Interactive Data Viz](https://github.com/teogame3d-alt/interactive-data-viz) - ETL-style cleaning with validation and interactive analytics.
6. [PyQt6 Magic Shop](https://github.com/teogame3d-alt/pyqt6-magic-shop) - desktop CRUD app with layered architecture and tests.
7. [Digital Library](https://github.com/teogame3d-alt/digital-library) - concise OOP and persistence fundamentals demo.

## What To Verify
- Run tests where available with `python -m pytest`.
- Check each README for setup, demo flow, current limits, and engineering notes.
- Inspect screenshots as proof of running UI/data flows, not as replacement for code review.
- Review docs for design choices: why a deterministic rule was used, what is covered by tests, and what remains future work.

## Project Status Labels
- Working repository: source code, setup steps, tests, CI or documented validation path.
- Local prototype: experimental build used to validate one technical idea.
- Frontend / visual showcase: presentation layer, UI study or Blender/brand work, not a finished product claim.
- Learning baseline: compact project kept because it proves fundamentals clearly.

This portfolio presents focused working projects with explicit scope, verification paths, and honest
limitations; it does not claim that every repository is a finished commercial product.

## Visual Review

Screenshots are included to make the technical review faster. UI projects show real interfaces;
CLI/API projects use honest evidence boards that summarize architecture, tests, and behavior.

<p>
  <a href="https://github.com/teogame3d-alt/pylive-qa-studio">
    <img src="docs/images/pylive-demo-overview.png" width="48%" alt="Python Live QA Studio overview">
  </a>
  <a href="https://github.com/teogame3d-alt/qa-automation-api-suite">
    <img src="docs/images/qa-api-suite.png" width="48%" alt="QA Automation API Suite overview">
  </a>
</p>

<p>
  <a href="https://github.com/teogame3d-alt/pyqt6-magic-shop">
    <img src="docs/images/magic-shop-ui.png" width="32%" alt="PyQt6 Magic Shop UI">
  </a>
  <a href="https://github.com/teogame3d-alt/interactive-data-viz">
    <img src="docs/images/data-viz-chart.png" width="32%" alt="Interactive Data Viz dashboard">
  </a>
  <a href="https://github.com/teogame3d-alt/ai-agent-text-ro">
    <img src="docs/images/ai-agent-text-ro.png" width="32%" alt="AI Agent Text RO UI">
  </a>
</p>

<p>
  <a href="https://github.com/teogame3d-alt/digital-library">
    <img src="docs/images/digital-library.png" width="48%" alt="Digital Library overview">
  </a>
</p>

## Project Matrix

| Project | Role of Project | Main Skills Demonstrated | Quality Signals |
| --- | --- | --- | --- |
| [Agentic QA Triage](https://github.com/teogame3d-alt/agentic-qa-triage) | Agentic workflow and QA operations prototype | structured outputs, approval gates, persistence, usage tracking, provider boundaries | tests, CI, architecture and cost notes |
| [Python Live QA Studio](https://github.com/teogame3d-alt/pylive-qa-studio) | Developer tool / QA learning assistant | AST diagnostics, traceback explanation, syntax coaching, privacy-safe output | tests, CI, screenshots, security/privacy notes |
| [QA Automation API Suite](https://github.com/teogame3d-alt/qa-automation-api-suite) | API test automation | pytest, requests, contract checks, CI pipelines | dedicated QA scope |
| [AI Agent Text RO](https://github.com/teogame3d-alt/ai-agent-text-ro) | User-trainable AI agent concept | learning queue, approved answers, policy rules, SQLite memory | tests, CI, architecture docs |
| [Interactive Data Viz](https://github.com/teogame3d-alt/interactive-data-viz) | Data cleaning + visual analytics | pandas ETL, data contracts, metrics, visual explainability | tests, CI, modular structure |
| [PyQt6 Magic Shop](https://github.com/teogame3d-alt/pyqt6-magic-shop) | Offline desktop business app | PyQt6, repository/service layers, SQLite | tests, CI, separation of concerns |
| [Digital Library](https://github.com/teogame3d-alt/digital-library) | Compact OOP baseline | domain modeling, CLI flows, JSON persistence | tests, clear scope |

## Build Notes and Tradeoffs
- Python Live QA Studio is kept deterministic first so runtime feedback can be tested before adding heavier editor features.
- Agentic QA Triage keeps the provider boundary explicit so agent behaviour, approvals, persistence, and usage can be inspected independently.
- QA Automation API Suite uses a public demo API; that keeps setup simple, but the repository documents contract assumptions and negative-path behavior.
- AI Agent Text RO avoids hidden external services in the core path so learning, memory, and policy behavior remain inspectable.
- UI projects separate business logic from presentation so tests can verify the important behavior without depending on screenshots.
- The portfolio is intentionally focused: new repositories should add a distinct skill, not duplicate an existing proof.

## Portfolio Boundaries

- Each public repository has one primary role; I avoid publishing duplicate demos that prove the same skill twice.
- Game/visual QA work is treated as a future track only when it can be shown safely: dataset validation, model evaluation, training configuration, and reports.
- Public computer-vision demos should not include live input automation, private browser profiles, local paths, logs, model checkpoints, or machine-specific artifacts.
- Brand direction: TeoGame3D, with development as the primary public GitHub track and 3D as a separate visual track.

## Technical Stack Snapshot
- Python
- PyQt6
- SQLite
- pandas / NumPy
- matplotlib / mplcursors
- pytest + GitHub Actions

## System Health

- Package-style projects install with `python -m pip install -e .`.
- Automated tests are available through `python -m pytest`.
- UI projects have smoke-checked PyQt6 startup paths.
- Data projects have smoke-checked report/dashboard generation.
- Public files are scanned for local machine paths, tokens, and private environment references.

## Notes
- Repositories are intentionally scoped for clarity and fast technical review.
- Each project README includes problem, solution, setup, and test commands.

## Build vs Polish Transparency
- Core features in each repo are supported by readable code, tests, documentation, and screenshots where useful.
- Public repositories are kept focused so each project role is easy to understand quickly.
- New public projects are added only when they demonstrate a distinct skill that the current portfolio does not already show.

## 3D Portfolio (Blender)
- Public site: https://teogame3d-site.pages.dev/
- Focus: stylized + realistic renders, animated previews, and branded presentation.

