# Contributing to GPT Software Development Skills

Thanks for helping make this collection more useful and more trustworthy.

This repository benefits most from contributions that improve **real software-engineering usefulness**, not just the number of packages.

## Good contributions

- Fix incorrect or unclear documentation.
- Add reproducible installation or compatibility notes.
- Add evaluation scenarios or regression checks.
- Report broken package structure, missing files or invalid references.
- Improve an existing skill's workflow, evidence requirements or failure handling.
- Propose a missing software-engineering skill with a concrete user problem.
- Add verified examples showing where a skill works — or fails.

## Before proposing a new skill

Please be able to answer:

1. What software-development problem does it solve?
2. Who is the intended user or agent?
3. What makes this a reusable skill rather than a one-off prompt?
4. What tools or environment does it require?
5. What evidence would demonstrate that it works?
6. What are its stop conditions, risks or known limitations?
7. Does an existing skill already cover most of the job?

## Package expectations

A proposed skill package should make its behavior inspectable. Where applicable, include:

- `SKILL.md` or `skill.md`;
- clear trigger/use-case description;
- workflow instructions;
- declared tool/runtime dependencies;
- references or source strategy when claims depend on external facts;
- deterministic scripts or validators when useful;
- evaluation scenarios;
- explicit limitations and unsupported cases.

Do not include credentials, API keys, private customer data or other secrets.

## Bug reports

A useful bug report contains:

- skill/package name;
- environment or agent used;
- exact task;
- expected behavior;
- observed behavior;
- reproducible steps;
- relevant logs/output with secrets removed.

## Pull requests

Keep changes bounded. Explain:

- what problem the PR fixes;
- which skill(s) it affects;
- how the change was validated;
- what remains unverified.

A plausible edit is not automatically evidence that a workflow works in a real repository or runtime.

## Repository-wide licensing

A repository-wide license is not currently declared in this contribution guide. Do not assume permission terms that are not explicitly present in the repository or individual packages.
