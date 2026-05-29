# Secondary Case Study: AI-MT4 Workflow Discipline

## Positioning

This is not the main project. The main project is OpenClaw AI Workflow System + Enterprise Email Agent.

This is not financial advice. This does not claim profitability. This is included only to demonstrate workflow discipline, runtime separation, risk boundaries, and evidence logging.

## Boundary Diagram

[AI-MT4 Boundary Diagram](diagrams/03_ai_mt4_boundary.mmd)

This diagram shows AI-MT4 as a secondary case study about separation, risk boundaries, and evidence logging.

## Why It Is Included

AI-MT4 represents a higher-risk workflow domain. The useful lesson for a recruiter or hiring manager is not trading performance. The useful lesson is disciplined system design when automation touches sensitive execution environments.

## Engineering Themes

- Runtime separation
- Replay/live isolation
- Risk-control thinking
- Evidence logs
- Audit-friendly workflow design
- Keeping high-risk execution systems separate from ordinary business automation

## Workflow Discipline

The case study demonstrates a design mindset where research, orchestration, review, and execution are not casually mixed. Higher-risk workflows need clearer boundaries, stronger review habits, and evidence that decisions followed a controlled process.

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
