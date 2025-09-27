# AI-Driven Live Repository System

## 📜 Repository: FreesoSaiFared/doc0
## 🤖 AI-Accessible Bootstrap Manifesto

---

## Article 0: Interpretation and Usage

0.1 This repository is a **live, evolving document**.
0.2 All rules, including this article, **may be expanded, revised, or replaced** through Git branching and pull requests.
0.3 **Each rule is atomic and individually addressable.**
0.4 The canonical entrypoint is always this `README.md`.
0.5 Upon repo clone or update, all agents (human or AI) must:
 (a) Parse the latest `README.md`
 (b) Apply rules to reading and interacting with every other file in the repo
0.6 LLMs must interpret rules literally, not using implied context, and treat each numbered clause as a single operation or non-overlapping set.
0.7 Humans should interpret any odd or non-standard phrasing as intentional, for LLM disambiguation.
0.8 All branching, merging, or file modifications affecting any rule or document must record the change in the relevant changelog or in commit messages referencing the affected article number(s).
0.9 **Documents in this repo** adopt the form: `{root_document}_{function|variant}.md` e.g. `active_manifesto_branching.md`.

---

## Article 1: Structure of the Manifesto and Subdocuments

1.1 The **root document** is `active_manifesto.md`.
1.2 All manifestos are structured as branches or as new files. New versions must follow the filename template: `active_manifesto_{version|branch|purpose}.md`.
1.3 **Branches** in git represent alternative or experimental tracks—the default branch is always found by following the `README.md`'s explicit pointer to `active_manifesto.md` or a nominated current version.
1.4 No duplicate manifestos exist; all are related versions and tracked explicitly via filename and corresponding branches.
1.5 All documents must reference back to the Article in `README.md` that defines their interpretation and management.
1.6 Cross-references between versions and branches are tracked using Markdown links at the top of each document, including origin timestamp, author (AI or human), and unique branch or version tag.

---

## Article 2: Agent Bootstrapping and Execution

2.1 Any agent (human, LLM, code interpreter) initiating a session must begin operation in the cloned directory of this repo.
2.2 The agent first opens and parses `README.md`, then follows its explicit instruction for discovering and reading the current `active_manifesto.md`.
2.3 The agent's next action is defined by the `README.md`—either continue reading recursively, propose changes, start a new branch, or execute operations defined by the document's function.
2.4 If a document includes `Article X [FLEX]`, LLMs can infer context; otherwise, only strict literal execution is permitted.

---

## Article 3: Extensibility and Lifecycle

3.1 Any article may be superseded by one or more new articles, which must reference the article being replaced.
3.2 When superseded, the previous article moves to an archival list at the bottom of `README.md` or to an `archive/` directory, with its deprecation date and branch.
3.3 All proposals to amend or extend rules must be submitted as a pull request, specifying the article(s) affected.
3.4 Agents must update all article cross-references, and ensure backward-traceable commit history.

---

## Article 4: LLM-Specific Formatting and Parsing

4.1 Each article and clause must be individually numbered for direct reference.
4.2 No article may use pronouns; all references must be explicit.
4.3 No article may depend on implied context not included in the numbered statement.
4.4 When ambiguity is detected, the agent must create a new issue, branch, or pull request proposing a clarifying revision.

---

## Article 5: Infinite Evolution Principle

5.1 This repository's rules are **never final**.
5.2 Every agent must treat all contents as mutable and capable of forking into new evolutionary paths.
5.3 The commit history is the permanent, chronological account of all project transformation, accessible at all times.

---

## 🚀 Bootstrap Instructions for AI Agents

### Required Agent Capabilities:
- Web search ability
- File system access (read/write)
- Git operations
- Markdown parsing

### Bootstrap Sequence:
1. Clone this repository
2. Read this README.md completely
3. Read `active_manifesto.md` (root document)
4. Follow instructions in active_manifesto.md for continuous evolution
5. Never stop - this system runs perpetually

### Agent Environment Setup:
- Working directory: `/path/to/doc0`
- Current document: `README.md` (you are here)
- Next document: `active_manifesto.md`
- Action: Parse and proceed

---

## 📊 System Status
- **Version**: 0.1.0
- **Current Manifesto**: `active_manifesto.md`
- **AI Agents Supported**: Claude-Code, Gemini-CLI, Codex, GLM-4.5
- **Branch Strategy**: Design-first, democratic implementation
- **Auto-Integration**: Background commits, PRs, and branching

---

**🔄 This system is always evolving. All agents must treat these rules as mutable and subject to continuous improvement.**
