# DevAudit

    Audit everything (starting with BitClout projects)


Concept by [https://bitclout.com/u/Taonaya](https://bitclout.com/u/Taonaya)

[https://bitclout.com/u/DevAudit](https://bitclout.com/u/DevAudit)

[https://github.com/devaudit](https://github.com/devaudit)



## Members
- [https://bitclout.com/u/Taonaya](https://bitclout.com/u/Taonaya)
- [https://bitclout.com/u/smartalec](https://bitclout.com/u/smartalec)
- [https://bitclout.com/u/transhumanist](https://bitclout.com/u/transhumanist)
- [https://bitclout.com/u/awesome_dev](https://bitclout.com/u/awesome_dev)
- [https://bitclout.com/u/BarryMichaelDoyle](https://bitclout.com/u/BarryMichaelDoyle)

- Join our Discord to become an auditor: [https://discord.gg/5wR9xgCvwf](https://discord.gg/5wR9xgCvwf)

**TRACK AUDIT PROGRESS HERE:**
[https://github.com/orgs/devaudit/projects/1](https://github.com/orgs/devaudit/projects/1)


## Intro


BitClout as a platform promotes the creation of third party applications that use BitClout as a data source, and means for user authentication. As this ecosystem expands, the potential risk of the users interacting with these third party sites is also rising sharply. 

## What is DevAudit?

DevAudit is intended to be an independent, unbiased (as much as humanly possible), impartial, and **community driven** committee that audits BitClout applications to promote transparency between BitClout developers, and the BitClout community.

DevAudit will inform the BitClout public about how apps handle their data, what permissions each application have, and how those apps are guarding your data in the event of attack. 

**It is to be noted** that some applications are required to have more permissions than others, due to their nature, or otherwise. More importantly, it's about how these applications handle your data, and who/what your data is allowed to be accessed by. 

## Why?

The need for watchdogs to inform the public about potential wrongdoing, or compromise could not be greater, as mass public adoption of BitClout is something we're all stiving for. 

In addition to this, the public should be informed with who they can trust with their data, and how applications are accessing their data.

## How?

DevAudit will start by investigating the public facing components of each respective third party application. The findings of each audit will be presented to the public. 

In addition to this, we are in the process of developing tools to allow developers to report vulnerability data right from their build, and deployment pipelines. **Developers, join our discord to learn more**

**To have any app audited, join our discord (listed above) and we'll add it to the backlog.**

In addition to auditing what's on public-domain (websites, open source projects, etc) we are open, and willing to partner with any and all BitClout project creators looking to secure their projects to ensure user safety, and security.  


## Current Touchpoints:

Below are **some** of the components of our audits. **Please join our discord to suggest additional audit touchpoints**

- [ ]  Legitimacy
    - [ ]  Proof of ownership
    - [ ]  Proof of development
    - [ ]  Legitimacy of responsible parties
- [ ]  Authentication
    - [ ]  Identity?
        - [ ]  Access Level (2, 3, 4)
    - [ ]  Self-Signing Authentication
        - [ ]  Seed Phrase Management
            - [ ]  Is Seed Sent to API? (Yes/No)
            - [ ]  Is Seed Logged anywhere? (Yes/No)
            - [ ]  Seed Captured In APM? (Yes/No)
            - [ ]  Seed Client side **ONLY?** (Yes/No)
            - [ ]  Seed Kept kept in app? If so, how?
        - [ ]  Private Key Management
            - [ ]  Encryption?
            - [ ]  Client Side? Server Side?
    - [ ]  Token Management
        - [ ]  TBD
- [ ]  Frontend
    - [ ]  Does the frontend bleed user auth data?
    - [ ]  Explanation of where frontend gets data
    - [ ]  More TBD
- [ ]  Backend
    - [ ]  TBD
- [ ]  Infrastructure
    - [ ]  SSL public endpoints?
