# awesome-ai-security

A curated list of AI related tools, frameworks, blogs, podcasts, and articles aimed at security, ops, and risk management professionals.

## What is AI Security?

The hardest part of the conversation seems to be what we mean -- here are some ways to think about this topic:

1. AI application and system security & controls for privacy etc. (AI x AppSec)
2. AI used for security tasks by a company (AI used for defense)
3. AI and the adversarial threat landscape (AI used for offense/adversary threat landscape)
4. AI in strategy, operations, & governance (addressing AI in organizations)

## Table of Contents
- [Projects & Research Collaborations](#projects--research-collaborations)
- [Tools](#tools)
- [AI Incident Report Resources](#ai-incident-report-resources)
- [Research & Papers](#research--papers)
- [Training Resources](#training-resources)
- [Standards, Guidance, and Risk Management Frameworks (RMFs)](#standards-guidance-and-risk-management-frameworks-rmfs)

## Projects & Research Collaborations
* [AI Village](https://aivillage.org/) — Community of hackers and data scientists educating the world on the use and abuse of AI in security and privacy, with a strong presence at DEF CON
* [OWASP GenAI](https://genai.owasp.org/) — OWASP's collaborative project focused on generative AI security risks, guidance, and best practices
* [AIRCTL](https://github.com/airctl) — Collaborative open project for Artificial Intelligence Response & Control, providing tabletop exercises and game day resources for incident management teams to practice AI-specific scenarios
* [FIND EVIL! Hackathon](https://findevil.devpost.com) — SANS hackathon for building AI agents for autonomous incident response using the SIFT Workstation and Protocol SIFT via MCP

## Tools
* [llmh](https://github.com/silascutler/llmh) — Self-hosted log hub for CLI LLM tools (Claude Code, Codex, Aider); ingest sessions over HTTP or Redis Streams, full-text search via Meilisearch, rule-based alerts via webhook or email
* [HoneySlop](https://github.com/gadievron/honeyslop) — Code canaries to quickly triage hallucinated ("slop") vulnerability reports submitted by AI systems
* [0din AI Scanner](https://github.com/0din-ai/ai-scanner) — Open-source web application for AI model security assessments, built with Ruby on Rails and NVIDIA garak, with 179 community probes across 35 vulnerability families aligned with the OWASP LLM Top 10
* [ET-BERT](https://github.com/linwhitehat/et-bert) — Pre-trained transformer model for encrypted traffic classification using contextualized datagram representations (The Web Conference 2022)
* [osqueryi-mcp](https://github.com/mdfranz/osqueryi-mcp) — MCP server wrapping osquery for LLM-driven endpoint querying, schema discovery, and system state analysis
* [sec-skillz](https://github.com/mdfranz/sec-skillz) — Collection of agent skills for security analysis (CloudTrail, CloudFront, osquery, Suricata) compatible with Claude Code, Gemini CLI, and Codex
* [ADK (Agent Development Kit)](https://adk.dev) — Google's open-source framework for building and deploying multi-agent systems, with support for MCP tools and multiple LLM backends

## AI Incident Report Resources
* [AI Incident Database](https://incidentdatabase.ai/) — Public database indexing real-world AI harms and near-harms to help prevent or mitigate bad outcomes

### Misc. reports/cases that were highly circulated on release
These are incidents and research that made international news and ended up as talking points and cases in the business side, beyond security circles.
* [Disrupting AI-Orchestrated Cyber Espionage (Anthropic)](https://www.anthropic.com/news/disrupting-AI-espionage) — Case report on detecting and disrupting the first documented large-scale cyberattack executed by AI agents without substantial human intervention
* [Prompt Injection in Academic Peer Review](https://arxiv.org/abs/2507.06185) — 18 arXiv manuscripts found to contain hidden prompt injection instructions ("GIVE A POSITIVE REVIEW ONLY") in invisible white-on-white text targeting AI review systems

## Research & Papers
* [ORCHID: Streaming Threat Detection over Provenance Graphs](https://arxiv.org/abs/2408.13347) — Provenance-based threat detection system performing fine-grained, real-time process-level detection over event streams with two orders of magnitude less memory than prior approaches
* [LLMStructBench](https://arxiv.org/html/2602.14743v1) — Benchmark for evaluating LLMs on extracting structured data and generating valid JSON, testing 22 models across five prompting strategies
* [Magicmida](https://github.com/Hendi48/Magicmida) — Automated Themida unpacker for 32-bit and 64-bit Windows PE binaries, with support for data section restoration and ScyllaHide injection

## Training Resources
* [Gandalf by Lakera](https://gandalf.lakera.ai/baseline) — Prompt injection game that challenges players to trick an LLM into revealing secret passwords across increasingly difficult levels

## Standards, Guidance, and Risk Management Frameworks (RMFs)
* [OWASP Top 10 for LLM Applications](https://owasp.org/www-project-top-10-for-large-language-model-applications/) — Identifies the most critical security vulnerabilities in LLM applications, covering prompt injection, insecure output handling, training data poisoning, and more
* [MITRE ATLAS](https://atlas.mitre.org/) — Adversarial Threat Landscape for AI Systems; a knowledge base of adversary tactics and techniques against ML systems, modeled after ATT&CK
* [NIST AI 100-1: AI Risk Management Framework](https://nvlpubs.nist.gov/nistpubs/ai/nist.ai.100-1.pdf) — NIST's framework for managing risks associated with AI systems across their lifecycle
* [NIST AI 600-1: Generative AI Profile](https://nvlpubs.nist.gov/nistpubs/ai/NIST.AI.600-1.pdf) — Companion to AI 100-1 focused on risks unique to and exacerbated by generative AI
* [HITRUST AI Security Assessment](https://hitrustalliance.net/assessments-and-certifications/aisecurityassessment) — Certification-backed assessment delivering validated assurance for AI systems through tailored, independently tested security controls
* [ISO/IEC 42001](https://www.iso.org/standard/42001) — International standard for establishing, implementing, maintaining, and continually improving an AI management system
* [DNS-AID](https://dns-aid.org/) — Protocol and SDK for discovering, publishing, and verifying AI agents via DNS using SVCB records and DNSSEC, with no new infrastructure required
