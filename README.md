# audit-portfolio
🔐 Audit Portfolio Independent smart contract security reviews and competitive audit findings.
About
I'm Carlos — a Web3 security researcher focused on Solidity/EVM protocols. This repo contains my completed audit reports, organized by engagement.
Each audit follows a 5-phase process:

Scoping — Understand protocol intent, architecture, and trust assumptions
Recon — Manual line-by-line review + static analysis (Slither, Aderyn)
Exploitation — Build PoCs in Foundry for every confirmed finding
Judging Agent — Validate findings against severity criteria before submission
Reporting — Professional PDF report with executive summary + detailed findings


Completed Audits
#ProtocolTypeDateFindingsReport001Protocol NameDeFi / Lending2026-XX1H · 2M · 3LPDF002Protocol NameNFT / Marketplace2026-XX0H · 1M · 2LPDF

Table updated as audits are completed.


Repo Structure
audit-portfolio/
├── README.md
├── audits/
│   ├── 001-protocol-name/
│   │   ├── report.pdf              # Final audit report
│   │   ├── findings.md             # All findings in markdown
│   │   ├── scope.md                # Scope, commit hash, LOC
│   │   └── poc/                    # Foundry PoC tests
│   │       └── test/
│   │           └── ExploitTest.t.sol
│   ├── 002-protocol-name/
│   │   └── ...
│   └── ...
├── templates/
│   ├── report-template.md          # Report skeleton
│   ├── finding-template.md         # Single finding format
│   └── scope-template.md           # Scoping checklist
└── competitive/
    ├── code4rena/
    │   └── contest-name/
    │       └── findings.md
    └── sherlock/
        └── contest-name/
            └── findings.md

Finding Severity Definitions
SeverityCriteriaHighDirect loss of funds, protocol insolvency, or permanent denial of serviceMediumConditional fund loss, governance manipulation, or significant griefingLowMinor inefficiency, informational, or best-practice deviation

Contact

Twitter/X: @yourhandle
Email: your@email.com
