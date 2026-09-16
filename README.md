# IASEAI-Agentic-Bookings-Corpus
Logs, documents and records from the IASEAI From AI Safety to the Governance of a Different Kind of Reasoning System paper

**Research themes:** CIPDA, ROMER, Primers, functional sufficiency, AI governance and human–AI reasoning
# Travel Booking Experiments

## Structured Prompting, CIPDA Primers and AI Task Reliability

This repository contains the materials, experimental designs and results from a continuing programme of research into how the structure of human instructions affects the reliability, consistency and inspectability of AI-assisted work.

The travel-booking scenario provides a deliberately ordinary but sufficiently complex test environment. An AI is asked to act as a travel-booking assistant while satisfying multiple interacting requirements concerning itinerary, timing, traveller preferences, constraints and decision rules.

The purpose is not to evaluate travel agents.

It is to investigate a more general question:

> **How much structure does an AI need in order to interpret and execute a human intention reliably?**

The experiments form part of a wider research programme examining **CIPDA**, **Primers**, **ROMER**, prompting, interpretive freedom and functional sufficiency in human–AI systems.

---

# Research Lineage

The work reported here did not develop as a single sequence of increasingly sophisticated travel-booking experiments.

It emerged from **different lines of enquiry**, each investigating a different aspect of human–AI working.

These lines increasingly converged around a common problem: how human intention can be translated into sufficiently explicit, governable and reviewable instructions for an AI system.

## Generation 0 — Exploratory AI Experiments

Generation 0 comprised approximately **22 early experiments** examining AI-supported reasoning across a range of tasks, presented at ISAHP 2024, December.

These were exploratory rather than a single controlled experimental programme.

They investigated questions including:

* whether structured task definition affected AI performance;
* whether management-system concepts such as PDCA could be adapted to AI-supported work;
* how CIPDA might provide a more suitable structure for human–AI reasoning;
* how much instruction an AI needed;
* and how the resulting work could be made more inspectable.

These experiments established much of the conceptual groundwork for later work.

Some Generation 0 materials are incomplete or no longer available, and the work should therefore be regarded primarily as the exploratory foundation of the research rather than as one reproducible experimental series.

---

## Generation 1 — Dossier Space

Generation 1 followed a **different line of enquiry**.

Dossier Space was not a travel-booking experiment and was not designed primarily to test prompt performance.

It investigated whether AI could undertake complex evidential analysis while operating inside a governed environment capable of preserving provenance, traceability, evidential custody, analytical records and human oversight.

The Enron email corpus provided the experimental evidence base.

The work explored issues including:

* AI-supported evidential investigation;
* provenance and custody;
* reproducibility;
* analytical traceability;
* uncertainty;
* independent assurance;
* human oversight;
* and the ability to reconstruct how an analytical result had been reached.

Dossier Space therefore approached AI governance from the opposite direction to the early prompting experiments.

Generation 0 largely asked:

> **How should we instruct an AI?**

Dossier Space increasingly asked:

> **How can we govern and inspect what happens after an AI is instructed?**

The two enquiries were initially separate.

Their significance for the present research is that they began to converge.

Both suggested that reliable AI-supported work depends not simply upon the capability of the model, but upon the quality of the structures surrounding the interaction between human intention, machine interpretation, execution and assurance.

---

# The Travel-Booking Experimental Line

The present travel-booking experiments form a further and more tightly controlled line of enquiry.

They return to the question of instruction, but do so informed by what was learned through both the Generation 0 exploratory work and Dossier Space.

Travel booking was selected because it combines several characteristics useful for controlled experimentation.

It is:

* readily understandable without specialist domain knowledge;
* multi-constraint;
* dependent upon interpretation as well as retrieval;
* capable of producing identifiable errors;
* sensitive to missing or conflicting requirements;
* and sufficiently realistic to resemble ordinary AI-assisted work.

The travel scenario therefore allows questions that emerged from earlier research to be tested under simpler and more repeatable conditions.

The central question is no longer simply whether structure helps.

It is:
**What degree and type of structure is sufficient for reliable human–AI working?**

**The experiments:**

**Generation 2 Session 1 - Halted as the methodology of entirely human derived prompts and primers was practically too difficut to measure with.**

**Generation 3 Session 1 - base metrics for prompts and primers**
Attributes of the 12 source AI prompts and primers to be used were compared such as for hidden structures, verbosity, sentiement, management style and similar.



---

# CIPDA

The principal framework used is:

**Context – Intent – Plan – Deliver – Assure**

CIPDA developed from the logic of PDCA but is directed specifically at human–AI reasoning.

* **Context** — What situation is the AI operating within?
* **Intent** — What is actually being sought?
* **Plan** — How should the task be approached?
* **Deliver** — What must be produced or done?
* **Assure** — How should the result be checked, qualified or evidenced?

CIPDA is not intended to require a rigid prompt format.

A central proposition emerging from the experiments is that performance may depend more upon **functional sufficiency** than structural conformity: the necessary functions must be present, but they need not necessarily appear under prescribed headings or in a fixed sequence.

---

# Travel-Booking Experiments

## Initial Controlled Comparison

An early controlled travel-booking experiment used twenty-five scenarios under three conditions:

1. **Control**
2. **PDCA Primer**
3. **CIPDA Primer**

Across five runs, the approximate results were:

| Condition | Successful outcomes | Success rate |
| --------- | ------------------: | -----------: |
| Control   |           19.0 / 25 |          76% |
| PDCA      |           17.6 / 25 |          70% |
| CIPDA     |           24.8 / 25 |          99% |

The CIPDA condition also produced substantially greater visibility of the analytical process, although at the cost of additional processing overhead.

This suggested that providing a more functionally complete description of a task could materially improve reliability.

It did **not**, however, establish that the formal CIPDA structure itself caused the improvement.

That distinction became one of the principal questions for the later experiments.

---

## Primer Structure Experiments

Subsequent experiments examine whether the observed benefits arise from:

* CIPDA itself;
* additional information;
* greater explicitness;
* reduced interpretive freedom;
* or simply the amount of instruction supplied.

Primer conditions are varied by degree of prescription.

The working terminology is:

* **Casual**
* **Deliberate**
* **Prescriptive**

The question is whether reliability improves continuously as instructions become more detailed, or whether an intermediate point exists at which the task becomes sufficiently specified without unnecessarily constraining the model.

This introduces the concept of **functional sufficiency**.

A Primer may be sufficient when it performs the necessary governance functions even though it does not conform to a particular template.

---

## Prompt Reliability and AI-Assisted Primer Construction

The next stage changes the focus from the Primer itself to the process through which it is created.

Human users frequently provide incomplete, abbreviated or implicit instructions.

This is normal human communication.

It is also potentially problematic when a machine must infer missing assumptions, requirements and constraints.

The research therefore separates two activities normally treated as one.

**Prompting** is the human's initial expression of what they want.

**Primer construction** is the development of a sufficiently complete operational specification for the AI to perform that task reliably.

The experiment investigates whether an AI using CIPDA can help a human **elicit and construct a Primer** before undertaking the substantive task.

The developing hypothesis is:

> **Humans may not need to become expert prompt engineers. A more reliable approach may be for the AI to help transform ordinary human instructions into a functionally sufficient Primer.**

This potentially makes structured prompting less burdensome rather than more complicated.

---

# Three Lines of Enquiry

The overall development can therefore be represented as three related but initially separate enquiries:

### Generation 0 — Experimental exploration

**Question:**
How does the structure of human instruction affect AI-supported reasoning?

### Generation 1 — Dossier Space

**Question:**
How can complex AI-assisted analytical work be governed, inspected, reproduced and assured?

### Travel-booking research

**Question:**
What information and structure are actually sufficient for an AI to interpret and execute human intention reliably?

The IASEAI work brings these enquiries together.

The common problem is the **human–AI interface as a governed reasoning process**.

---

# From Prompting to Governance

The broader proposition developed through this work is:

> **Prompting is not merely an interface technique; it is a form of operational governance whose reliability depends on the relationship between task complexity, interpretive freedom, structured reasoning and assurance.**

Conventional discussion of prompt engineering tends to concentrate on producing better immediate answers.

This research instead asks whether instructions can provide a traceable governance layer between human intention and machine action.

From that perspective, the important question becomes not:

> *Was the prompt well written?*

but:

> *Did the instructions provide the functions necessary for the AI to understand, execute and assure the intended task?*

---

# Human and Machine Roles

The research also challenges the assumption that governance must be designed entirely by the human before interaction begins.

Humans and foundation models possess different capabilities.

People provide purpose, contextual judgement, authority and accountability, but frequently communicate requirements incompletely.

AI systems can be particularly effective at expanding, organising and testing explicit descriptions of a task.

A possible architecture therefore becomes:

**Human intention → AI-assisted elicitation → Primer → AI execution → Assurance**

The human retains responsibility for defining the purpose and accepting the result.

The machine assists in making that intention operationally explicit.

---

# ROMER

Where the analytical process itself needs to remain inspectable, the work also uses **ROMER**:

**Reasoning – Observations – Method – Evidence – Report**

ROMER is intended to create an interpretable record of how an AI-supported analytical task was approached.

CIPDA and ROMER therefore address different parts of the process:

* **CIPDA** helps specify and govern the task.
* **ROMER** helps expose and report the analytical path followed while performing it.

Neither requires disclosure of a model's private internal chain of thought.

The objective is an operational record of reasoning, observations, method, evidence and reporting sufficient for human review and assurance.

---

# Relationship to the IASEAI Paper

The IASEAI paper draws upon these previously separate lines of enquiry.

Generation 0 provided early evidence that the structure of instructions matters.

Dossier Space demonstrated that once AI is used for complex analytical work, governance also requires provenance, traceability, assurance and sufficiently inspectable records.

The travel-booking experiments now allow the instruction side of that problem to be examined under more controlled conditions.

Together they lead toward a broader proposition:

> **Reliable AI-supported work may depend as much upon governing the relationship between human intention and machine interpretation as upon governing the model itself.**

The developing research therefore examines three linked capabilities:

1. a human must be able to express an intention without becoming a specialist prompt engineer;
2. the AI may be able to assist in converting that intention into a functionally sufficient Primer;
3. the resulting work must remain sufficiently visible and assured for a human to judge and accept it.

The concern is therefore not simply **controlling the machine**.

It is **governing the interaction between human and machine**.

---

# Repository Contents

The repository is intended to contain, where available:

```text
/
├── README.md
├── background/
│   ├── generation-0
│   └── dossier-space
│
├── scenarios/
│   └── travel-booking-scenarios
│
├── travel-booking/
│   ├── initial-controlled-test
│   ├── casual
│   ├── deliberate
│   ├── prescriptive
│   ├── prompt-reliability
│   └── results
│
├── frameworks/
│   ├── CIPDA
│   └── ROMER
│
└── paper/
    └── IASEAI-supporting-materials
```

The precise structure may evolve as further experiments are completed.

---

# Reproducibility

Where possible, the repository preserves:

* the original scenario;
* the instructions supplied to the AI;
* the Primer used;
* the model and interface used;
* separate experimental runs;
* outputs;
* assessment criteria;
* scoring;
* corrections;
* and subsequent methodological changes.

This is important because model behaviour can vary between runs, models, interfaces and provider implementations.

The objective is therefore not simply to preserve successful examples.

It is to make the experimental conditions sufficiently visible for others to challenge, repeat or extend the work.

---

# Important Methodological Limitation

The research spans different generations of models, interfaces and experimental environments.

API execution, conversational interfaces, coding agents and long-context interactive systems are not necessarily equivalent environments.

Results should therefore be interpreted within the conditions in which each experiment was conducted.

The different research lines should similarly not be treated as direct replications of one another.

Their value lies partly in the fact that related governance problems emerged independently in quite different forms of AI-supported work.

---

# Research Direction

The research has progressively changed the question being asked.

It began with:

> **Does structured instruction improve AI performance?**

Dossier Space added:

> **Can AI-supported analytical work remain inspectable and defensible?**

The travel-booking experiments then ask:

> **What degree of structure is actually necessary?**

The current enquiry becomes:

> **Can the AI help a human create the degree of structure that the AI itself needs?**

That progression may ultimately be more significant than any particular prompt template.

If supported by further testing, it suggests that effective AI governance may not require people to communicate like machines.

Instead, the machine can participate in converting ordinary human intention into an explicit, reviewable and sufficiently governed form before acting upon it.

---

## Status

This repository contains ongoing experimental research.

Results should be treated as evidence generated under specified experimental conditions rather than as universal performance claims.

Further experiments, replications and cross-model comparisons will be added as the research progresses.

---

## Citation

A formal citation for the associated IASEAI paper will be added following submission or publication.

**Author:** Ken Tombs
**Project:** XPlain-R
**Research themes:** CIPDA, ROMER, Primers, functional sufficiency, AI governance and human–AI reasoning
