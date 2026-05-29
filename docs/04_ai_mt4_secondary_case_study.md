# Secondary Case Study: AI-MT4 Workflow Discipline

## Positioning

This is not the main project. The main project is OpenClaw AI Workflow System + Enterprise Email Agent.

This is not financial advice. This does not claim profitability. This is included only as a high-risk automation boundary case study about workflow discipline, runtime separation, risk boundaries, and evidence logging.

## Boundary Diagram

[AI-MT4 Boundary Diagram](diagrams/03_ai_mt4_boundary.md)

This diagram shows AI-MT4 as a secondary case study about separation, risk boundaries, and evidence logging.

## Why It Is Included

AI-MT4 represents a higher-risk automation domain. The useful lesson is not trading performance. The useful lesson is disciplined system design when automation touches sensitive execution environments.

High-risk automation requires stronger boundaries. Research logic, review logic, and execution systems should not be casually mixed.

## Engineering Themes

- Runtime separation
- Replay/live isolation
- Separation of research, review, and execution
- Risk-boundary design
- Evidence logs for audit and review
- Risk guard thinking that applies beyond trading to any sensitive workflow
- Keeping high-risk execution systems separate from ordinary business automation

## Workflow Discipline

The case study demonstrates a design mindset where research, orchestration, review, and execution are treated as separate responsibilities. Evidence logging supports audit, review, and risk attribution when decisions need to be examined later.

## Public Showcase Boundary

This showcase does not include:

- Real trading logs
- Live config
- Account data
- Broker data
- Runtime signal files
- Profit claims
- Performance claims

## Interview Answer

The AI-MT4 case study is included to show how I think about operational risk. I kept it separate from ordinary business automation and treated it as a boundary-design problem: isolate runtime responsibilities, preserve evidence, and avoid presenting high-risk automation as a casual AI demo.

