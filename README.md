# AI Intake Checklist

A business-ready, generic checklist for approving a new AI tool. Use it before a tool goes live, not after a problem shows up.

This is a generic template, built from public practice. It is not a copy of any employer's internal policy, and it contains no client or employer material.

## 1. What the tool does

- [ ] What business problem does this solve, in one sentence?
- [ ] Who will use it, and for what decisions?
- [ ] Is it a chat tool, an agent, a coding assistant, or embedded in another product?
- [ ] What happens if it is wrong? Who is affected, and how badly?

## 2. What data goes in

- [ ] What data types will users paste, upload, or connect? (customer data, employee data, code, financial data, health data, other)
- [ ] Is any of that data regulated, confidential, or subject to a contract restriction?
- [ ] Does the vendor train on your inputs? Get the answer in writing, not from a marketing page.
- [ ] Where is data stored, for how long, and who at the vendor can access it?

## 3. Identity and access

- [ ] Does the tool use a shared account, or does every user sign in individually?
- [ ] For agents: does the agent have its own identity, separate from any human?
- [ ] What permissions does the agent or integration have? Least privilege, reviewed on a schedule.
- [ ] How do you revoke access, for one user and for the whole tool, in under an hour?

## 4. Output and decision risk

- [ ] Are outputs reviewed by a human before they affect a customer, a payment, a hire, or a security decision?
- [ ] How do you detect a wrong, biased, or hallucinated output?
- [ ] What is logged: prompt, output, user, time, and data sources used?

## 5. Security and vendor risk

- [ ] Does the vendor publish a security whitepaper, SOC 2, or equivalent?
- [ ] How are vulnerabilities and incidents reported to customers, and how fast?
- [ ] What is the exit plan? How do you export your data and turn the tool off?

## 6. Approval

- [ ] Tool name and vendor:
- [ ] Data types approved:
- [ ] Users approved:
- [ ] Human review required for:
- [ ] Review date (revisit at least annually, or after a major model change):
- [ ] Approved by:

## Agent use policy, short version

1. Approved tools only. If it is not on the approved list, do not paste company data into it.
2. Agents get their own accounts, least privilege, and a human approver for high-risk actions.
3. Never paste credentials, secrets, or regulated data into an unapproved tool.
4. Check outputs before acting on them. The model being confident is not evidence.
5. Report a suspected data leak or a strange agent action to security immediately, do not try to fix it quietly.

## Data classification, quick guide

- Public: can be shared anywhere, no approval needed.
- Internal: company use only, approved tools only.
- Confidential: named users only, human review required, agent use only with approval.
- Restricted: legal or compliance approval required before any AI use.

A clean checklist does not mean a tool is safe forever. Revisit it after model changes, vendor changes, and data changes.
