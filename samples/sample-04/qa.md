# Cited Q&A — AWS SAA-C03 Study Knowledge Base

Five revision questions, the answers NotebookLM returned, and the source each cited (`[S#]` from `sources.md`).

> Illustrative reference of cited revision answers. Your notebook cites your own readings.

---

### Q1. "When should I use S3 vs EBS vs EFS? Cite the reading."

**Answer:** Use **S3** for object storage — files, backups, static assets — accessed over HTTP, with high durability **[S3]**. Use **EBS** for block storage attached to a single EC2 instance, like a disk **[S3]**. Use **EFS** for a shared file system mounted by *many* EC2 instances at once **[S3]**. Rule of thumb from the storage overview: object = S3, one-instance disk = EBS, shared file system = EFS **[S3]**.

---

### Q2. "What are the five pillars of the Well-Architected Framework?"

**Answer:** Operational Excellence, Security, Reliability, Performance Efficiency, and Cost Optimization **[S2]**. (Later editions add Sustainability, but the core five above are what the exam guide emphasises **[S1][S2]**.)

---

### Q3. "How do I make an application highly available across failures?"

**Answer:** Deploy across **multiple Availability Zones**, put instances behind a load balancer, and use **Auto Scaling** to replace failed instances **[S8][S4]**. For the database, use **Multi-AZ RDS** for automatic failover, or DynamoDB which is regionally replicated by design **[S7][S8]**. The HA/DR patterns reading frames this as "design for failure — no single point of failure" **[S8]**.

---

### Q4. "What's the difference between an IAM role and an IAM user?"

**Answer:** An **IAM user** is a long-lived identity with its own credentials, for a specific person or service **[S6]**. An **IAM role** has no long-term credentials — it's *assumed* temporarily and grants permissions via short-lived tokens, which is the preferred way for EC2/Lambda to access other services **[S6]**. Best practice: prefer roles over embedding user keys **[S6]**.

---

### Q5. "Which exam domain is weighted most heavily, so I should study it first?"

**Answer:** Per the official exam guide, **"Design Secure Architectures"** and **"Design Resilient Architectures"** carry the largest weightings, so prioritise security (IAM, KMS) and high-availability design **[S1]**. Cost-optimised and high-performing architectures follow **[S1]**. Study order should track those weightings **[S1]**.

---

## What to copy into your own `qa.md`
Ask the questions you keep getting wrong. A cited answer lets you jump straight to the source and re-read it — far better revision than a confident answer you can't verify. If NotebookLM can't find it in your readings, that's a gap in your materials to fill.
