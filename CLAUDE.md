# CLAUDE.md — modus-operandi

This is a template repository. It contains no product-specific content.
Its purpose is to provide a consistent starting structure for open source
preservation, restoration, and reverse engineering projects.

---

## What this repository is

modus-operandi is the common foundation for a family of restoration projects
including Millennium (Logitech MX1000) and Michiyuki (Tomy i-SOBOT). It
defines shared conventions for structure, documentation style, licensing, and
contribution workflow.

When starting a new project from this template, the expectation is that
directory structure, file naming, license model, README voice, and
CONTRIBUTING.md format all remain consistent with this baseline unless there
is a domain-specific reason to diverge.

---

## Repository contents

- `README.template.md` — the canonical project README template; renamed to
  `README.md` in each derived project
- `CONTRIBUTING.md` — contribution guidelines template
- `.github/ISSUE_TEMPLATE/contributing-finding.md` — issue template for
  physical documentation contributions
- `LICENSE-DOCUMENTATION` — CC BY 4.0 (documentation)
- `LICENSE-FIRMWARE` — GPL-3.0 (firmware and software)
- `LICENSE-HARDWARE` — CERN-OHL-S-2.0 (hardware designs)
- `docs/`, `hardware/`, `software/`, `parts/`, `references/` — default
  directory structure; adapted per project

---

## Conventions this template encodes

**Naming:** files lowercase with hyphens. Directories lowercase, single word
where possible.

**README structure:** Project Name → vision → design philosophy → [components]
→ repository structure → current status → contributing → prior art → license
→ trademark disclaimer. Do not reorder sections without updating this template.

**License model:** all projects in this family use the same three-way split —
CERN-OHL-S-2.0 for hardware, GPL-3.0 for firmware and software, CC BY 4.0 for
documentation. Do not substitute other licenses without updating all derived
projects.

**Tone:** direct and technical. README intentionally avoids implementation
specifics — those belong in their respective directories, not the top-level
README.

**CONTRIBUTING.md structure:** code of conduct → current needs → per-type
workflow → file naming and directory conventions → measurements guidance →
license agreement.

---

## Derived projects

| Project | Subject | Repository |
|---|---|---|
| Millennium | Logitech MX1000 | jacob-rn-wallace/millennium |
| Michiyuki | Tomy i-SOBOT | jacob-rn-wallace/michiyuki |

Update this table when new projects are started from the template.