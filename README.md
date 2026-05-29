# OpenClaw AI Workflow Portfolio

## Overview

OpenClaw is a local AI workflow system designed to turn AI from a chat tool into repeatable business workflows.

The main use case is the **Enterprise Email Agent**, which helps business users identify important messages, required actions, and daily priorities. AI-MT4 is included only as a secondary technical case study about workflow discipline, runtime separation, risk boundaries, and evidence logging.

## Visual Overview

The diagrams below summarize the portfolio structure and the main workflow.

GitHub can render Mermaid diagrams directly, so the `.mmd` files are included as source diagrams for transparent review and future editing.

- [OpenClaw Overall Architecture](docs/diagrams/01_openclaw_architecture.mmd)
- [Enterprise Email Agent Workflow](docs/diagrams/02_email_agent_workflow.mmd)
- [AI-MT4 Boundary Diagram](docs/diagrams/03_ai_mt4_boundary.mmd)

## Why This Portfolio Exists

This portfolio is designed for HR, recruiters, and hiring managers. It explains the business value, system thinking, and applied AI workflow skills behind the project without publishing private source code, real email data, trading logs, credentials, or live configuration.

## Main Project: Enterprise Email Agent

The Enterprise Email Agent is a business workflow assistant for busy professionals, managers, and small business owners. It turns inbox activity into a daily brief with priorities, required actions, suggested replies, and label recommendations.

The goal is simple: help a business user understand the most important matters of the day within five minutes.

## Supporting System: OpenClaw Workflow Runtime

OpenClaw provides the operating layer behind the agent. It coordinates workflow steps, connects business agents, stores workflow context, records outputs, and makes AI automation more repeatable and reviewable than disconnected scripts.

## Secondary Case Study: AI-MT4 Workflow Discipline

AI-MT4 is not the main project. It is not presented as a trading profit system and does not claim profitability. It is included only to show engineering discipline in a higher-risk workflow domain: runtime separation, replay/live isolation, risk-control thinking, and evidence logging.

## Skills Demonstrated

- AI workflow design
- Business automation analysis
- Agent orchestration
- Email triage and prioritization logic
- Local runtime architecture
- Structured outputs and traceable workflow behavior
- Privacy-conscious documentation
- Risk-boundary thinking for high-risk systems

## Repository Contents

```text
.
|-- README.md
|-- portfolio_summary.md
|-- .gitignore
|-- docs
|   |-- 01_architecture_overview.md
|   |-- 02_enterprise_email_agent_case_study.md
|   |-- 03_openclaw_system_case_study.md
|   |-- 04_ai_mt4_secondary_case_study.md
|   |-- 05_privacy_and_redaction_policy.md
|   |-- 06_resume_and_interview_snippets.md
|   |-- 07_publishing_checklist.md
|   `-- diagrams
|       |-- README.md
|       |-- 01_openclaw_architecture.mmd
|       |-- 02_email_agent_workflow.mmd
|       `-- 03_ai_mt4_boundary.mmd
`-- sample_outputs
    |-- email_daily_brief_sample.md
    |-- email_workflow_trace_sample.json
    `-- ai_mt4_signal_decision_sample.json
```

## Current Status

This is a documentation portfolio for a development project. It is structured for recruiter review, interview discussion, and future GitHub publishing after manual privacy review.

This repository is a curated portfolio showcase, not a full source-code mirror of the private development environment.

## Safety and Privacy Boundary

This showcase excludes credentials, API keys, OAuth tokens, app passwords, real email content, account data, trading logs, live configuration, runtime signal files, and private operational outputs.

## Disclaimer

The sample outputs use synthetic data only. The AI-MT4 case study is not financial advice, does not include live trading data, and makes no profitability or performance claim.

