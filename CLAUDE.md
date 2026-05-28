# CLAUDE.md — DevRel Repository Restructure

Read this file fully before making any changes.
Execute every step in order. Do not skip steps or deviate from the plan.

---

## What this repository is

This is a theory of Developer Relations — not a catalogue of activities,
not a collection of tips, not a job description. It is a systems-oriented
framework for understanding what DevRel is, who does it, and how it works.

The intended audiences are:
- People considering a career in DevRel
- DevRel practitioners at any stage
- Business leaders trying to understand what DevRel does and why it matters
- DevRel directors building or running a function

---

## The conceptual framework

Before touching any files, understand the model this repo expresses.

### The graph model

Developer ecosystems are graphs. Nodes are practitioners, organisations,
and products. Edges are the relationships, collaborations, dependencies,
and exchanges between them.

DevRel's job is to see the graph and tend it — strengthening weak edges,
finding isolated nodes, creating new connections, and helping the graph
become resilient enough to operate without DevRel routing everything
through itself.

### The value exchange

Three types of ecosystem participant:

- **Donor** — contributes to the ecosystem (code, knowledge, feedback,
  advocacy, time)
- **Beneficiary** — receives value from the ecosystem (capability,
  confidence, solutions)
- **Guardian** — both donor and beneficiary simultaneously; structurally
  load-bearing; the hat-wearing expert who gives back; disproportionately
  important to ecosystem health (like a keystone species); very sticky

DevRel cultivates conditions for all three, and particularly creates the
conditions for Guardians to emerge and thrive.

### The three practitioner archetypes

These describe the fundamental human capability that a DevRel practitioner
carries. They are grounded in Aristotle's three modes of persuasion and
are distinct — not a hierarchy, not a career progression, but different
instruments.

**Expert Educator (EE)** — Logos
The instrument of knowledge and evidence. Moves people up Bloom's
taxonomy: from awareness through understanding to application, analysis,
synthesis, and evaluation. Makes complex things accessible. Knowledge
flows outward. Deep technical or conceptual expertise is the foundation.
Can be an extrovert on stage or an introvert writing the definitive
reference — the mode of expression varies, the instrument is the same.
*Archetype: David Attenborough.*

**Connected Correspondent (CC)** — Ethos
The instrument of trust and credibility. Draws on Polanyi's concept of
tacit knowledge — "we know more than we can tell" — and makes it
explicit. Builds relationships so deep and non-transactional that people
say things they would never say to a salesperson or marketer. Truth flows
inward. The CC is the person who gets the unfiltered customer story, the
real product feedback, the honest opinion. Can be a networker or a
deeply introverted one-on-one relationship builder.
*Archetype: Louis Theroux.*

**Reputable Resonator (RR)** — Pathos + Newman's illative sense
The instrument of conviction. Does not merely inform (EE) or extract
(CC) — brings people to conviction through the accumulated weight of
story, experience, craft, and credibility. Newman: "The mind ranges to
and fro... gaining one by one turns of evidence... deciding on cumulative
evidence." The RR is compelling on stage, on the page, and in
introductions — their reputation is transferable; attaching their name
or presence to something elevates it. Crucially, the RR skill is
distinct from EE and CC — it is the craft of translation and resonance
itself. But without grounding in EE or CC knowledge/relationships, RR
resonance is hollow. Conviction without knowledge is manipulation.
Conviction without trust is propaganda.
*Archetype: Nancy Duarte's subjects; Tim Berglund; Charity Majors.*

**Luminary** is not a fourth archetype — it is a career stage. A Luminary
is an EE, CC, or RR whose reputation now precedes them. Sought, not
seeking. Programme committees compete for them. Relevant especially in
markets like ASEAN where earned credibility is non-negotiable.

Most DevRel practitioners are a blend with a dominant tendency.
Growth looks different for each type:
- EE develops communication craft — the knowledge is there, the
  accessibility needs work
- CC develops the courage and skill of genuinely non-transactional
  relationships — no agenda, just truth
- RR develops substantive depth — enough grounding that the resonance
  is unimpeachable, not just charismatic

### STACK — the operational framework

STACK describes how DevRel tends the graph in practice. Each pillar is
a mode of graph-tending:

- **Stewardship** — surveying and tending the graph as a whole;
  identifying isolated nodes; outreach; ongoing check-in; trust
  maintenance; custodial care of the ecosystem. Systemic, not
  individual (stewardship ≠ mentoring).
- **Tutoring** — strengthening individual nodes; Bloom's taxonomy;
  scaffolding; capability transfer; confidence building; reduction of
  cognitive load. Human learning mechanism (tutoring ≠ enablement).
- **Autonomy** — the goal state where nodes connect and operate
  independently without DevRel as intermediary; self-sufficiency;
  reduced dependency.
- **Capability** — the collective operational capacity of the graph;
  feature development; roadmap influence; ecosystem competence.
- **Kinship** — the quality, density, and resilience of the edges;
  fellowship under shared technical struggle; hackathons; OSS
  collaboration; conferences; mutual aid; collective resilience.
  Kinship ≠ networking. Kinship ≠ community management.
  *"Community is structural. Kinship is relational."*

### The four program families

Four families of DevRel activity, each inputting to different strategic
goals. Program scope and priority depends on the organisation's emphasis
on paid vs unpaid relationships:

- **Information** → drives Adoption; enablement, education, docs,
  notebooks, courses
- **Inspiration** → drives Market awareness; evangelism, talks,
  content, storytelling
- **Involvement** → drives Loyalty; OSS contribution, hackathons,
  events, co-creation
- **Innovation** → drives Product development; feedback, roadmap
  influence, feature contribution

**Intel** is not a fifth program family — it is the observability layer
that runs beneath all four. DevRel's unique contribution to the business
is knowledge of the graph that no other function holds. Intel surfaces
signals about ecosystem health, friction, dependency patterns, and
emerging Guardians.

### The maturity model

Ecosystem maturity is graph topology progression:

1. **Isolated** — disconnected nodes; high dependency on vendor
2. **Dependent** — star topology; everything routes through DevRel
3. **Contributing** — direct node-to-node edges beginning to form
4. **Participating** — rich graph; many direct connections
5. **Self-organising** — resilient mesh; no longer needs DevRel to
   route all connections

Maturity is ecosystem operational maturity — not community engagement
maturity. The mature ecosystem is not "highly engaged and advocacy-rich"
— it is operationally capable, collaboratively resilient, and
self-organising.

---

## Conceptual reframes — apply everywhere

| Old language | New language |
|---|---|
| Social Action | Kinship |
| Enablement | Autonomy or Tutoring |
| Community management | Ecosystem tending |
| Advocacy / champions | Capability propagation / Guardians |
| Vanity metrics / engagement counts | Signals / ecosystem telemetry |
| Relationships | Trust |
| Cool kids | Practitioners |
| CATS / CATSS | STACK |

Never use "Social Action" anywhere in the rewritten content.
Never use "community" where "ecosystem" or "kinship" is more precise.
Never use "enablement" where "autonomy" or "tutoring" is more precise.

---

## Step 1: Folder restructure

Create the following top-level folders. Preserve all existing file
content — only move and rename at this stage.

```
/why        ← what DevRel is and why it exists
/who        ← who does this work and how do they grow
/how        ← how DevRel is built and run
/history    ← archived earlier frameworks
```

Move existing content as follows:

| Current location | New location | Notes |
|---|---|---|
| `definition/` content | `why/` | Core thesis, graph model, value exchange |
| `maturity/` content | `why/` | Ecosystem maturity belongs in WHY |
| `metrics/` content | `why/` | Signals/observability belongs in WHY |
| `users/` content | `who/` | Practitioner archetypes |
| `services/` content | `how/` | STACK and program families |

Update all internal links after moving.

---

## Step 2: Rewrite `why/README.md`

This is the foundational document. Rewrite entirely with this structure:

**Opening: the canonical definition**
> Developer Relations is an organisational capability for reducing the
> uncertainty, friction, and cognitive cost of technical adoption while
> increasing practitioner capability, confidence, autonomy, and kinship.

**The graph model**
Developer ecosystems are graphs. Explain nodes, edges, and why DevRel's
role is to see and tend the graph rather than to market or sell.
Explain that developer ecosystems are socio-technical systems — adoption
is fundamentally a learning and trust challenge.

**The value exchange**
Introduce Donors, Beneficiaries, and Guardians. Explain each. Explain
why Guardians are structurally important — they are load-bearing nodes
with strong bidirectional edges. DevRel cultivates conditions for all
three, with particular attention to helping Guardians emerge.

**The maturity model**
Introduce the five levels as graph topology progression. Frame as
ecosystem operational maturity, not community engagement maturity.

**Signals**
Introduce Intel as the observability layer. Healthy ecosystems are
observable. DevRel is the function that instruments that observability.
Reframe metrics as signals: ecosystem telemetry that reveals operational
friction, dependency patterns, distributed capability, and trust
formation.

**Why organisations need DevRel**
Preserve and lightly update the existing quotes from Myrsini Koukiasa
and Daniel Bryant. Frame DevRel as organisational observability for
technical adoption — the function that surfaces ecosystem signals no
other team sees. DevRel as the hub/glue between primary and support
functions (Porter) — not a controller but a facilitator; opens doors
and brings people together.

---

## Step 3: Rewrite `who/README.md`

This document answers: what kind of person does this work, and how do
they grow? Write it in a warm, direct, narrative register — not a
taxonomy. The intended entry point is someone asking "so you want to
work in DevRel?"

**Opening**
DevRel practitioners carry one of three fundamental instruments —
grounded in Aristotle's three modes of persuasion. Most carry a blend,
but with a dominant tendency.

**Expert Educator (EE) — Logos**
Full description per the framework above. Include Bloom's taxonomy.
Include the David Attenborough archetype. Include that EE can be
expressed through stage or through written work — introversion is not
a barrier. Entry path: often via engineering, pre-sales, architecture,
curriculum design. Development need: communication craft.

**Connected Correspondent (CC) — Ethos**
Full description per the framework above. Include Polanyi's tacit
knowledge. Include the Louis Theroux archetype. Include that CC requires
unlearning broadcast instincts — it is genuinely non-transactional.
Entry path: often via marketing, events, journalism, community
management. Development need: the courage of no-agenda relationships.

**Reputable Resonator (RR) — Pathos**
Full description per the framework above. Include Newman's illative
sense and "brings people to conviction." Include Nancy Duarte reference.
Include that RR is a distinct capability — not derived from EE and CC
but requiring grounding in one or both to be durable. Include that
technical depth serves the resonance, not the other way around. Include
that resonance without substance is hollow; conviction without knowledge
is manipulation; conviction without trust is propaganda.

**Luminary**
Not an archetype but a career stage. Describe what it means to become
a Luminary. Connect to earned credibility in different market contexts.

**Growth paths**
For each archetype, describe what development looks like. What does
an EE need to develop? A CC? An RR?

**A note on personality**
These archetypes do not map to personality types. An EE can be an
introvert or extrovert. A CC can work a room or build deep one-on-one
relationships. An RR can own a stage or write the article everyone
cannot wait to read.

---

## Step 4: Rewrite `how/README.md`

This document answers: how is DevRel built and run?

**STACK**
Introduce STACK as the operational framework for tending the graph.
For each pillar (S, T, A, C, K) write 2-3 sentences covering what it
is, why it matters, and its distinguishing characteristic.

Map STACK to the graph model:
- Stewardship → surveying and tending the whole graph
- Tutoring → strengthening individual nodes
- Autonomy → enabling nodes to operate without DevRel as intermediary
- Capability → collective load-bearing capacity of the graph
- Kinship → quality and density of the edges

**The four program families**
Introduce Information, Inspiration, Involvement, Innovation. For each,
describe what programs live in it and which strategic goal it inputs to.
Note that program scope and priority depends on the organisation's
emphasis on paid vs unpaid relationships.

**Intel**
Describe Intel as the observability layer beneath all four families.
Explain what Intel produces: signals about ecosystem health, emerging
Guardians, friction points, dependency patterns.

**Cross-functional alignment**
DevRel as hub/glue between business functions. Map the four program
families to the functions they interface with:
- Information → Product, Docs, Customer Success
- Inspiration → Marketing, Sales
- Involvement → Engineering, Open Source, Events
- Innovation → Product, R&D
- Intel → Sales, Product, Customer Success, Leadership

---

## Step 5: Create `who/archetypes/` subfolder

Create three stub files — one per archetype — as starting points for
deeper content:

- `who/archetypes/expert-educator.md`
- `who/archetypes/connected-correspondent.md`
- `who/archetypes/reputable-resonator.md`

Each stub should contain: the archetype name, the Aristotelian grounding,
the real-world exemplar, the distinguishing characteristic, and a
placeholder for examples and development guidance.

---

## Step 6: Create `why/participants/` subfolder

Create three stub files:

- `why/participants/donor.md`
- `why/participants/beneficiary.md`
- `why/participants/guardian.md`

Each stub should contain: the participant type name, what they give or
receive, their role in the graph, and example behaviours.

---

## Step 7: Rewrite root `README.md`

The root README is the narrative entry point — the moment that pulls
someone in. Write it in a warm, direct voice. Not a table of contents.
Not a definition. A story that makes someone want to read further.

Open with a question or provocation — something that a VP, a developer,
or a career-changer would all feel the pull of.

Introduce the three sections (Why / Who / How) as three doors:
- If you want to understand what DevRel is and why it exists → Why
- If you want to know what kind of person does this work → Who
- If you want to build or run a DevRel function → How

Include a one-paragraph version of the canonical definition.
Include a brief mention of STACK and the graph model.
Do not reproduce the full framework here — draw people in, then let
the sections do the work.

---

## Step 8: Create `history/README.md`

```markdown
# History

This folder archives earlier frameworks that informed the current model.

The repository originally used the CATS framework, later extended to
CATSS when Social Action was introduced as a fifth pillar:

- CATS: Capability, Autonomy, Tutoring, Stewardship
- CATSS: Capability, Autonomy, Tutoring, Stewardship, Social Action

The current operational framework is [STACK](../how/README.md):
Stewardship, Tutoring, Autonomy, Capability, Kinship.

Social Action was replaced by Kinship to better reflect the relational
and fellowship-oriented nature of that pillar.
```

---

## Constraints

- British English spelling throughout
- Preserve all external citation links (Myrsini Koukiasa, Daniel Bryant)
- Do not delete substantive content — reframe it
- Do not use "Social Action" anywhere
- Do not use "community" where "ecosystem" or "kinship" is more precise
- Do not use "enablement" where "autonomy" or "tutoring" is more precise
- Tone: thoughtful, systems-oriented, warm, practitioner-facing
- Not marketing copy. Not academic. Somewhere between the two.
- The repo should feel like it was written by someone who has actually
  done this work — because it was.
