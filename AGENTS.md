# Development Instructions

This repository follows the Evandro Development Standard, aligned with current OpenAI Skills/Plugins engineering guidance.

## Workflow
1. Define the problem and acceptance criteria before implementation.
2. Inspect applicable official Skills/Plugins and existing project conventions before inventing a new workflow.
3. Implement the smallest useful testable increment.
4. Run appropriate tests and inspect errors/logs.
5. Validate user-facing behavior when applicable.
6. Document meaningful architecture and decisions.
7. Commit incrementally with truthful descriptions of completed work.

## AI systems
- Separate deterministic business rules from model-driven behavior where practical.
- Define expected inputs, outputs, failure states and validation around model calls.
- Do not treat plausible model output as proof of correctness.
- Prefer measurable evaluation cases for important AI behavior.

## Secrets and data
Never commit API keys, tokens, passwords, private datasets or confidential user/client information. Use environment variables and safe secret-management mechanisms.

## Portfolio integrity
Never fabricate commits, dates, tests, benchmarks, users, deployment status or results. The repository should demonstrate genuine progression from zero to working outcomes.
