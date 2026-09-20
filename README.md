# Awesome-Identity-Analytics

Top Identity Analytics Platforms Ecosystem

Curated List of SaaS Products & Open-Source GitHub Projects
Focused on User & Entity Behavior Analytics (UEBA), Identity Threat Detection & Response (ITDR) & Insider Risk Management
Last updated: September 2026

This repository tracks notable SaaS platforms and open-source projects for Identity Analytics. These tools help security teams detect compromised accounts, insider threats, lateral movement, and privilege abuse by baselining normal user and entity behavior and flagging deviations.

Examples include Exabeam, Securonix, Microsoft Defender for Identity, Darktrace Identity, ManageEngine Log360, IBM QRadar UBA, LogRhythm UEBA, Microsoft Sentinel UEBA, ObserveIT, and Varonis (the category leaders).

Open-source emphasis: This section is heavily expanded with every major active project for self-hosting, custom detection models, and transparent identity security workflows — ideal for SOC teams, security engineers, and organizations that need deep visibility into identity risk without vendor lock-in.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

Table of Contents

SaaS/Hosted Platforms

Open-Source GitHub Projects

How to Contribute

Disclaimer

SaaS/Hosted Platforms

Exabeam
Security intelligence and UEBA platform. Builds behavioral baselines for users and entities, assigns risk scores, and correlates events across SIEM and identity sources to detect credential compromise and insider threats.

Securonix
Next-gen SIEM and UEBA platform with identity analytics. Uses machine learning and behavior analytics to detect advanced threats, insider risks, and account takeovers at enterprise scale.

Microsoft Defender for Identity
Cloud-based identity threat detection for Active Directory and Azure AD. Monitors on-premises signals to detect lateral movement, privilege escalation, and compromised credentials.

Darktrace Identity
AI-powered identity analytics module within the Darktrace ecosystem. Uses self-learning AI to detect anomalous behavior across cloud, SaaS, and on-premises identity infrastructure.

ManageEngine Log360
Integrated SIEM with UEBA capabilities. Establishes behavioral baselines for users and hosts, uses RPCA and Markov Chains for anomaly detection, and provides risk scoring with time/count/pattern-based deviations -
2
-
14
.

IBM QRadar UBA
User Behavior Analytics application for QRadar SIEM. Builds risk profiles for users by combining disparate accounts into unified identities, with machine learning for time-series profiling and clustering -
1
-
8
.

LogRhythm UEBA
UEBA Module and CloudAI within the LogRhythm platform. AI Engine rules detect anomalies including abnormal file access, lateral movement, privilege escalation, and exfiltration with ML-backed detection -
3
.

Microsoft Sentinel UEBA
Cloud-native SIEM with built-in UEBA capabilities. Provides unified IdentityInfo tables, entity behavior analytics, and integration with the broader Defender portal for enriched investigations -
4
.

ObserveIT
Insider threat monitoring platform (now Proofpoint). Records user sessions, analyzes behavior, and detects risky activities like data exfiltration and privilege abuse.

Varonis
Data security platform with UEBA capabilities. Analyzes file activity, permissions, and user behavior to detect insider threats, ransomware, and data exfiltration.

Open-Source GitHub Projects

OpenUBA
Robust, flexible open-source UEBA framework for security analytics. Features managed JupyterLab workspaces, Python SDK (pip install openuba), visual flow-based rule builder (Rule Canvas), model library/marketplace with community-contributed models (sklearn, PyTorch, TensorFlow, NetworkX), JWT auth with RBAC, case management, and SIEM-agnostic architecture. ~513 stars, 280 forks -
5
-
16
.

ThreatFlix
AI-powered security copilot SDK that detects, analyzes, and responds to application threats using Google Gemini and the MITRE ATT&CK framework. Deliberately separates deterministic investigation (evidence, attack chain) from ML-based assistance (UEBA ensemble, graph similarity, LLM narration) so models cannot rewrite facts. Student-built, research-grade -
6
.

Idryx
Identity Security Graph that unifies humans, service accounts, keys, and AI agents in one graph. Features per-identity baselining, 27 detectors across ITDR/NHI/agents/least-privilege, delegation graph resolution with cycle protection, Agent-BOM (CycloneDX-shaped), remediation proposals (never mutates), and alert delivery to Slack/SIEM/OTLP. Apache-2.0 -
7
-
11
-
17
.

UEBA Blockchain Ledger
ML-based anomaly detection system with blockchain-backed tamper-proof audit logging. Isolation Forest model with per-user behavioral baselines, Streamlit dashboard, hash-chained ledger for alert integrity, and real-time desktop notifications. Built for Smart India Hackathon 2025 -
10
.

Baton
Toolkit for adding identity governance to any application. Extracts, normalizes, and interacts with identity data (accounts, permissions, roles, groups) across SaaS and IaaS systems. Use cases include access reviews, SIEM exports, permission diffs, and effective access calculation. ~v0.4.5 -
12
.

Additional Strong Open-Source Options

Identity Governance: Baton (ConductorOne) for access auditing and permission analysis across GitHub, AWS, and other systems -
12
.

Graph-Based Detection: Idryx for unified identity graphs spanning humans, service accounts, and AI agents with delegation chain resolution -
17
.

ML Frameworks: OpenUBA model library with Isolation Forest, PyTorch, TensorFlow, and NetworkX-based detection models -
16
.

Audit Integrity: UEBA Blockchain Ledger for tamper-proof alert logging via hash-chained ledgers -
10
.

Frameworks for building custom systems: Combine OpenUBA for the core UEBA engine and model registry, Idryx for identity graph unification and ITDR detectors, Baton for identity governance data extraction, and PostgreSQL + GraphQL for persistence. Add JupyterLab for model development and Slack/webhooks for alerting.

How to Contribute

Fork the repo.

Add/edit entries in README.md (follow existing format).

Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

Submit PR with a short explanation.

Star the repo if you find it useful!

Disclaimer

This is a community-curated list — not exhaustive and not an endorsement.

Identity analytics tools process sensitive user behavior data; ensure compliance with privacy regulations, employee monitoring laws, and data protection requirements.

Self-hosted open-source solutions require proper security hardening, model validation, and regular tuning to minimize false positives.

Made for SOC analysts, identity security engineers, threat hunters, and security architects.
Let's make identity analytics more open, explainable, and effective.
