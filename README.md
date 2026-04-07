# Software Architecture Descriptions

This repository contains source-based software architecture descriptions written against the ISO/IEC/IEEE 42010 standard.

Each subdirectory captures the architecture of a different open source system at a specific repository snapshot. The descriptions are implementation-driven: they are based on inspected source code, configuration, tests, infrastructure definitions, and repository documentation for the recorded snapshot date and commit.

## Repository Structure

### `quinntynebrown-blog-iso42010`

Architecture description for `QuinntyneBrown/Blog`, an ASP.NET Core modular monolith focused on publishing, SEO, performance, and back-office administration.

- Upstream repository: `https://github.com/QuinntyneBrown/Blog`
- Description file: `quinntynebrown-blog-iso42010/README.md`

### `davidfowl-tally-iso42010`

Architecture description for `davidfowl/tally`, a local-first CLI for transaction classification, reporting, and budget analysis.

- Upstream repository: `https://github.com/davidfowl/tally`
- Description file: `davidfowl-tally-iso42010/README.md`

### `microsoft-typeagent-iso42010`

Architecture description for `microsoft/TypeAgent`, a dispatcher-centered multi-host agent platform exploring structured prompting, explanation-driven caching, and Structured RAG memory.

- Upstream repository: `https://github.com/microsoft/TypeAgent`
- Description file: `microsoft-typeagent-iso42010/README.md`

## Scope

The architecture descriptions in this repository typically cover:

- system purpose and boundaries
- stakeholders and concerns
- architectural viewpoints and views
- module, information, runtime, and deployment structure
- quality attributes, rationale, risks, and inconsistencies
- traceability back to repository evidence

## Notes

- Each description is tied to the commit and snapshot date recorded inside that project's `README.md`.
- The repository root is an index for the collected descriptions; the detailed architecture content lives inside each project folder.
