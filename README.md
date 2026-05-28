# Nursing Qualitative Skills

A reusable AI skills repository for nursing qualitative research writing.

This repository currently contains one core skill:

- `nursing-qualitative-writing`: an AI writing skill for drafting, revising, structuring, and critically improving qualitative nursing research manuscripts.

The skill is designed for manuscript preparation and revision for nursing and health-care journals such as:

- International Journal of Nursing Studies
- Journal of Advanced Nursing
- Nurse Education Today
- Nurse Education in Practice
- BMC Nursing
- Journal of Clinical Nursing
- Geriatric Nursing

## Repository structure

```text
nursing-qualitative-skills/
├── README.md
├── LICENSE
├── .gitignore
├── install.sh
└── skills/
    └── nursing-qualitative-writing/
        ├── SKILL.md
        ├── README.md
        ├── examples/
        │   └── prompts.md
        └── references/
            ├── ijns-style-guide.md
            ├── qualitative-methods-guide.md
            ├── results-writing-guide.md
            ├── discussion-writing-guide.md
            └── factuality-ethics-guide.md
```

## Installation

### Option 1: Install all skills

From the repository root:

```bash
bash install.sh
```

Then restart Codex or your AI agent.

### Option 2: Manual installation

Copy the full skill folder into your Codex skills directory:

```bash
mkdir -p ~/.codex/skills
cp -R skills/nursing-qualitative-writing ~/.codex/skills/
```

Then restart Codex.

## Example use

After installation, you can ask:

```text
Use nursing-qualitative-writing to revise the Introduction section in an IJNS-style funnel structure.
```

```text
Use nursing-qualitative-writing to rewrite the Results section using theme-level analytic paragraphs, subtheme explanations, and participant quotations.
```

```text
Use nursing-qualitative-writing to check this manuscript against COREQ/SRQR and identify missing reporting items.
```

## Important principles

This skill is designed to help with academic writing, but it must not fabricate:

- participant numbers;
- participant characteristics;
- recruitment sites;
- interview dates or duration;
- themes or subthemes;
- participant quotations;
- ethics approval numbers;
- analytic procedures;
- software use;
- saturation or information power;
- member checking;
- references;
- journal requirements.

If information is missing, the assistant should flag the missing item and use a placeholder rather than inventing details.

## License

This repository is released under the MIT License.
