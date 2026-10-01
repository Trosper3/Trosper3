# Hi, I'm Michael Trosper

**Software Engineer | Computer Science at Idaho State University | USMC Veteran**

I build systems that turn hard computational theory into tools people can actually use, and I care about the engineering around the code just as much as the code itself: tests, CI gates, containerized deploys, and secure input handling. With a background as a United States Marine, I bring a disciplined, high-ownership approach to every project, from team research platforms to solo game engines.

My work spans C# web APIs, Python services, React/Next.js frontends, native C++ game development, Android apps, and Lua/C++ game modding.

---

### Featured Work

#### Redux: Computational Theory Knowledgebase (Idaho State University)
An interactive platform for canonical CS problems, solvers, verifiers, and reductions, built around Karp's 21 NP-Complete problems and extending into P, NP-Hard, and quantum classes. I am one of the most active contributors across the team's repositories.
* **Backend (C#, ASP.NET Core, .NET 10):** Top committer by identity. Added DFA/NFA acceptance, Min-Cut (Stoer-Wagner), Min s-t Cut (Edmonds-Karp), and two NP-Hard pump scheduling problems along with NP-Hard support in the catalog. Built the problem/reduction tagging taxonomy, a weighted shortest-path reduction finder, a health endpoint, and structured 400 errors with regex timeouts. Primary author of the backend test suite, and added the CI format-check gate.
* **Official Frontend (Next.js, React, MUI, D3):** Top committer. Built faceted browse filters, complexity and solver tags, centralized theming and dark mode, weighted graph edge labels, automata table visualizations, contributor stat popups, keyboard accessibility, and fixes for a ReDoS-prone regex and npm audit findings.
* **Interactive Frontend (Next.js, React, d3-force, dnd-kit, Playwright):** Sole author of a redesigned frontend: a searchable faceted catalog, problem pages with reorderable sections, live solver and verifier runs through an API proxy, step-by-step playback, drag-to-edit visualizations, a reduction network graph, and shareable course playlists.
* **SPADE (C#, ANTLR4):** Extended the discrete math parsing language that Redux uses for problem instances, adding multisets, a one-pass instance scanner, order-independent set hashing, type-check constraints, and a test project.

#### SARE 2026: Water Allocation Research Lab
A research visualization lab that models agricultural water allocation as a chain of reductions: max-flow/min-cut on the pipe network, branch-and-bound farm selection with an FPTAS fallback, and NP-Hard scheduling through graph coloring, bin packing, and job-shop. Linked views re-solve every phase live when a pipe changes. The project also includes animated walkthroughs of automata, SAT, TSP, knapsack, convex hull, and more.
* **Stack:** Python, FastAPI, Pydantic, pytest, an optional C++ solver bound with pybind11, and a React/TypeScript/Vite frontend. The pump scheduling work was ported into mainline Redux.

#### Star Reach: Top-Down Space Game (Solo)
An independent game in C++20 with modular ship engineering, localized hardpoint damage, a multi-tier economy, and ten factions with distinct behaviors.
* **Stack:** CMake presets, vcpkg, raylib, EnTT (ECS), nlohmann/json, and Catch2 unit and integration tests.
* **Engineering:** About 50k lines of C++ across 165 commits, with GitHub Actions running clang-format, clang-tidy, a matrix build, and custom structural checks that enforce layer boundaries and size limits.
* **Earlier prototype:** A previous version used Box2D physics, Dear ImGui, a seeded procedural galaxy, and ENet LAN multiplayer with client-side prediction.

#### Battlezone: Combat Commander Modding (United War)
Contributor to *United War*, a total overhaul mod on the Steam Workshop.
* **mtcampaign.dll (C++17, BZCC mission SDK):** A mission DLL that wraps the stock Lua mission runtime to add branching campaigns: per-pilot save tracking, outcomes that persist across missions, generated campaign menus with mission locks, non-destructive campaign resets, and support for several mods side by side.
* **Lua mission scripting:** Wrote a reusable mission module library (ambush waves, cutscene cameras, dropships, escorts, guard groups, objectives) and the multi-phase mission *Operation: Shard*, plus a "War Room" campaign timeline and achievements screen.
* **UI work:** Reworked the in-game HUD layout and added a campaign reset flow to the main menu.

#### Applied Projects
* **Job Search API (Python, FastAPI, httpx, Docker):** An async middleware service on the live Adzuna labor market API that computes salary statistics and extracts trending technical skills from job descriptions. CI enforces an 80% test coverage gate.
* **Student Productivity App (Kotlin, Android):** A native Android app for managing coursework, built with a two-person team. I built the CameraX document scanner and PDF system, the ML Kit OCR pipeline that turns scanned pages into assignments, the interactive campus map, the video lecture tool with transcript search, and the home page. I also led the full refactor into a feature-based MVVM structure and added due-date notifications and a light/dark theme. The app also uses Room with Flow/LiveData, Coroutines, and Canvas LMS sync through Retrofit.
* **Workforce Ops App (in progress):** A security-focused, multi-tenant scheduling platform with RBAC and a tamper-evident audit log. The backend uses FastAPI, SQLAlchemy, Alembic, and MySQL in Docker. The project runs on protected branches, required reviews, written decision records, and full CI/CD on both repos.
* **WiFi Device Scanner (C#, SharpPcap):** A network monitor that scans the local network every minute and flags devices that are not on a MAC allowlist.

---

### Technical Toolkit

**Languages:**
C# | C++ | Python | TypeScript/JavaScript | Kotlin | Lua | C | Java | SQL | HTML/CSS

**Backend & Data:**
ASP.NET Core | FastAPI | Pydantic | SQLAlchemy | Alembic | MySQL | REST API design | Swagger/OpenAPI

**Frontend:**
Next.js | React | Material UI | D3 | dnd-kit | Vite

**Mobile:**
Android SDK | Jetpack Compose | Room | Retrofit | CameraX | ML Kit | Coroutines/Flow | Gradle

**Systems & Games:**
CMake | vcpkg | raylib | EnTT | Box2D | ENet | Dear ImGui | pybind11 | ANTLR4 | MSVC

**Testing, DevOps & Security:**
xUnit | pytest | Playwright | Catch2 | Vitest | GitHub Actions | Docker | CodeQL | clang-tidy | Linux | AWS | Wireshark | SharpPcap

---

### Operational Philosophy
*"Translated high-level strategic directives into actionable execution under high-pressure conditions."* My transition from military operations and classified data compliance into software engineering means I build systems with defense in depth in mind. I treat every codebase like an operation: plan it, gate it, test it, and own it all the way through deployment.

**Let's connect:** https://www.linkedin.com/in/michael-trosper-634258237/
