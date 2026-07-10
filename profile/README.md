# Owlhoot AI

**AI Completion Assurance for agent workflows.**

AI agents are good at reporting that work is finished. Owlhoot AI is building tools that let teams verify completion against trusted evidence instead of relying on the agent's summary.

> Evidence is authoritative. Prose is not.

## Start here

[AuditGrade Verifier](https://github.com/owlhoot-ai/auditgrade-verifier) is our public verifier and certificate-format preview. It demonstrates offline verification of:

- pinned issuer trust;
- signed certificate payloads;
- evidence hashes and file sizes;
- aggregate evidence integrity; and
- refusal of self-rooted proof.

## Public by design

We publish the verification boundary:

- a standalone verifier;
- a preview certificate specification;
- public-safe examples and tamper cases; and
- threat-model and claims documentation.

The private enforcement kernel, issuer orchestration, production keys, and customer material are not included.

## Status

Public preview. Formats and interfaces may change before v1.0. We publish runnable demonstrations and state explicitly what they do—and do not—prove.

## Links

- [Founder: Kirk Nielson](https://www.linkedin.com/in/kirk-nielson/)
- [Security policy](https://github.com/owlhoot-ai/auditgrade-verifier/blob/main/SECURITY.md)
