# Adoption

**The practitioner's question:** I am building with this.

Adoption is the stage at which the practitioner transitions from deciding to do something to actually doing it. The Assessment question — should I? — has been answered. Now the question is: how? The practitioner is building: setting up environments, writing first integrations, working through the documentation, hitting problems, getting unstuck, and slowly building a working mental model of how to use the technology in practice.

This is one of the most cognitively demanding stages in the journey. And it is one of the most consequential — the practitioner who gets through it successfully is on the path to [Acclimation](acclimation.md) and beyond. The one who gets stuck and stays stuck often leaves quietly, without telling anyone why.

---

## What is happening for the practitioner

Adoption corresponds roughly to the pre-production phases of the software development lifecycle: Plan, Code, Build, Test. The practitioner is making real architectural decisions, writing real code, and navigating real integration challenges for the first time. They are doing this against a background of existing responsibilities — Adoption is almost never someone's full-time job.

At this stage, the gap between what the practitioner knows and what they need to know is at its widest. The documentation they relied on during [Assessment](assessment.md) — which covered the getting-started path — now needs to go much deeper. They are encountering the parts of the technology that tutorials do not cover: the edge cases, the configuration options that matter in real deployments, the interactions between components that only become visible when you are doing something real.

The practitioner at Adoption is also frequently dealing with integration complexity — connecting the new technology to existing systems, matching it to existing architectural patterns, reconciling it with the constraints of the organisation they work in. This is where the distance between the quick-start demo and the real-world deployment becomes fully apparent.

Cognitive load is the central challenge of Adoption. The practitioner is managing the new technology's learning curve while continuing to deliver against other commitments. Anything that increases unnecessary cognitive load — confusing documentation, inconsistent APIs, tooling that does not behave predictably — directly increases the time and effort required to complete Adoption. Anything that reduces it — clear reference documentation, good error messages, patterns and examples that match real use cases — accelerates the path through.

---

## What makes Adoption succeed

**Documentation that goes beyond the happy path.** The getting-started tutorial got the practitioner through Assessment. What they need now is reference documentation — comprehensive, accurate, searchable — that can answer the specific questions they have when they have them. The documentation that succeeds at Adoption covers not just how to do things but why: why this configuration option exists, why this architecture is recommended, why this error occurs and what to do about it.

**Patterns and examples that match real use cases.** The practitioner who can find an example that closely resembles what they are building has a qualitatively better experience than the practitioner who has to extrapolate from toy examples to real complexity. Cookbooks, notebooks, and reference architectures that reflect real production patterns are high-leverage investments at this stage.

**Fast unblocking.** Practitioners who get stuck during Adoption and cannot find an answer quickly will stop. The time-to-unblock — the time between encountering a blocker and resolving it — is one of the most important experiential variables at this stage. This is what the [Tutoring](../programs/information.md) programme addresses: the human layer that provides real-time help when the self-service layer cannot.

**A responsive community.** When practitioners cannot find answers in documentation, they go to community channels. A community where questions get answered quickly — by other practitioners as well as by DevRel — dramatically improves the Adoption experience. The community where questions go unanswered, or where the standard response is "check the docs" without any further help, signals that practitioners who are stuck are on their own.

**Good error messages and observability.** Practitioners at Adoption spend a significant proportion of their time debugging. Error messages that tell them what happened and why — rather than surfacing cryptic codes or internal state — save real time. Observability that makes the technology's behaviour legible during development accelerates learning and reduces frustration.

---

## What makes Adoption fail

**The gap between the demo and the real thing.** If the getting-started experience significantly understates the complexity of real-world use, practitioners hit a wall at Adoption that they did not anticipate. The confidence built during Assessment and the early stages of Adoption collapses. Silent churn at this point is common — the practitioner abandons quietly rather than filing feedback, and the organisation never learns why.

**Documentation debt.** Adoption is where documentation gaps are most costly. The practitioner with a specific, technical, non-trivial question who cannot find an answer in the documentation — who has to file an issue, post in a forum, or wait for an office hours session — is experiencing a failure of the Information infrastructure that could have been avoided. Documentation that lags the product creates compounding debt at exactly the stage where practitioners most need it.

**Friction in the feedback loop.** Practitioners at Adoption regularly encounter things that are broken, confusing, or missing. If there is no clear, accessible mechanism for reporting these things — or if they report them and see no response — they stop reporting. The organisation that loses this feedback loop loses the most direct signal it has about what is making Adoption hard.

**Isolation.** The practitioner who gets stuck during Adoption and has no peer or community support is significantly more likely to abandon than the practitioner who has access to someone who can help. This is especially true for practitioners who are the first in their organisation to use the technology — they do not have a colleague to ask.

---

## DevRel's role at Adoption

Adoption is the natural home of the [Expert Educator](../practitioners/expert-educator.md). The EE's instrument — knowledge transfer, curriculum design, the ability to reduce cognitive load through good explanation — is exactly what Adoption requires. The EE who builds and maintains the documentation, the education pathways, and the tutoring infrastructure is directly reducing the friction that causes practitioners to abandon at this stage.

The primary programme homes for Adoption are the [Information family](../programs/information.md) (Education, Documentation, Tutoring) and the early parts of the [Involvement family](../programs/involvement.md) (where community support begins to supplement self-service).

The [DevOps lifecycle](../programs/README.md) mapping is useful here: Plan, Code, Build, and Test correspond to Adoption. The EE is most effective when they are close to this cycle — writing docs that reflect real build and test patterns, running office hours that address the questions that arise during coding, building education that follows the actual workflow of a practitioner building something real.

Adoption ends when the practitioner ships to production. What follows — [Acclimation](acclimation.md) — is a different stage with different demands. But the quality of the Adoption experience directly sets the conditions for what Acclimation looks like.
