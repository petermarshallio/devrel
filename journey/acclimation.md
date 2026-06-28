# Acclimation

**The practitioner's question:** I am running this in production. I am finding
my feet.

Acclimation is the stage most often overlooked in DevRel planning — and its
absence is one of the most common sources of silent churn. The practitioner has
shipped. The thing they built during [Adoption](adoption.md) is running in
production. This feels like success. For the organisation, it often gets counted
as success. But the practitioner's journey is far from over.

The practitioner at Acclimation is experiencing the technology in a way they
have not before: under real load, with real failure conditions, with real
operational requirements. They are discovering things that no tutorial could
have prepared them for, because those things only become visible at scale and
over time.
## What is happening for the practitioner

Acclimation corresponds to the post-production phases of the software
development lifecycle: Release, Deploy, Operate, Monitor. The practitioner is no
longer building — they are running. The questions that define this stage are
different in character from the questions that defined [Adoption](adoption.md):

- Why does this behave differently under this load pattern?
- What does this metric actually mean, and should I be concerned?
- How do I tune this for our specific access patterns?
- What happens when this component fails, and how do I recover?
- Is the way I set this up during Adoption actually right for production, or do
  I need to rearchitect?

These questions are harder to answer from documentation alone. They require
operational experience — either the practitioner's own or borrowed from someone
who has been through it before. The practitioner at Acclimation is often running
at the edge of what the documentation covers. They are in territory that
tutorials never reached and that case studies only hint at.

The emotional character of Acclimation is also distinct. The practitioner who
sailed through Adoption with growing confidence may encounter Acclimation with a
different feeling: the nagging uncertainty of running something in production
that they do not yet fully understand. The first incident — the unexpected
outage, the performance degradation under real load, the operational surprise at
2am — tests whether the trust built during Adoption holds.

This is the stage where the practitioner forms their real, durable opinion of
the technology. The opinions formed during Assessment and Adoption are
provisional. The opinion formed during Acclimation — built on actual production
experience, on how the technology behaves when real things go wrong, on whether
the community and the vendor were there when they needed them — is the one that
they will carry into [Application](application.md), share with colleagues, and
eventually turn into [Advocacy](advocacy.md).
## What makes Acclimation succeed

**Operational documentation that matches reality.** The documentation needed at
Acclimation is different from the documentation needed at Adoption.
Getting-started guides are not relevant here. What matters is operational
reference material: how to monitor this correctly, how to interpret what you are
seeing, how to tune for common production patterns, how to plan for failure, how
to recover when things go wrong. This documentation is frequently underdeveloped
— it is less exciting to write than feature documentation, and its absence is
less immediately visible than a missing tutorial.

**Community members who have been through it before.** The most valuable
Acclimation resource is often another practitioner who encountered the same
operational situation eighteen months earlier and can describe what they did.
This is where the depth of Guardian engagement in community channels pays off
directly. The Guardian who answers the production-debugging question at 11pm —
not because they are paid to, but because they have been there — is doing
something no amount of official documentation can replicate.

**Responsive incident channels.** When something breaks in production, the
practitioner's expectation of the response time is compressed. The community
channel that responds in minutes rather than days to a production issue is
qualitatively different from the one that responds when someone gets to it. This
is not about 24/7 support — it is about having enough active Guardians and
engaged DevRel practitioners that production questions do not go unanswered for
long.

**Honest operational guidance, not just optimistic documentation.**
Practitioners at Acclimation are capable of handling honest operational
guidance. They need to know: what are the known failure modes? What do the most
experienced operators do differently from beginners? What did we get wrong early
in the design of this thing and what do we now recommend instead? Documentation
that acknowledges complexity and limitation earns trust at Acclimation in a way
that uncritically positive content does not.

**The sense that someone has been here before.** The practitioner running a
technology in production for the first time is navigating unfamiliar territory.
What makes that navigable is evidence that the territory is not unmapped — that
other practitioners have run this, that there is a body of operational
knowledge, that the questions they are asking have been asked before and have
answers. This evidence comes from community activity, from practitioner-written
content, from the volume and quality of operational documentation. An ecosystem
with active Guardians feels mapped. An ecosystem without them feels abandoned.
## What makes Acclimation fail

**The absence of post-production attention.** DevRel functions that concentrate
their investment in Adoption-stage content and under-invest in Acclimation are
essentially withdrawing support at the moment when the practitioner's commitment
is being tested most seriously. The practitioner who feels abandoned after
production deployment does not blame the documentation gaps — they blame the
organisation.

**Operational documentation that lags behind the product.** When the product
changes significantly — a new major version, a changed operational model, a
deprecated configuration option — the operational documentation needs to keep
pace. Practitioners who are running things in production and discovering that
the documentation no longer reflects how the product actually behaves have a
legitimately damaging experience. The trust erosion at Acclimation is difficult
to repair.

**First incident without support.** The first production incident with a new
technology is a defining moment. The practitioner who gets through it quickly,
with help, and with a clear understanding of what happened and why, will
continue. The practitioner who struggles alone for hours, reaches out to the
community and gets nothing, and eventually resolves the incident through brute
force without understanding what caused it, has had a crisis-level experience.
Some will continue — but their confidence is dented and their advocacy will
reflect it.

**No mechanism for routing operational feedback.** Practitioners at Acclimation
generate extremely valuable product intelligence: real operational edge cases,
real failure modes, real performance characteristics under real load. This
intelligence does not make it back to the product team unless there is a
deliberate mechanism for routing it. The organisation that does not collect this
signal is missing the highest-quality feedback available to it.
## DevRel's role at Acclimation

Acclimation is where the
[Connected Correspondent](../practitioners/connected-correspondent.md) becomes
the dominant DevRel instrument. The CC's relational depth — their ability to
maintain genuine ongoing contact with practitioners who are running the
technology in real environments — is what makes the Acclimation experience feel
supported rather than abandoned. The CC who knows which practitioners recently
shipped to production and checks in on how it is going is doing something that
has no self-service equivalent.

The [Information program family](../programs/2-information.md) remains relevant
— operational documentation and tutoring for production questions. But the
[Involvement family](../programs/3-involvement.md) becomes increasingly
important: the community channels where operational knowledge circulates, the
events where practitioners who have been through Acclimation share what they
learned.

The [Intel](../programs.md) layer is also critical here. Acclimation is one of
the richest sources of product signal in the entire journey — practitioners who
are running things in production and encountering its limits are generating
feedback that the product team cannot get any other way. DevRel's role is to
ensure that signal reaches the right people.

The practitioner who navigates Acclimation successfully arrives at
[Application](application.md) with something qualitatively different from the
practitioner who just completed Adoption: they have operational experience, they
have formed a real opinion, and they are beginning to have things worth saying
to other practitioners who are earlier in the journey.
