# Assessment

**The practitioner's question:** Should I use this? Can I?

Assessment is the stage at which the practitioner moves from understanding what
a technology is to deciding whether to adopt it. They have formed a mental model
during [Awareness](awareness.md). Now they are stress-testing it against their
real situation: their architecture, their team, their constraints, their
requirements.

This is a high-effort, high-stakes stage. The practitioner is about to make a
decision that could affect months or years of work. They are asking hard
questions and expecting honest answers.
## What is happening for the practitioner

Assessment is not a passive evaluation. Practitioners at this stage are actively
building the case — positive or negative — for adoption. They are asking:

- Can I actually get this to do the thing I need it to do?
- How hard is it to get started?
- What does production look like — operability, observability, failure modes?
- What is the migration path from what I have now?
- What happens when things break?
- What are other practitioners like me actually using this for, and are their
  situations close enough to mine to be informative?
- What are the known limitations, and do any of them disqualify this for my use
  case?

The practitioner at Assessment has typically also broadened their investigation
to alternatives. They are not evaluating in isolation — they are comparing. This
means that the Assessment experience for one technology is implicitly measured
against the Assessment experience for its competitors. A technology that makes
Assessment easy — that answers hard questions honestly, that surfaces
limitations proactively, that makes it straightforward to try — gains a
significant advantage over one that makes Assessment feel like a negotiation.

Assessment often involves more than one person. The practitioner doing the
investigation typically has to make a case to someone: a manager, an architect,
a team lead. The Assessment content that serves them needs to be usable not just
by the investigator but by the person who will make the final decision — who may
have a different level of technical depth and a different set of concerns.
## What makes Assessment succeed

**The ability to try before committing.** The practitioner who can stand up a
working instance, run a realistic test, and observe the actual behaviour of the
technology in conditions close to their own makes a better-informed Assessment
decision. Getting-started documentation, sandboxed environments, and quick-start
guides that reach a working state in minutes rather than hours compress the
assessment cycle significantly.

**Honest treatment of limitations and trade-offs.** Nothing builds Assessment
credibility faster than proactively acknowledging what the technology is not
good at. Practitioners who discover limitations through painful first-hand
experience — rather than finding them clearly documented — feel deceived. The
technology whose documentation says "this is optimised for X and not for Y"
earns more trust than the one that buries its limitations in a community thread
from eighteen months ago.

**Comparison content done well.** Practitioners doing Assessment will compare
alternatives whether or not the vendor facilitates it. Comparison content —
written honestly, from the perspective of helping the practitioner make a
genuinely informed decision — is more useful and more trusted than content that
tries to avoid the comparison. The practitioner who comes away from a vendor's
comparison guide thinking "that was fairer than I expected" is much closer to
adoption than the one who felt they had to go elsewhere for the honest version.

**Case studies that match the practitioner's context.** The most useful
Assessment content is the story of a practitioner who looked and felt like the
assessor — same scale, same architecture, similar constraints — who made this
decision and can speak honestly about how it went. Generic case studies that
hide specifics to avoid embarrassment are almost useless at Assessment.
Specific, honest accounts of real deployments with real results are extremely
valuable.

**Accessible technical depth.** Assessment questions are technical. The content
that answers them needs to go deep enough to actually address the question — not
to a level of depth that requires a PhD, but to the level at which a senior
practitioner asking serious questions gets serious answers. Shallow treatment of
hard technical questions at Assessment creates doubt rather than confidence.
## What makes Assessment fail

**The trial experience that does not match the reality.** If getting started is
easy but production is painful, Assessment converts to failed
[Acclimation](acclimation.md). The practitioner who successfully completes a
quick-start tutorial but then hits a wall when they try to replicate it in their
actual environment did not have a realistic Assessment experience — they had a
demo.

**Documentation that cannot answer real questions.** When a practitioner is deep
in Assessment, they will try to find answers in the documentation. If those
answers are not there — if the documentation covers the happy path thoroughly
but is silent on edge cases, failure modes, and real operational concerns — the
practitioner experiences a loss of confidence at exactly the wrong moment.

**Forced sales engagement before the practitioner is ready.** Practitioners
doing Assessment have a pronounced aversion to being handed to sales before they
have finished forming their own view. Assessment is a practitioner-led process;
interrupting it with a relationship they did not request signals that the
organisation values the sales relationship more than the practitioner's
autonomy. This is particularly damaging in the developer segment, where the peer
recommendation that follows a genuine Assessment experience is worth far more
than any deal accelerated by forced engagement.

**Inconsistent community evidence.** Practitioners at Assessment will look at
community forums, Stack Overflow, Reddit, and GitHub issues. What they find
there is independent evidence about the real experience of the technology. If
the community evidence is dominated by unanswered questions, expressions of
frustration, or known issues that appear in the official roadmap but have been
open for years, it will undermine even the best official Assessment content.
## DevRel's role at Assessment

Assessment is the stage where the
[Expert Educator](../practitioners/expert-educator.md)'s investment in
documentation, tutorials, and honest reference material pays off most directly.
The EE who has built the getting-started experience with real empathy for what a
practitioner is actually doing — not a contrived demo, but a realistic path
through a realistic use case — creates Assessment experiences that convert.

The [Connected Correspondent](../practitioners/connected-correspondent.md)
contributes through the Guardian relationships that surface the practitioner
case studies and honest comparison narratives that are most influential at this
stage. Practitioners doing Assessment trust other practitioners far more than
they trust vendor content; the CC is the person who builds the relationships
that make those practitioner voices available and willing to be heard.

The primary program home for Assessment content is the
[Information program family](../programs/2-information.md): the documentation,
the getting-started guides, the technical deep-dives, and the office hours where
a stuck practitioner can get a real answer from someone who knows. Assessment is
also where the [Innovation program family](../programs/4-innovation.md) has an
indirect role — the product quality and roadmap responsiveness that
practitioners discover during Assessment are partly the result of feedback loops
that DevRel maintains.

The practitioner who completes a successful Assessment carries something
specific into [Adoption](adoption.md): not just a decision, but a calibrated
expectation. Assessment sets the frame for everything that follows.
