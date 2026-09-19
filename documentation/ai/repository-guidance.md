# Repository Guidance

1. Read root `meta.md`, `todo.md`, this file, and the relevant detailed guide before changes.
2. Work on `develop` or `develop/*`; do not develop directly on `main`.
3. Preserve upstream cookbook examples unless a deliberate compatibility change is authorized.
4. Keep the repository public-safe and neutral; do not store assistant/tool branding, private prompts, credentials, or unrelated identities.
5. Prefer documented public APIs and deterministic adapters. Use Browser, Sandbox, or Desktop only when that execution surface solves a concrete problem.
6. Preserve raw/evidence provenance, transformation history, bounded retries/concurrency, explicit failures, and deterministic identities.
7. Do not expose durable provider credentials to static JavaScript. Provider execution remains a controlled server/broker responsibility unless an explicitly safe browser credential/client model is verified.
8. Update the centralized TODO rather than creating a second active project backlog.

The compatibility `docs/README.md` must remain until the Dockerfile's `COPY docs ./docs` dependency is changed under separate non-Markdown authority.
