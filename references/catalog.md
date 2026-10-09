# Agent Skills Master Catalog

This catalog serves as the reference database for `skill-suggester` to recommend the right tool for every software engineering challenge.

---

## 1. Core Engineering & Quality

### `tdd` & `tdd-workflow`
* **Trigger:** Building new features, writing units, adding test coverage, refactoring.
* **Why:** Enforces Red-Green-Refactor, public interface verification, vertical slicing, and prevents tautological or implementation-coupled tests.

### `diagnosing-bugs`
* **Trigger:** Error messages, stack traces, race conditions, unexpected regressions, performance bottlenecks.
* **Why:** Enforces a disciplined 6-phase loop (tight feedback loop $\rightarrow$ minimal repro $\rightarrow$ ranked hypotheses $\rightarrow$ targeted probes $\rightarrow$ regression test $\rightarrow$ cleanup).

### `ponytail`
* **Trigger:** Code simplification, avoiding bloat, YAGNI, boilerplate reduction, minimal diffs.
* **Why:** Channels a "lazy senior developer" ladder: checks whether code is needed at all, uses stdlib/native features, and rejects unnecessary abstractions.

---

## 2. Architecture & Design

### `blueprint`
* **Trigger:** Starting large features, multi-PR projects, complex migrations, long-running agent tasks.
* **Why:** Creates self-contained, cold-start execution plans with dependency graphs and adversarial review gates.

### `improve-codebase-architecture`
* **Trigger:** Tangled dependencies, shallow modules, low locality, leaking seams.
* **Why:** Produces visual HTML before/after architecture reports (using Mermaid) to deepen modules and simplify systems.

### `grill-me`
* **Trigger:** Unclear specifications, product planning, architecture vetting before coding.
* **Why:** Conducts a relentless depth-first interview to uncover hidden assumptions and clarify requirements.

### `code-review`
* **Trigger:** Reviewing PRs, git diffs, inspecting changes between commits/branches.
* **Why:** Parallel two-axis evaluation: documented coding standards vs. originating requirements/specifications.

---

## 3. Autonomous Agents & AI Systems

### `agents-best-practices`
* **Trigger:** Building agentic systems, AI workers, tool design, evaluation harnesses, memory lifecycles.
* **Why:** Provider-neutral blueprint covering loops, approvals, permissions, speculative execution, prompt caching, and evals.

---

## 4. Cloud, Data & Infrastructure

### `gcp-data-pipelines` & `bigquery-sql`
* **Trigger:** ETL workflows, SQL optimizations, data warehouse modeling, streaming pipelines.
* **Why:** Best practices for cloud data processing, cost-effective SQL, and resilient data architectures.

### `ci-cd-and-automation`
* **Trigger:** GitHub Actions, deployment pipelines, containerization, quality gates.
* **Why:** Repeatable build and release automation with automated testing and security scans.
