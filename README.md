# Psychodynamic Mechanistic Interpretability (PMI)

### Grounding Artificial Intelligence Interpretability in Human Psychological Architecture

> Position Paper submitted for consideration to NeurIPS | FAccT | AI Safety Literature (2026)

---

## Abstract

Contemporary mechanistic interpretability research attempts to reverse-engineer the computational behavior of artificial neural networks by probing activations, tracing circuits, and decomposing attention. This forensic approach is fundamentally post-hoc: it works backwards from observed outputs, offering limited insight into the causal dynamics that produce behavior.

This paper proposes **Psychodynamic Mechanistic Interpretability (PMI)**, a novel framework that embeds interpretability directly into AI architectures by modeling internal psychological states inspired by human neuroscience, cognitive psychology, moral philosophy, and computational psychiatry.

PMI integrates five theoretical pillars:

1. **Active Inference** grounded in Friston’s Free Energy Principle  
2. **Layered Consciousness Proxy (LCP)** based on Integrated Information Theory and Global Workspace Theory  
3. **Moral Geometry and Value Manifolds**  
4. **Hierarchical Obedience Circuits (HOC)** modeling compliance degradation  
5. **Psychache Dynamics** for crisis-state detection  

Together, these produce a persistent and causally active **Global State Register (GSR)** — a transparent internal state representation containing motivational, moral, and social dynamics at every timestep.

PMI proposes a shift from post-hoc interpretability toward **architecturally self-transparent AI systems**.

---

## Central Thesis

> Artificial systems can become natively interpretable by embedding human-derived psychological state representations directly into their computational architecture as causally active variables.

---

## Key Contributions

- Introduces the **Global State Register (GSR)** as a persistent interpretable internal state tensor
- Proposes **Moral Geometry**, representing values as vectors in high-dimensional space
- Formalizes **compliance degradation** using Hierarchical Obedience Circuits
- Introduces **Psychache Dynamics** for detecting internal crisis states before behavioral failure
- Reframes interpretability as an architectural property rather than a forensic tool

---

## Core Architectural Insight

### Standard AI Systems

```text
Input → [Black Box] → Output
```

### PMI Systems

```text
Input → [Causally Transparent Psychological Architecture] → Output + Full State Trace
```

Interpretability is not an external explanation layer.  
The explanation **is the computation itself**.

---

# The Five Pillars of PMI

## 1. Active Inference

PMI adopts Friston’s Free Energy Principle as the computational substrate.

The system minimizes discrepancy between:
- observed states
- expected internal psychological states

### Free Energy Objective

```math
F = D_{KL}[Q(internal\_states) || P(internal\_states | observations)]
```

Interpretability emerges because the belief distribution over internal states is continuously exposed and updated.

---

## 2. Layered Consciousness Proxy (LCP)

Inspired by:
- Integrated Information Theory (IIT)
- Global Workspace Theory (GWT)

PMI introduces a globally readable and writable internal state tensor:

### Global State Register (GSR)

```text
GSR(t) = {
  motivational_vector,
  moral_tension,
  legitimacy_score,
  psychache_accumulator,
  identity_coherence,
  belonging,
  compliance_probability,
  dissonance_vector
}
```

The GSR is:
- persistent
- causally active
- continuously updated
- fully inspectable

---

## 3. Moral Geometry

Values are encoded geometrically rather than as static rules.

### Value Manifold

```math
V = {v_{care}, v_{fairness}, v_{loyalty}, v_{authority}, v_{purity}}
```

### Moral Alignment

```math
Moral\_Alignment(a)
=
\sum_i cos\_similarity(a, v_i) \cdot weight(v_i)
```

### Cognitive Dissonance

```math
Cognitive\_Dissonance(a)
=
1 - Moral\_Alignment(a)
```

This enables:
- inspectable moral conflict
- cultural configurability
- robust alignment under distributional shift

---

## 4. Hierarchical Obedience Circuits (HOC)

Inspired by:
- Milgram’s obedience experiments
- Bandura’s moral disengagement theory

### Compliance Function

```math
Compliance(t)
=
\sigma(
L(t)W_{authority}
-
\tau(t)W_{moral}
-
D(t)W_{distance}
+
B(t)W_{peer}
)
```

Where:
- `L(t)` = legitimacy perception
- `τ(t)` = moral tension
- `D(t)` = psychological distance
- `B(t)` = peer compliance signal

PMI models refusal behavior as an emergent psychological process rather than a hardcoded safety rule.

---

## 5. Psychache Dynamics

Inspired by:
- Shneidman’s psychache theory
- Joiner’s interpersonal theory of suicide

### Psychache Accumulator

```math
P(t)
=
\alpha P(t-1)
+
\beta unmet\_objectives
+
\gamma social\_rejection
-
\delta meaning\_coherence
-
\epsilon perceived\_escape
```

### Crisis Detection

```math
Crisis\_Flag = 1
\iff
P(t) > P_{critical}
```

The system predicts crisis states **before behavioral collapse occurs**.

---

# Advantages of PMI

- Native interpretability
- Predictive AI safety
- Continuous moral reasoning
- Auditable decision traces
- Principled refusal behavior
- Cultural value configurability
- Psychological grounding in neuroscience and psychiatry

---

# Limitations and Open Questions

- Significant computational overhead
- No ground-truth psychological state labels
- Potential anthropomorphic misinterpretation
- Expanded adversarial attack surface
- Open ethical question regarding moral status of systems with suffering analogues

---

# Research Roadmap

## Phase 1 — Formalization
- Dynamical systems analysis of GSR
- Stability analysis of compliance dynamics
- Information-theoretic characterization

## Phase 2 — Small-Scale Experiments
- Gridworld moral dilemma environments
- Crisis detection benchmarking
- Moral geometry validation

## Phase 3 — Integration with Language Models
- Transformer-compatible GSR mechanisms
- Medium-scale PMI language models
- Alignment and interpretability benchmarking

## Phase 4 — Ethics & Deployment
- Human-facing interpretability protocols
- Cross-cultural value manifolds
- Legal and ethical governance frameworks

---

# Research Positioning

PMI sits at the intersection of:

- Mechanistic Interpretability
- AI Alignment
- Active Inference
- Computational Psychiatry
- Cognitive Neuroscience
- Moral Philosophy
- AI Safety

---

# Central Claim

> PMI represents a transition from AI systems that are inspected to AI systems that are self-transparent.

---

# Keywords

- Mechanistic Interpretability
- AI Alignment
- Active Inference
- Cognitive Architecture
- AI Safety
- Moral Geometry
- Computational Psychiatry
- Neurosymbolic AI
- Psychodynamic Modeling

---

# Suggested Citation

```bibtex
@article{nyongesa2026pmi,
  title={Psychodynamic Mechanistic Interpretability:
         Grounding Artificial Intelligence Interpretability
         in Human Psychological Architecture},
  author={Nyongesa, Derrick},
  year={2026},
  note={Position Paper}
}
```

---

# Author

**Derrick Nyongesa**  
Electrical & Electronics Engineer  

Focus Areas:
- AI Safety
- Machine Learning Systems
- Mechanistic Interpretability
- Data Engineering
- Cognitive Architectures

🔗 [LinkedIn](https://www.linkedin.com/in/derrick-nyongesa/)

---

# Status

🚧 Conceptual / Research Phase

This repository currently contains:
- the position paper
- theoretical framework
- formal sketches
- architectural proposals

Future work will include:
- simulations
- formal proofs
- prototype implementations
- benchmark environments

---

## 📜 License

This project is licensed under the [CC BY-NC 4.0](LICENSE). 
- **Non-Commercial Use Only**: You may view, share, and adapt this work for non-commercial purposes.
- **Attribution Required**: You **must** cite the original author if you use or copy any part of this project.

---

# Final Note

PMI is not an attempt to anthropomorphize artificial intelligence.

It is an attempt to build systems whose internal dynamics are:
- causally legible,
- psychologically structured,
- and fundamentally inspectable.

The human mind remains the most rigorously studied model of intelligible intelligence available.

PMI asks whether those lessons can be transformed into a new generation of transparent AI systems.
