# Four Faces of AI Risk™

**Version 1.0 · Open for comment · November 2026 · © 2026 Evan Wheeler · Licensed [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)**

*The differences matter.*

This file is the complete working reference for the Four Faces of AI Risk: the four faces, the rules for placing a risk or a risk factor in a face, worked examples, and the vocabulary. It is written to be read by people and loaded into an AI assistant.

---

## The claim

"AI risk" is not one risk. It is four, with different causes, owners, controls, data, and forms of loss, and nothing useful happens in an assessment until you say which one you mean.

The face is the first question to ask of any AI risk scenario: why it happened. It sets the cause, and through the cause, the frequency driver.

## Built for measurement

Four Faces does two jobs. For executives, it is a mental model: four separate conversations in place of one blended worry about "AI risk." For risk analysts, it is the first scoping decision in a scenario they can measure. The lines between the faces were drawn for the second job as much as the first.

**The face sets the cause, and the cause sets what you estimate from.** Scenarios in different faces draw their frequency from different evidence and land different kinds of loss, so each can be estimated, and challenged, on its own terms.

| Face | What drives how often | What shapes the loss |
|---|---|---|
| **1 Strategy** | Decision cycles, launches, and supplier events such as repricing and deprecation, not recurring loss events | Variance against a plan or business case: stranded spend, forgone value, competitive erosion, structural cost |
| **2 Execution** | How much the AI is used and how often it errs, drifts, or is used carelessly; usage, defect, and incident data | Our own failure: operational, stakeholder, obligation, and information outcomes, and the cost of putting them right |
| **3 Subversion** | How often someone tries to push our AI past its bounds, and how often our safeguards stop them | Often the same outcomes as faces 2 and 4, with different response costs, insurance recovery, and secondary loss |
| **4 Attack** | Adversaries' activity and capability, largely outside our control; threat intelligence | Financial crime, disruption, and exposure with the speed, scale, and adaptability only AI makes possible |

**Why the lines fall where they do.** The 1/2 line separates decisions from operations, because face 1 is measured as variance against a plan, at the pace of decision cycles. The 2/3 line follows intent, because accidents and deliberate misuse come from different threat communities with different frequencies. The 3/4 line follows whose AI, because the safeguards that matter and the evidence for frequency both change when the AI doing the damage is theirs.

## The four faces

| # | Tag | Headline | Shorthand | The question |
|---|---|---|---|---|
| 1 | **Strategy** | Innovate with AI | We bet wrong. | Are we making the right bets? |
| 2 | **Execution** | Build and run AI responsibly | We botched it. | Is it well built and well run? |
| 3 | **Subversion** | Prevent abuse of our AI | They hijacked ours. | Can it be turned against us? |
| 4 | **Attack** | Defend against their AI | They attacked with theirs. | Is theirs aimed at us? |

### 1 · Strategy: Innovate with AI

**We bet wrong.** *Are we making the right bets?*

We move too slowly, too timidly, or fast with no strategy behind the bets. The AI may work exactly as intended; the choices about where, how fast, and how much were wrong.

**In a phrase:** A solution looking for a problem

**What it looks like:**

- Losing ground to faster competitors
- Bets mistimed or driven by hype
- Returns that never arrive (unattributable, or waiting on workflow changes no one made)
- Scarce talent and skills
- Cost and dependence that creep up

**The loss:** **Value:** stranded spend, forgone value, competitive erosion, structural cost increases. Measured as variance against a plan or business case, not as a loss event.

**So we:** Set the appetite. Name the bets, and the pace.

### 2 · Execution: Build and run AI responsibly

**We botched it.** *Is it well built and well run?*

AI we chose to adopt is badly designed, built, or used. No one acted against us; the cause is ours.

**In a phrase:** Move fast and break things

**What it looks like:**

- Wrong or inconsistent answers
- Bias and unequal performance
- Data used without rights or consent
- Obligations missed
- Oversight that cannot keep up

**The loss:** **Operational, stakeholder, obligation, and information outcomes:** our AI fails or misfires and harms us or the people who depend on it.

**So we:** Build and run it against a named set of risks, at every stage of its life.

### 3 · Subversion: Prevent abuse of our AI

**They hijacked ours.** *Can it be turned against us?*

Someone deliberately pushes our AI past the bounds we set, and we did not prevent it.

*In the face 3 definition, "our AI" means our AI and the data, models, and outputs it is built from or produces.* See edge rule 11.

**In a phrase:** Our AI, hijacked

**What it looks like:**

- Inputs that hijack behavior
- Poisoned data, models, or memory
- Models and secrets extracted
- Compromised supply chain
- Agents turned against us
- Our data or insights carried into someone else's AI

**The loss:** **The outcomes of face 2 or face 4, reached through our own AI:** harm to stakeholders, data exposure, theft of funds, obligations breached. Same outcomes, different cause, safeguards, and frequency.

**So we:** Test how it could be abused. Guard it like any other critical asset.

### 4 · Attack: Defend against their AI

**They attacked with theirs.** *Is theirs aimed at us?*

Someone turns their AI on us, and we are not ready.

**In a phrase:** A knife to a gunfight

**What it looks like:**

- Deepfake impersonation
- AI-enabled fraud and phishing
- Autonomous attack agents
- Frontier capability with the guardrails stripped

**The loss:** Financial crime, service disruption, data exposure, with the speed, scale, and adaptability only AI makes possible.

**So we:** Build defenses for AI-enabled attacks and deepfakes. Test them before an attacker does.

## How the four relate

- **Our AI: get it right**: faces 1–3.
- **Their AI: be ready**: face 4.

| | No one acts against us | Someone acts deliberately |
|---|---|---|
| **Ours** | 1 Strategy · 2 Execution | 3 Subversion |
| **Theirs** | Two cases (edge rule 2). Others' AI failing in their own systems is not ours to manage. Others' AI reshaping our competitive landscape belongs in face 1, because how we respond is our own strategic decision. | 4 Attack |

**By intent:** in faces 1 and 2, no one acts against us. The intentions behind the decisions were sound, or at worst careless, and they went wrong. In faces 3 and 4, someone acts deliberately: against the bounds we set for our AI, or against us with theirs.

**Two plus two.** The split between faces 1 and 2 is about what we did (chose the bet, or ran what we chose). The split between faces 3 and 4 is about whose AI someone else used (ours, or theirs). Told as two questions: Did somebody do this to us? If no: was it the bet or the build? If yes: did they use our AI or theirs?

This is not a 2×2. Faces 1 and 2 share a cell and are split by a third question: was it the choice of bets, or how a chosen AI was built and run?

The line between faces 2 and 3 is labeled **accident « » intent**.

## Placing a risk

Three questions, in order:

1. **Whose AI?** Theirs, aimed at us → face 4.
2. **Ours (our AI, or the data, models, and outputs it is built from or produces). Did someone deliberately push it past the bounds we set?** Yes → face 3.
3. **No. Where did it go wrong?**
   - In how AI we chose was built or run, causing an operational failure → face 2.
   - Where we chose to invest, how fast, and how much, causing a strategic shortfall → face 1.

**The three seams:**

| Seam | Question that decides it | Precise terms |
|---|---|---|
| 1 / 2 | Was it the choice of bets, or how a chosen AI was built and run? | Strategic shortfall (1) vs. operational failure (2). Decisions about whether, where, how fast, and how much are face 1. The performance of what was deployed is face 2. Place it by what went wrong, not when it became visible: a bet that was wrong when it was made is face 1, even when the loss first shows up in operations. |
| 2 / 3 | Did someone deliberately push our AI past the bounds we set? | Accident or carelessness (2) vs. intentional misuse (3). The test is deliberate action, not malice: a curious user who jailbreaks our agent is face 3. |
| 3 / 4 | Whose AI is it? | Ours (3) means our AI, adopted however sourced, and the data, models, and outputs it is built from or produces; theirs (4) means their AI, aimed at us. For a lay audience: which system did the damage, ours or theirs? and, where our assets have left our hands, did they misuse something of ours, or attack us with something of theirs? Face 3 feels like an enemy within because the harm comes through something of ours, but the person steering it may be an employee, a customer, a partner, or a stranger. |

**In face 1 the actor is always the decision-maker.** Frequency in face 1 comes from decision cycles, launches, and supplier events such as repricing and deprecation, not from recurring loss events.

**A 3/4 pair:** A hijacked payments agent (face 3) and a deepfake CFO (face 4) both end in theft of funds, with the same primary losses. Their cause, pathway, safeguards, and frequency driver all differ. The lay question settles it: which system did the damage?

## Edge rules

These settle the cases that come up most often.

1. **AI you adopt is yours, however it fails.** A vendor's model, a hosted service, an open-weight model you run: once adopted, its failures are face 2 and its abuse is face 3. Accountability does not transfer with sourcing. This is why the frame does not separate externally sourced AI into its own face.
2. **AI aimed at you is theirs.** Face 4 is about attack and fraud. AI that is merely nearby, failing in someone else's systems, is not an AI risk you manage; any exposure is handled as ordinary third-party or counterparty risk. Face 4 is deliberately not widened to accidental harm. Exception, which is face 1: the effect of competitors' or customers' AI on the value of our own strategy, such as advantages built on knowledge, data, or skilled work that others can now approximate. No one acts against us, but how we respond is our own strategic decision, so it belongs with the other strategic choices.
3. **Intent means a person's intent.** When our own agent escapes its sandbox or pursues an authorized goal by unauthorized means, no person acted deliberately against our bounds: face 2. For an AI agent, the person whose intent counts is its principal: the one it acts for.
4. **Careless misuse is face 2; intentional misuse is face 3.** An employee pasting client data into a chatbot is face 2. A user deliberately steering our AI to produce fraud or disinformation is face 3.
5. **Organizational misconduct sorts by the organization's stance.** Even where an individual acted knowingly (overstating AI capability, for example), the organization's position is that it did not mean it: face 2. A malicious insider acting against the organization is face 3.
6. **When intent is unknown, scope both.** Accident and intentional misuse are different threat communities with different frequencies. Write two scenarios rather than one blended one.
7. **Safeguard gaps and amplifiers take the faces of the losses they affect; only a general amplifier has no face.** Weak board oversight, no governance body, low AI literacy, or an insurance gap are not loss events on their own. Each takes the faces of the losses it would prevent or limit, and in an assessment it is a condition on those scenarios, never a scenario of its own. An amplifier changes how often, how far, or how badly a loss lands, and it takes the faces of the losses it amplifies, such as reputational damage when our AI fails in public. Only an amplifier that applies equally to any face, such as reputational damage in general, takes no face. That kind turns up in an organization's own register; a factor library limited to conditions unique to AI, such as the AI Risk Map, won't carry one.
8. **One condition can create two scenarios.** Some weaknesses we create can hurt us by accident and can also be exploited on purpose. Each way it can hurt us is a separate scenario, scoped in its own face, with its own frequency and controls. Example: our retrieval system returns documents beyond the requesting user's entitlements. A legitimate employee asks an ordinary question and is shown a confidential salary file: face 2, an operational failure, with frequency driven by normal usage. An attacker probes the same system to extract that file on purpose: face 3, intentional misuse, with frequency driven by attack attempts. Same weakness, two scenarios. Do not merge them, and do not pick one and drop the other.
9. **Spend on deployed AI is operational; spend decisions are strategic.** Runaway token or compute spend because usage of deployed AI is not managed is face 2. Forecasting, investment size, and provider choice are face 1.
10. **Backlash over AI use is face 1.** When stakeholders object to our use of AI although nothing failed (replacing people, using AI in hiring, an AI-only channel), the loss follows from the adoption choice. It is face 2 only when the objection is to conduct in use, such as failing to disclose that AI was involved.
11. **Our assets in their AI are face 3 when our bounds were crossed.** When a customer or partner takes data, insights, or outputs from our AI into their own AI and uses them past the terms we set (reverse-engineering the source, targeting individuals at scale, replicating our model to replace our service), that is deliberate action against our bounds: face 3, even though the AI doing the work is theirs and no one attacks us. The actor need not be hostile; a partner may believe the use is permitted (deliberate, not malicious). When no bounds were crossed, for example a competitor approximating our advantage with general-purpose AI and public information, it is face 1 under edge rule 2's exception.

## Going further with a risk-factor library

Four Faces works on its own. A risk-factor library widens each face's scope. The AI Risk Map is a companion library built to be used with it. It lists AI-specific causes, safeguard gaps, amplifiers, and outcomes, organized by who owns them. Where the AI Risk Map is available, name the face first, then use its factors to find what else could cause or worsen that scenario. Where it isn't, the rules here stand alone.

The AI Risk Map covers faces 1–3. Face 4 is outside its subject boundary by design and belongs on the threat register. The AI Risk Map is organized by who owns each risk, because domains don't line up one-to-one with faces: governance, procurement, workforce, and operations each hold factors in two or more faces, so one owner manages more than one kind of risk, each with its own controls. An assessment therefore runs in the other direction. **Name the face first, then use the AI Risk Map to widen the scope.**

The AI Risk Map is a separate work by the same author, licensed CC BY-SA 4.0: [https://www.riskframework.org/ai-risk-map/](https://www.riskframework.org/ai-risk-map/) · files, including `AI-Risk-Map.md` for AI assistants, at [https://github.com/wheels344i-gte/ai-risk-map](https://github.com/wheels344i-gte/ai-risk-map).

## Classifying risk factors

The three questions and the edge rules place a scenario. Risk registers and factor libraries, the AI Risk Map for instance, also hold factors that are not scenarios: safeguard gaps, outcomes, and amplifiers. These rules place factors consistently.

**Condition types.** How a factor enters an assessment. The definitions are shared with the AI Risk Map, so factors from it already carry them; any risk register can use them.

- **Cause:** the first thing that goes wrong; fix it and the loss never starts.
- **Safeguard gap:** a missing or weak control; fix it and the first failure still happens, but a later step is stopped or the loss is softened. It is a condition on the scenarios it protects, never a scenario of its own.
- **Amplifier:** changes how often losses happen, how far they spread, or how badly they land, without causing them.
- **Outcome:** names the loss event itself.

1. **A safeguard gap takes the faces of the losses it would prevent or limit.** Ask: if this safeguard is missing, what goes wrong? Give the factor those faces. (Weak board oversight → 1 and 2; no acceptable-use policy → 2; an insurance gap → 2 and 3.)
2. **Record separately how a factor enters an assessment: its condition type.** The values are shared with the AI Risk Map, so its factors already carry them. A cause becomes a scenario. A safeguard gap (a missing or deficient safeguard) becomes a condition on the scenarios it protects, never a scenario of its own. An outcome names the loss event rather than what produces it (stranded investment, labor-relations impacts, harmful output driving decisions); it takes the faces of the causes it names and is linked to them. An amplifier changes how often, how far, or how badly a loss lands; it takes the faces of the losses it amplifies, and only one that applies equally to any face takes no face. A factor library limited to conditions unique to AI, such as the AI Risk Map, holds no faceless amplifiers; the faceless case is for items in an organization's own register, such as reputational damage in general.
3. **One step only.** Assign faces by what a factor causes or protects directly. Do not follow longer chains (weak governance → weak controls → breach), or every factor ends up in every face.
4. **The 2/3 straddle test.** A cause straddles faces 2 and 3 only when its own condition can cause an operational failure with no one acting against us and create an opening someone can deliberately abuse; if it matters only when exploited, it is face 3. A missing safeguard straddles 2 and 3 only when it limits both kinds of loss and deliberate misuse is a main reason it exists, not just a possible case (incident response and investigation straddle; documentation and version control do not).
5. **When the attack has its own factor, the condition does not double up.** If a separate factor already names the deliberate version (data extraction, memory poisoning, a planted model), the condition that creates the opening takes face 2 only, and the two are linked. This does not apply to detection and response safeguards, which respond to whatever happened.
6. **Classify by the factor's own condition, not by the face of the loss it eventually worsens.** Our defensive model refusing to analyze attack data is face 2, even though it worsens a face 4 incident. When our AI is itself a control, its failure is a condition on the scenario it protects; that scenario's actor sets the frequency, and the AI failure keeps its own face for ownership.
7. **Event-type factors take the faces of their direct causes.** An agent taking an irreversible action is an event; it can be caused by the agent's own error (2) or by someone hijacking it (3).
8. **Supplier and people factors split by the loss, not the function.** Suppliers: the shape and cost of our dependence (concentration, lock-in, switching cost, exit terms, viability) → 1; the supplier's AI behaving badly in our use → 2 (edge rule 1). People: capacity, adoption, and foreseeable side effects of the adoption strategy on our own capabilities (deskilling, lost institutional knowledge) → 1; how people use and oversee deployed AI, and fallbacks when it is unavailable → 2. Procurement and workforce are functions that appear in both faces, as governance does.

## Why the differences matter

- **Each face implies a threat type, which drives frequency.** No one acts against us (1, 2), someone deliberately misuses our asset (3), someone attacks with their own tool (4). Blending them averages incompatible frequencies into one number nobody can defend.
- **Each face implies a distinct mix of outcomes; where faces share an outcome, they differ in response, recovery, and secondary loss.** Face 1's outcomes (stranded spend, forgone value, competitive erosion, structural cost) appear in no other face; faces 2, 3, and 4 can share an outcome such as data exposure or theft of funds, and then share its primary loss forms, differing in response costs (forensics versus revalidation), insurance recovery (2026 AI exclusions apply to AI we use, faces 2–3, not to attacks with theirs), and secondary loss (how regulators and the public treat negligence versus victimization).
- **Each face has a different control set.** Appetite and portfolio discipline (1), quality and variance management (2), prevention and detection (3), readiness and resilience (4).
- **Each face draws on different data.** Investment outcomes and market benchmarks, defect and incident rates, attack frequency against exposed AI, threat intelligence.
- **The face is the first scoping decision.** Name the face, then the asset, then the scenario.

### Worked example: customer data exposed through AI

| What actually happens | Face | Scenario |
|---|---|---|
| An employee pastes customer records into a public chatbot | 2 · Execution | Careless use; frequency from usage telemetry and DLP data |
| A model memorizes training data and repeats it to the wrong user | 2 · Execution | Model failure; frequency from testing and incident data |
| An attacker injects instructions that make our agent hand over data | 3 · Subversion | Intentional misuse; frequency from attack attempts against exposed agents |
| A partner loads customer insights from our AI into their own AI and uses them past the terms we set | 3 · Subversion | Intentional misuse of our asset (edge rule 11); frequency from the number of partners with access and how we enforce our terms |
| An attacker uses AI-written phishing to steal credentials and pull customer data | 4 · Attack | Their AI aimed at us; frequency from threat intelligence |
| We ban AI on customer data out of unfounded fear, while competitors adopt it with sound controls | 1 · Strategy | Strategic shortfall; the fear itself produces the loss |

One register line becomes six scenarios across all four faces.

## The finance view

**Nobody asks for one number called "the risk of the manufacturing line."** Finance already runs four separate conversations for every major asset. AI needs all four.

Every CFO already governs each material asset with four separate disciplines. AI is one more asset that gets all four questions.

| Face | Finance word | The question |
|---|---|---|
| 1 · Strategy | **Investment** | Did we invest in the right asset, at the right time, at the right scale? That's capital allocation, and choosing not to invest is a decision too. |
| 2 · Execution | **Error** | Is it performing the way we planned? When it isn't, nobody meant it to fail. That's operating error. |
| 3 · Subversion | **Misappropriation** | Is someone using our asset for their own gain? Auditors have a word for that: misappropriation. |
| 4 · Attack | **External threat** | Are we ready for the shocks we can't prevent? That's an external threat, and we hedge, insure, and plan for continuity. |

The 2/3 line is the one auditors have drawn for decades: error versus fraud, split by intent. Within fraud, misappropriation of assets is the category that matches face 3.

## How to use it

- **In a workshop.** Sort the fears in the room into faces before anyone starts naming risks.
- **Scoping a scenario.** Ask the three questions first. The face sets the cause, and the cause drives frequency.
- **With executives.** Lead with the finance view and the shorthand. Use the deck.

## Using this file with an AI assistant

Paste or upload this whole file, then instruct your assistant as follows.

```
You are helping me apply the Four Faces of AI Risk. Follow these rules:

1. Use only this document's definitions and rules. Do not invent a
   fifth face, and do not blend two faces into one scenario.
2. To place a scenario, ask the three questions in order (Whose AI?
   Did someone deliberately push ours past the bounds we set? Was it
   the bets or the build?). Say which question decided it.
3. Apply the edge rules by number when one settles the case, and cite
   the rule ("edge rule 4").
4. If intent is unknown, do not guess. Return two scenarios, one in
   face 2 and one in face 3 (edge rule 6).
5. If one condition can hurt us by accident and also be exploited on
   purpose, return two scenarios (edge rule 8).
6. For a risk-register factor that is not a scenario (a safeguard
   gap, an outcome, an amplifier), use the factor rules and give its
   condition type: cause, safeguard gap, amplifier, or outcome.
7. For each placement, give: the face (number and tag), the question
   or rule that decided it, what drives its frequency, and your
   confidence. Flag anything you could not place.
8. Do not score, rank, or quantify. This document contains no
   likelihood or loss data.
9. If the AI Risk Map (AI-Risk-Map.md) is also loaded, use its
   factors to widen each face's scope and cite their AIRM IDs. If it
   is not, work from this file alone: do not invent factor IDs or
   assume what the AI Risk Map contains.
```

**Questions this file answers well:**

- "Here is our AI risk register. Which lines are really more than one scenario, and what separates them?"
- "Our board asked us to 'assess AI risk'. What distinct scenarios should we scope, and who has to act on each?"
- "We are deploying a customer-facing AI agent. What scenarios should we scope before launch, beyond the model getting it wrong?"
- "A partner is loading our AI's outputs into their own model. How should we scope that risk, and what drives its frequency?"
- "This scenario mixes an accident and an attack. Rewrite it as separate scenarios, each with its own cause and frequency driver."
- "Which of these concerns are missing safeguards rather than scenarios?"
- "What have we left out? Check this list of AI risks for a kind of risk with no scenario at all."

**Questions it cannot answer:** how likely a scenario is, what it would cost, or which controls are effective. That data is not here by design.

**Further reading:** how-to articles on applying Four Faces, with worked examples, are published at https://www.riskframework.org/thinking/. They build on the model defined in this file and do not change it.

## Vocabulary
<!-- vocab:start -->
| Use | Avoid | Why |
|---|---|---|
| faces, kinds (as the name for the four) | dimensions, quadrants (as the name) | Faces are sorted into, not scored along; it is not a 2×2. |
| condition type: cause, safeguard gap, amplifier, outcome (how a factor enters an assessment) | acts as; consequence; loss (as a condition type) | The AI Risk Map's field and values since v2.0; one vocabulary across the works |
| abuse, intentional misuse (face 3) | misuse, unqualified | Misuse without intent is face 2 |
| deliberate action (the 2/3 test) | malice, malicious (as the test) | A curious jailbreaker is face 3 without malice |
| misappropriation (finance view) | fraud | "AI fraud" means face 4 to executives |
| strategic shortfall (face 1) | failure, unqualified, for face 1 | Face 1 is a failure of choices, not of operation; keep "failure" for face 2 or qualify it |
| external threat | external force | Face 4 has an adversary |
<!-- vocab:end -->

## What it is not

- **Not a catalog or a governance framework.** It names four kinds of risk. It does not list risk factors or controls, and it does not tell you how to govern AI.
- **Not a measurement method.** It helps you define scenarios well enough to measure. How you estimate frequency and loss is the job of your measurement method.
- **Not a prioritization.** Faces are sorted into, not ranked. Four Faces alone does not tell you which risks to address first.
- **Not an org chart.** Owners vary by organization. Assigning them is the next conversation.

## Limitations

- Intent is not always known when you scope. When it isn't, scope more than one face.
- Face 1 is measured differently: as variance against a plan, at the pace of decision cycles.

## License and citation

Four Faces of AI Risk © 2026 Evan Wheeler, licensed [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). You may share and adapt it, including commercially, with attribution. If you adapt it, say so.

Four Faces of AI Risk™ is a trademark of Evan Wheeler.

**Cite as:** Wheeler, E. (2026). *Four Faces of AI Risk* v1.0. Licensed CC BY 4.0. https://www.riskframework.org/four-faces/

---

*Four Faces of AI Risk™ v1.0 · © 2026 Evan Wheeler · CC BY 4.0.*
