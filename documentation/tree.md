# Repository Tree

```text
.
├── .github/workflows/          # CI, history scanning, and platform-update checks
├── app/                        # FastAPI application, contracts, collectors, persistence, jobs, and APIs
├── docs/
│   └── README.md               # Compatibility pointer retained for the current Dockerfile
├── documentation/
│   ├── ai/
│   │   ├── architecture.md
│   │   ├── repository-guidance.md
│   │   └── guides/             # Detailed implementation documents moved byte-for-byte from docs/
│   ├── history/
│   │   ├── history.md
│   │   ├── local-todo-before-centralization.md
│   │   ├── original-meta.md
│   │   ├── original-read-first.md
│   │   ├── original-readme.md
│   │   └── prime-prompts-compliance-2026-09-01.md
│   ├── human/
│   │   ├── administrative.md
│   │   ├── communications.md
│   │   ├── infrastructure.md
│   │   ├── maintenance.md
│   │   ├── ownership.md
│   │   ├── priority.md
│   │   ├── security.md
│   │   ├── sources.md          # Preserved source registry/provenance rules
│   │   └── guides/             # Detailed operator/reviewer/source documents moved from docs/
│   └── tree.md
├── examples/                   # Preserved upstream self-contained cookbook examples and READMEs
├── samples/                    # Synthetic/public sample output
├── static-broker/              # Optional controlled broker example and README
├── static-console/             # Canonical backend-independent analyst frontend and Node tests
├── tests/                      # Python application and contract tests
├── tools/                      # Runtime, release-scan, contract, and packaging utilities
├── Dockerfile
├── docker-compose.yml
├── README.md
├── meta.md
├── requirements.txt
├── requirements-dev.txt
├── todo.md
├── update-macos.sh
├── update.ps1
└── update.sh
```

Only `README.md`, `meta.md`, and `todo.md` are current root Markdown files. Example and component READMEs remain beside the code they explain. `documentation/` is the canonical project-documentation tree; `docs/` is a build-compatibility pointer only.
