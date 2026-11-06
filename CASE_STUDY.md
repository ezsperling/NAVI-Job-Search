# NAVI: designing a practical job-search workflow

**Navigation & Advancement Via Intelligence**  
Project owner: Elizabeth Sperling  
Format: reusable instructions, templates, and a guided ChatGPT workflow for a nontechnical audience.

## The problem

A job search spreads information across postings, resume versions, application forms, email threads, and spreadsheets. Preparing a document is easy to confuse with submitting it. A receipt can be mistaken for human review, and an unknown date can become an invented fact.

NAVI organizes these handoffs around a private application record, supporting evidence, and a clear next action.

## Elizabeth's contribution

Elizabeth defined the application standard, organizational requirements, review expectations, and user needs through her job-search work. She shaped the toolkit for people who want to work through ChatGPT without learning to code.

The documentation and templates were developed iteratively with AI assistance. This is a workflow and product-design case study, not a claim that every underlying AI capability or integration was independently programmed.

## Design decisions

| Need | Decision | Intended benefit |
| --- | --- | --- |
| Accessible setup | Plain-language guide and copyable requests | A user can begin with one posting and resume |
| Reliable status tracking | Separate Preparing, Applied, and employer-confirmed stages | Reduce unsupported status changes |
| Honest tailoring | Separate verified achievements, transferable skills, and gaps | Prevent invented qualifications |
| Traceable records | Save posting, versions, answers, and confirmation evidence | Support follow-up and interview preparation |
| Incomplete evidence | Explicit COMPLETE, PENDING, NOT APPLICABLE, and UNVERIFIABLE labels | Make unresolved work visible |
| User control | Review applications and approve external actions | Keep consequential choices with the candidate |
| Different account capabilities | Manual and connected paths | Avoid dependence on a custom server |

These are design intentions. Their effect on time saved, error rates, interviews, or offers has not been established by this case study.

## What is available now

The repository includes a setup guide, project instructions, an 18-item application standard, a reusable checklist, prompts, a blank tracker, profile and application-record templates, and a fictional walkthrough.

Connected email/file operations depend on the user's available tools and authorization. Downloading the repository does not install an agent, grant account access, or create recurring tasks.

## How the approach evolved

Earlier NAVI development explored a custom agent and authentication infrastructure. The reusable toolkit now focuses on a workflow people can follow through ChatGPT with optional connections. Retired infrastructure is not required by this toolkit.

The approach preserves useful lessons: verify access, distinguish intended actions from successful writes, preserve unknowns, and give manual recovery steps when a capability is unavailable.

## Evidence and validation

The [application standard](NAVI_APPLICATION_STANDARD.md) documents the rules. The [fictional walkthrough](EXAMPLE_WALKTHROUGH.md) illustrates expected behavior and unresolved evidence.

The walkthrough is illustrative, not a measured user study or proof that integrations passed end-to-end tests. Future evaluation should use explicitly consented or fictional records and report failures as well as successes.

## Next learning questions

Can a new user complete setup without help? Can the workflow reconcile a receipt with an existing application without duplication? Does it preserve unknown pay, dates, and eligibility? Can users find the exact materials used before an interview?

See the [roadmap](ROADMAP.md) for proposed evaluation and improvements.
