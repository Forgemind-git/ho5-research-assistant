# Study Guide — AWS SAA-C03

*One-page study guide generated from the notebook (Studio → Study guide), then trimmed. NotebookLM also generated an FAQ from the same sources — see the pointers at the bottom. Every point is citable in the notebook.*

## Study order (by exam weighting)
1. **Secure architectures** — IAM users vs roles, least privilege, KMS `[S1][S6]`.
2. **Resilient architectures** — Multi-AZ, load balancing, Auto Scaling, Multi-AZ RDS `[S1][S8]`.
3. **High-performing architectures** — right compute (EC2 vs Lambda), right storage `[S1][S4]`.
4. **Cost-optimised architectures** — pick the cheapest service that meets the need `[S1][S2]`.

## Core facts to lock in
- **Storage:** object → **S3**; single-instance disk → **EBS**; shared file system → **EFS**; cheap archive → **Glacier** `[S3]`.
- **Compute:** **EC2** = servers you manage; **Lambda** = run code without servers; **Auto Scaling** replaces failed instances `[S4]`.
- **Well-Architected pillars:** Operational Excellence, Security, Reliability, Performance Efficiency, Cost Optimization `[S2]`.
- **IAM:** prefer **roles** (temporary credentials) over long-lived **user** keys `[S6]`.
- **HA principle:** design for failure — spread across AZs, no single point of failure `[S8]`.

## How to revise with this notebook
- Ask a question → read the cited source → close the loop. Don't accept an uncited answer.
- Use the **FAQ** doc (Studio → FAQ) for rapid self-testing; it's generated from the same readings.
- Regenerate the **Study guide** after adding new notes so it stays current.

## FAQ pointers (generated in Studio → FAQ)
- "What's the difference between security groups and NACLs?" → networking reading `[S5]`.
- "When Aurora vs RDS vs DynamoDB?" → database notes `[S7]`.
- "What does Multi-AZ actually protect against?" → HA/DR reading `[S8]`.

## Audio Overview
An Audio Overview (Studio → Audio Overview) turns these readings into a two-host revision podcast — good for commute revision. Link: _paste your Audio Overview Share link here_.
