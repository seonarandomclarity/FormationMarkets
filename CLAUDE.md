# Techdollar Investor Data Room

A private GitHub repo used as the investor data room. Investors are collaborators who browse it on github.com:
`README.md` is the home page and `DOCUMENTS.md` is the documents page.

## Sections (fixed; never rename)

| Folder | Display title |
| --- | --- |
| 01-roadmap | Roadmap |
| 02-technology | Technology |
| 03-company-structures | Company Structures |
| 04-team-and-hiring-plan | Team and Hiring Plan |
| 05-liquidity-curve | Liquidity Curve |
| 06-why-company-kpis | Why Company KPIs? |
| 07-regulatory | Regulatory |
| 08-economics | Economics |
| 09-target-icps | Target ICPs |
| 10-use-of-funds | Use of Funds |
| 11-documents-vdr | Documents (VDR) |

## Rules

- Folder names and display titles are fixed as listed above; never rename them.
- After any file is added, removed or renamed in a section folder, rerun the build script before committing:
  `powershell -ExecutionPolicy Bypass -File scripts/build-documents-page.ps1`
  Never edit `DOCUMENTS.md` by hand.
- Never draft section content unless the user explicitly asks for it.
- Never put passwords, keys or personal contact details in the repo.
- Explain what you're about to do in plain English before doing it; the user is learning.
