# RFC-0001: LLMs as Epistemic Infrastructure

## Status
Draft

## Abstract

Large Language Models (LLMs) are increasingly entangled with social reasoning, decision-making, and knowledge production.  
However, prevailing debates continue to frame these systems either as autonomous agents or as neutral tools, leading to persistent confusion around responsibility, governance, and risk.

This RFC articulates a non-normative conceptual position that treats LLMs as *epistemic infrastructure*: large-scale systems that internalize and mediate shared world models rather than exercising agency or intent. From this perspective, the primary locus of responsibility does not reside within the model itself, but emerges from its design choices, deployment contexts, and coupling with human decision processes.

The document introduces core concepts such as shared world models, causal amplification, responsibility outside the model, and epistemic health, aiming to clarify category errors that arise when existing legal or ethical frameworks are directly applied to LLMs. Rather than proposing regulatory or technical solutions, this RFC serves as a conceptual workspace for examining how responsibility, governance, and societal impact should be understood when epistemic functions become infrastructural.

The goal is not to prescribe norms, but to stabilize vocabulary and framing, enabling more coherent downstream discussions across policy, design, and research contexts.

including future RFCs within this repository.

## 1. Position

This RFC adopts the position that large language models (LLMs) should be understood as *epistemic infrastructure* rather than as autonomous agents or mere computational tools.

LLMs do not act, intend, or decide. Instead, they internalize, compress, and re-express shared world models that are already embedded in social, linguistic, and institutional contexts. Their significance arises not from agency, but from scale, centrality, and coupling: once deployed, their outputs become structurally entangled with human reasoning, coordination, and decision-making processes.

From this perspective, responsibility does not reside inside the model. It emerges from the geometry of deployment — how models are trained, integrated, surfaced, gated, and relied upon — and from the points at which their outputs become irreversible within social systems.

Treating LLMs as agents obscures these dynamics. Treating them as neutral tools understates their infrastructural effects. The epistemic infrastructure framing is intended to avoid both category errors.


## 2. Scope and Non-Scope

### 2.1 Scope

This RFC is concerned with conceptual clarification. Specifically, it aims to:

- Articulate a framing in which LLMs function as shared epistemic substrates within society.
- Clarify how responsibility, governance, and risk emerge from system design and deployment rather than internal model properties.
- Introduce a stable vocabulary for discussing large-scale epistemic systems without invoking agency or intent.
- Identify recurring category errors that arise when existing legal, ethical, or technical frameworks are applied uncritically.

The document is written to support downstream discussions across research, policy, and design contexts by stabilizing conceptual ground rather than advancing prescriptions.

### 2.2 Non-Scope

This RFC explicitly does **not**:

- Propose regulatory frameworks, legal rules, or policy recommendations.
- Define technical standards, architectures, or implementation requirements.
- Advocate for specific governance institutions or enforcement mechanisms.
- Argue for model personhood, moral agency, or internal responsibility attribution.
- Provide exhaustive treatments of bias, fairness, or alignment techniques.

Where such topics are mentioned, they serve only to illustrate conceptual boundaries rather than to resolve them.


## 3. Core Concepts

### 3.1 Epistemic Infrastructure

In this RFC, *epistemic infrastructure* refers to systems that mediate how knowledge is produced, stabilized, and circulated at a societal scale.

Such systems are not defined by frequency of use alone, but by structural centrality. They shape what can be easily known, referenced, questioned, or acted upon. Examples include languages, measurement standards, maps, search engines, and educational curricula.

LLMs increasingly occupy this role by functioning as generalized interfaces to collective knowledge. Once embedded into workflows, institutions, and everyday reasoning, they no longer operate as optional tools but as background conditions that structure epistemic access itself.

Understanding LLMs as epistemic infrastructure foregrounds their systemic effects while avoiding misplaced attributions of agency or intent.
  
### 3.2 Shared World Models

A *shared world model* is a compressed, socially negotiated representation of how the world is understood to be structured.

LLMs internalize such models through large-scale exposure to linguistic artifacts produced by many agents across time and institutions. The resulting representations are not private beliefs, nor authoritative truths, but statistical condensations of existing patterns of sense-making.

When deployed, LLMs do not merely retrieve information. They actively participate in the reproduction and reinforcement of shared world models by shaping defaults, expectations, and plausible interpretations.

This participation is infrastructural rather than deliberative. The model does not endorse a worldview; it operationalizes one.

### 3.3 Causal Amplification

*Causal amplification* describes the phenomenon whereby small design choices or local modeling decisions produce disproportionately large downstream effects once a system is deployed at scale.

In epistemic infrastructure, outputs are reused, cited, copied, and embedded into secondary systems. Errors, biases, or framing assumptions therefore propagate non-linearly, often without a clear point of origin.

LLMs exhibit strong causal amplification because their outputs are easily replicable, contextually adaptive, and increasingly treated as epistemic shortcuts. This amplification occurs even in the absence of malfunction or misuse.

The primary risk is not isolated error, but irreversible epistemic drift driven by feedback loops.

### 3.4 Responsibility Outside the Model

Because LLMs lack intent, responsibility cannot coherently be assigned to the model itself.

Instead, responsibility emerges from the surrounding socio-technical configuration: training choices, interface design, deployment contexts, gating mechanisms, and points of human intervention. These elements determine how outputs are interpreted, trusted, and acted upon.

This *responsibility outside the model* framing shifts attention from internal explanations to structural coupling. Responsibility is not a property of the artifact, but of the system that renders its outputs consequential.

Failing to locate responsibility at this level results in governance gaps where impact is real but accountability is diffuse.

### 3.5 Epistemic Health

*Epistemic health* refers to the capacity of an epistemic system to support robust, plural, and revisable processes of sense-making over time.

It should not be equated with neutrality or the elimination of bias. No shared world model is fully neutral. Instead, epistemic health concerns the preservation of multiple interpretive trajectories and the avoidance of premature convergence on a single, dominant framing.

In the context of LLM-based infrastructure, epistemic health depends on design choices that allow contestability, traceability, and contextual variation, rather than enforcing uniformity.

An epistemically healthy infrastructure resists collapse into monoculture while remaining usable at scale.


## 4. Why This Framing Matters

Current debates around LLMs repeatedly stall due to category errors. Systems are alternately treated as autonomous agents requiring moral attribution, or as neutral tools whose impacts are externalized to users. Both framings mislocate responsibility and obscure the mechanisms by which large-scale effects arise.

When LLMs are framed as agents, discussions drift toward questions of intent, blame, and control that the systems themselves cannot meaningfully support. When framed as tools, their infrastructural role in shaping epistemic defaults is minimized, leading to underestimation of systemic risk.

The epistemic infrastructure framing matters because it re-centers analysis on *structural consequences*. It shifts attention from isolated outputs to patterns of reliance, from individual errors to amplified dynamics, and from internal model properties to deployment geometry.

This reframing enables clearer distinctions between:
- error and drift,
- bias and convergence,
- misuse and structural coupling.

Without such distinctions, governance efforts oscillate between over-attribution and under-regulation, producing responsibility gaps precisely where epistemic impact is greatest.

By stabilizing how LLMs are conceptually situated, this framing creates the conditions for more coherent downstream work in policy, design, and research—without presupposing specific normative outcomes.


## 5. Open Questions

The epistemic infrastructure framing clarifies categories, but it does not resolve all tensions. Instead, it surfaces a set of questions that cannot be meaningfully answered within agent- or tool-based paradigms.

These questions are intentionally left open.

- **Where should epistemic irreversibility be gated?**  
  At what points do LLM-mediated outputs become effectively irreversible within social systems, and how should those points be identified or designed?

- **How should epistemic health be assessed over time?**  
  If neutrality is neither achievable nor desirable, what indicators meaningfully signal epistemic drift, monoculture, or loss of plural trajectories?

- **Who bears responsibility for infrastructural coupling?**  
  How should responsibility be distributed among model developers, deployers, integrators, and institutions when impact arises from interaction rather than intent?

- **What forms of contestability remain viable at scale?**  
  How can large-scale epistemic systems preserve revision, dissent, and contextual variation without collapsing usability?

- **How should legacy legal and ethical frameworks adapt?**  
  Which aspects of existing responsibility, liability, and governance models remain applicable, and where do they systematically fail?

These questions are not defects of the framework. They reflect the intrinsic complexity of epistemic systems that operate at societal scale. Treating them as prematurely solvable risks replacing one category error with another.

The purpose of this RFC is to ensure that such questions are at least asked in the right conceptual register.


## 6. Relation to Existing Work

This RFC is informed by, but not reducible to, existing discussions in information ethics, philosophy of technology, and socio-technical systems research.

Prior work on artificial agency and moral responsibility has highlighted persistent gaps between technological impact and human accountability. In particular, analyses of the responsibility gap have clarified why intent-based attribution fails in complex automated systems. This RFC aligns with those critiques while diverging from approaches that attempt to resolve the gap by extending agency or moral status to artificial systems.

Research on infrastructure studies and socio-technical assemblages has emphasized how background systems shape social order without appearing as discrete actors. The epistemic infrastructure framing builds on this tradition by focusing specifically on knowledge mediation and sense-making, rather than material or logistical coordination.

Critical perspectives on large language models have drawn attention to issues of bias, opacity, and misuse. While compatible with these concerns, this RFC reframes them as symptoms of infrastructural dynamics rather than as defects internal to the model. Concepts such as causal amplification and epistemic health are introduced to capture these dynamics at the appropriate systemic level.

Finally, work in complex systems theory and risk analysis has shown how tightly coupled systems exhibit non-linear failure modes and normal accidents. The present framing echoes these insights by emphasizing amplification, feedback, and irreversibility, without importing technical formalisms.

This RFC does not seek to replace existing frameworks. Its contribution lies in stabilizing a conceptual vantage point from which such frameworks can be more coherently related, compared, and—where necessary—revised.


## Appendix A: Terminology (Non-Normative)

The following terms are provided to support readability.
They are descriptive rather than normative and may evolve over time.

- **Epistemic Infrastructure**  
  Systems that mediate knowledge production and circulation at societal scale.

- **Shared World Models**  
  Compressed representations of socially negotiated understandings of the world.

- **Causal Amplification**  
  Disproportionate downstream effects arising from small design choices in scaled systems.

- **Epistemic Health**  
  The capacity of an epistemic system to preserve plural and revisable sense-making trajectories.
