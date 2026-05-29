# OpenClaw AI Workflow Portfolio

## Overview

OpenClaw is a local AI workflow system designed to turn AI from a chat tool into repeatable business workflows.

The main use case is the **Enterprise Email Agent**, which helps business users identify important messages, required actions, and daily priorities. AI-MT4 is included only as a secondary technical case study about workflow discipline, runtime separation, risk boundaries, and evidence logging.

## Visual Overview

The diagrams below summarize the portfolio structure and the main workflow.

GitHub can render Mermaid diagrams directly. The `.mmd` files are retained as editable source files, while the `.md` pages are the recommended GitHub viewing pages.

- [OpenClaw Overall Architecture](docs/diagrams/01_openclaw_architecture.md)
- [Enterprise Email Agent Workflow](docs/diagrams/02_email_agent_workflow.md)
- [AI-MT4 Boundary Diagram](docs/diagrams/03_ai_mt4_boundary.md)

## Why This Portfolio Exists

This portfolio documents how AI workflow engineering can improve real business operations by turning messy information streams into repeatable, reviewable, structured workflows. It focuses on practical business value, operational clarity, privacy boundaries, and risk-aware automation design.

## Main Project: Enterprise Email Agent

The Enterprise Email Agent is a business workflow assistant for busy professionals, managers, and small business owners. It turns inbox activity into a daily brief with priorities, required actions, suggested replies, and label recommendations.

The goal is simple: help a business user understand the most important matters of the day within five minutes. This reduces manual triage, lowers cognitive load, and helps prevent missed approvals, payments, meetings, supplier updates, and customer requests.

## Supporting System: OpenClaw Workflow Runtime

OpenClaw provides the operating layer behind the agent. It coordinates workflow steps, connects business agents, stores workflow context, records outputs, and makes AI automation more repeatable and reviewable than disconnected scripts.

## Secondary Case Study: AI-MT4 Workflow Discipline

AI-MT4 is not the main project. It is not presented as a trading profit system and does not claim profitability. It is included only to show risk-aware system design in a higher-risk workflow domain: runtime separation, replay/live isolation, review boundaries, and evidence logging.

## Skills Demonstrated

- Practical AI workflow engineering
- Business process automation
- Agent orchestration
- Email triage and prioritization logic
- Local runtime architecture
- Structured outputs and traceable workflow behavior
- Privacy-conscious operational design
- Risk-aware system design for sensitive workflows

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
|       |-- 01_openclaw_architecture.md
|       |-- 01_openclaw_architecture.mmd
|       |-- 02_email_agent_workflow.md
|       |-- 02_email_agent_workflow.mmd
|       |-- 03_ai_mt4_boundary.md
|       `-- 03_ai_mt4_boundary.mmd
`-- sample_outputs
    |-- email_daily_brief_sample.md
    |-- email_workflow_trace_sample.json
    `-- ai_mt4_signal_decision_sample.json
```

## Current Status

This is a documentation portfolio for a development project. It is structured for public review, technical discussion, and future GitHub publishing after manual privacy review.

This repository is a curated portfolio showcase, not a full source-code mirror of the private development environment.

## Safety and Privacy Boundary

This showcase excludes credentials, API keys, OAuth tokens, app passwords, real email content, account data, trading logs, live configuration, runtime signal files, and private operational outputs.

## Disclaimer

The sample outputs use synthetic data only. The AI-MT4 case study is not financial advice, does not include live trading data, and makes no profitability or performance claim.

