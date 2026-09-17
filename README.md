# MIP — Messagerie Instantanée Professionnelle

MIP is a sovereign, end-to-end encrypted enterprise messaging platform for Moroccan public-sector and enterprise clients, built as a capstone project. Every message is E2EE by default via the Signal protocol — the server only ever stores ciphertext, so admins manage accounts and structure but can never read content. It ships as SaaS or fully self-hosted on-premise, includes encrypted voice/video calls and attachments, and is positioned around Moroccan data sovereignty and regulatory compliance (DGSSI, CNDP) rather than just being "another Matrix deployment."

**Stack:** Spring Boot/Java backend, Keycloak for auth, Flutter mobile client, LiveKit for calls, Postgres + SeaweedFS for storage.
