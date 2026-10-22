# Security

## Reporting

Open a private advisory at <https://github.com/ME0094/huntplan/security/advisories/new>. Please do not
open a public issue for an unfixed flaw.

## Scope

The tool turns a question into a threat-hunting plan and validates it. It makes no network calls and
does nothing with the file beyond reading it. What matters: inputs that exhaust memory, and any path
by which a plan is reported as valid when it is not.

## Out of scope

Whether a plan is worth hunting is not the tool's call: it measures falsifiability, data sources,
closure criteria and maturity, not the analyst's judgement.
