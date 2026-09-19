# Infrastructure

No production deployment, server, hostname, deployed revision, provider, region, or runtime path is verified.

The repository supports two intended modes:

- static mode from `static-console/` on ordinary HTTPS/static hosting;
- optional FastAPI mode from `app/`, with the canonical workspace mounted at `/workspace/` and advanced server operations at `/server-dashboard`.

Docker and Compose definitions exist for local or future server packaging. Their presence is not deployment evidence. SQLite is the current server persistence model; browser mode uses IndexedDB. Any future production deployment must record exact hosting, network, monitoring, backup, restore, rollback, release, and ownership evidence before metadata is updated.
