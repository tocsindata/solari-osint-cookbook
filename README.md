# Solari OSINT Operations Center

This public repository preserves the upstream Solari cookbook examples and develops a production-minded, public-source intelligence operations center. It combines a backend-independent analyst workspace with an optional FastAPI service for normalized acquisition, evidence, geospatial analysis, cases, workflows, observability, and controlled Solari Browser, Sandbox, and Desktop execution.

Only lawful public/open information belongs in this project. Do not add credentials, private source inventories, customer data, proprietary logic, FCI, CUI, classified information, or unrelated personal information.

## Start here

- [Repository map](documentation/tree.md)
- [Operations and setup](documentation/human/maintenance.md)
- [Security and public-data boundary](documentation/human/security.md)
- [Source registry and provenance](documentation/human/sources.md)
- [Architecture and implementation guidance](documentation/ai/architecture.md)
- [Current priorities](documentation/human/priority.md)
- [Authoritative TODO pointer](todo.md)

## Runtime modes

- `static-console/` is the canonical browser analyst workspace. It can run from ordinary static hosting and persists local work in browser storage.
- `app/` is the optional FastAPI service. It mounts the same static console at `/workspace/` and retains advanced server-only operations at `/server-dashboard`.
- SQLite is the current server-side persistence model. Optional larger-scale backends are not claimed as implemented.
- Root update entry points are `./update.sh`, `./update-macos.sh`, and `.\\update.ps1`; they intentionally run only from `develop` or `develop/*`.

## Local server

After installing the declared dependencies:

```bash
python -m uvicorn app.main:app --reload
```

Open `/` for the analyst workspace or `/server-dashboard` for advanced server operations. Live Solari integration requires an operator-supplied `SOLARI_API_KEY`; never store it in the repository.

## Documentation compatibility

Current project documentation is canonical under `documentation/`. The small `docs/README.md` compatibility pointer remains because the existing Dockerfile copies `docs/`; all prior `docs/` content was retained byte-for-byte under the canonical tree.

MIT licensed.
