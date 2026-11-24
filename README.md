# ORBIT Envision Demo

> **STATUS: DEMONSTRATION AND DESIGN REFERENCE**
>
> This repository contains the working ORBIT Envision-path demonstration
> application. It is used to explore workflows, interaction patterns, board
> rules, and MVP user experience.
>
> **This is not the production Envision build.**
>
> **Active production-build repository:** `ncscdude/orbit-helios`
>
> **Data rule:** This repository uses fictional demonstration data only. It must
> never receive live personnel data, operational records, credentials, exports,
> or real identifiers.

## What this repository is for

- Demonstrating the ORBIT user experience and workflow.
- Testing front-end interaction patterns.
- Maintaining the fictional-data MVP reference.
- Supporting controlled reuse of UI concepts and isolated code patterns.

## What this repository is not for

- Connecting to live Envision data.
- Authenticating operational users.
- Serving as an authoritative audit system.
- Storing production decisions, scores, or board records.
- Becoming the production system by changing its data source.

## Branch guidance

| Branch | Purpose |
|---|---|
| `prototype-4.3.0` | Preserved prototype baseline; do not modify |
| `envision-path` | Cleaned Envision-oriented demo path |
| `mvp-scope` | Working UX and scope reference for the one-board MVP |

Any code reused in `orbit-helios` must be reviewed, stripped of fictional data,
and aligned with the production specifications, platform controls, and security
rules before use.
