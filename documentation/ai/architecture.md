# Architecture

`static-console/` is the single analyst frontend. In static mode it uses browser storage and direct, explicitly supported public/CORS sources. In server mode FastAPI mounts the same checked-in frontend at `/workspace/`; `server-runtime.js` synchronizes server events, entities, relationships, evidence, acquisitions, source health, and bounded collection controls. `/server-dashboard` remains an advanced server-only operations surface.

The server stack is FastAPI, Pydantic, and SQLite. The static stack is dependency-free HTML/CSS/ES modules with IndexedDB, Web Crypto, and a service worker. Evidence and provenance distinguish observed facts, deterministic transformations, and inference. Collection and background work use bounded concurrency, deterministic ordering, explicit error state, and a single-host durable SQLite queue; distributed execution is not claimed.

Detailed current implementation documents are preserved byte-for-byte under `documentation/ai/guides/`. They are subordinate to current code, root metadata, and the applicable Prime Prompts.
