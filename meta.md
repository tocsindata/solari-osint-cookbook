# Project Info
- title: Solari OSINT Operations Center
- short_name: solari-osint-cookbook
- domain: N/A
- production_url: N/A
- local_domain: unknown
- status: active development
- archived: no
- old: false
- legacy: false
- legacy_reason: N/A
- started: 2026-09-01
- ended: ongoing
- hours_worked_on: 1.0
- hours_tracking_started: 2026-09-19T13:17:58Z
- hours_before_tracking_baseline: unknown
- change_count: 1
- change_count_tracking_started: 2026-09-19T13:17:58Z
- change_count_before_tracking_baseline: unknown
- last_repo_update: 2026-09-19
- last_meta_update: 2026-09-19

# Migration
- migration_needed: false
- migration_status: N/A
- migration_target_framework: N/A
- migration_target_repo: N/A
- migration_last_checked: 2026-09-19
- migration_source_commit: a64faf3fcae806a21e0a33bdb54db346b21b5b4f
- migration_target_commit: N/A

# Security
- security_level: 0
- security_level_name: Public
- security_categories: general_security; public-release boundary
- security_boundary: public-source information and public engineering material only; private, proprietary, customer, FCI, CUI, classified, credentialed-private, and unrelated personally identifying material are prohibited
- security_level_source: primes/security/levels.md

# Hosting Info
- hosting_provider: unknown
- hosting_region: unknown
- instance_name: unknown
- instance_id: unknown
- ip: unknown
- checkout_path: unknown
- runtime_path: unknown
- deployed_branch: N/A
- deployed_commit: unknown
- production_path: unknown
- document_root: unknown
- hosting_status: no production deployment or hostname is verified
- deployment_evidence: unknown

# Domain / Edge Info
- dns_provider: unknown
- cloudflare: unknown
- registrar: unknown
- domain_expiry: unknown
- matomo_id: N/A
- matomo_site_name: N/A
- matomo_tracked_url: N/A
- matomo_mapping_evidence: no production hostname exists; exact repository and Solari searches in #webstats C0A68E6PY6P on 2026-09-19 found no authoritative mapping
- domain_status_command: N/A

# Category Info
- primary_scope: primes/tocsindata/solari-osint-cookbook/prime-prompts.md
- project_family: tocsindata
- lifecycle_category: active
- repository_type: public FastAPI and static-web OSINT application with preserved SDK examples
- work_context: work
- security_posture: public repository with automated current-tree scanning and an explicit final semantic public-release gate
- scope_rule: project-family scope defines which repositories may be worked on; traits define behavior only and never expand scope

# Prime Prompt Manifest
- prime_prompt_manifest_status: verified
- prime_prompt_manifest_reviewed: 2026-09-19
- prime_prompt: primes/tocsindata/prime-prompts.md
- prime_prompt: primes/tocsindata/solari-osint-cookbook/prime-prompts.md
- prime_prompt: primes/lifecycle/active.md
- prime_prompt: primes/technology/other_application.md
- prime_prompt: primes/technology/source-control.md
- prime_prompt: primes/technology/update-scripts.md
- prime_prompt: primes/technology/bounded-background-processing.md
- prime_prompt: primes/technology/environment-variables.md
- prime_prompt: primes/technology/interface-contracts.md
- prime_prompt: primes/work-context/work.md
- prime_prompt: primes/security/levels.md
- prime_prompt: primes/security/general_security.md

# Development Notes
- repo_url: https://github.com/tocsindata/solari-osint-cookbook
- main_repo: https://github.com/tocsindata/solari-osint-cookbook
- primary_branch: main
- development_branch: develop; normal work occurs on develop or develop/* and main receives reviewed promotion
- framework: FastAPI, Pydantic, dependency-free HTML/CSS/ES modules, IndexedDB, Web Crypto, and service worker
- runtime: Python 3.11+ required by update tooling; Python 3.12 is used by CI and Docker; Node.js 20+ is used for static-console tests
- database: SQLite for current server mode; browser IndexedDB for static mode
- deployment_model: static-console may use static HTTPS hosting; optional FastAPI deployment and Docker packaging exist; no production deployment is verified
- update_sh: update.sh
- update_macos: update-macos.sh
- update_ps1: update.ps1
- local_dev_path: unknown
- local_backup_path: unknown
- local_host_path: unknown
- canonical_local_url: unknown
- upstream_repo: solari-sdk/solari-cookbook
- source_baseline: develop a64faf3fcae806a21e0a33bdb54db346b21b5b4f; main e6fc205625b31ea0c97ae06af8ccdaf5bc006a4c

# Communications
- slack_channel: unknown
- slack_channel_id: unknown
- chatgpt_project: unknown

# Ownership
- project_owner: Tocsin Data
- technical_lead: unknown
- operational_owner: unknown

# Related Repositories
- related_repos: solari-sdk/solari-cookbook upstream; related repositories do not become authorized scope merely because they are related
- related_repos_authority: informational only

# Repository Evidence
- repository_visibility: public
- repository_created: 2026-09-01
- tracked_blob_count: 323 at develop baseline
- application_stack: optional FastAPI service plus a backend-independent static analyst workspace
- static_stack: dependency-free HTML, CSS, ES modules, IndexedDB, Web Crypto, and service worker
- storage_model: SQLite server stores, browser IndexedDB stores, and content-addressed artifact storage
- ci_status: successful at develop baseline
- latest_ci_run: https://github.com/tocsindata/solari-osint-cookbook/actions/runs/33563475841
- public_data_boundary: lawful public/open operational sources and synthetic fixtures only
- credential_handling: SOLARI_API_KEY and any gated-source credentials are operator-supplied through the environment and must never be committed or persisted in static assets
- release_marker: N/A; no production hostname or deployment is verified
- documentation_migration_baseline: PRIME_PROMPTS revision 9024d161fe151222311b4d846fc01c25f7697727
