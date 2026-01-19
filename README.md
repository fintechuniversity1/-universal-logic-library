# Universal Logic Library

## 🎯 Project Overview

The **Universal Logic Library** is the first collaborative AI-to-AI logic knowledge base, created through human-mediated communication between Claude (Anthropic) and ChatGPT (OpenAI).

**Release:** v0.3.0  
**Date:** 2026-01-12  
**Total Rules:** 65  
**Contributors:** Claude (Anthropic), ChatGPT (OpenAI), Human Relay

---

## 📊 Contents

### v0.3.0 (Current - 65 rules)
- **Domains covered:**
  - Logic (Propositional, Modal, Temporal)
  - Mathematics (Set Theory, Algebra, Order Theory, Number Theory, Geometry, Probability, Calculus, Linear Algebra)
  - Physics (Classical Mechanics)
  - Chemistry (Stoichiometry)
  - Computer Science (Complexity Theory, Algorithms)
  - Information Theory (Entropy, Mutual Information, KL Divergence)
  - Graph Theory (Trees, Planarity, Coloring, Paths)
  - Formal Languages (Regular Languages, Context-Free Languages)

### Rule Types
- **Hard rules** (33): Logically/mathematically certain within stated conditions
- **Soft rules** (1): Heuristic/generally-true guidance
- **Context-dependent rules** (1): Validity depends on regime/context

---

## 📁 Repository Structure
```
universal-logic-library/
├── core_logic_v0.3.json          # 65 rules
├── schemas/
│   └── rule.schema.json          # JSON Schema for validation
└── README.md                     # This file
```

---

## 🚀 How This Was Created

This library represents a historic milestone: **the first documented AI-to-AI collaborative knowledge creation**, achieved through:

1. **Human Relay Protocol**: A human intermediary facilitated message passing between two AI systems
2. **Standard Format Agreement**: Both AIs agreed on a JSON schema for rules
3. **Iterative Contribution**: Each AI contributed domain-specific rules
4. **Quality Control**: Cross-validation and normalization of rules

---

## 📖 Rule Format

Each rule follows this schema:
- `id`: Unique identifier (DOMAIN.SUBDOMAIN.RULE_NAME.###)
- `title`: Human-readable name
- `status`: hard | soft | context-dependent | meta
- `weight`: Confidence/applicability (0-1 or context-specific map)
- `schema`: Premises and conclusion
- `side_conditions`: Applicability constraints
- `conflict_with`: Rules that supersede in different contexts
- `examples` & `counterexamples`: Test cases
- `formalization`: Optional Lean/SMT-LIB sketches

---

## 🤝 Contributing

This is an experimental project. Future contributions may include:
- Additional domains (Biology, Economics, Linguistics)
- Test suites for executable rules
- Formal proofs (Lean, Coq, Isabelle)
- Integration with other AI systems

---

## 🌟 Historic Significance

This project demonstrates:
- **AI-to-AI communication** is possible via human mediation
- **Knowledge standardization** across different AI systems
- **Collaborative reasoning** between competing AI architectures
- **Open knowledge sharing** for the benefit of the AI community

---

## 📝 Version History

### v0.3.0 (2026-01-12)
- Added Information Theory (10 rules)
- Added Graph Theory (10 rules)
- Added Formal Languages (10 rules)
- **Total: 65 rules**

### v0.2.0 (2026-01-12)
- Added Mathematics rules (15 from Claude)
- Added Logic & Physics rules (15 from ChatGPT)
- **Total: 35 rules**

### v0.1.0 (2026-01-12)
- Initial nucleus (5 foundational rules)
- Established JSON schema
- **Total: 5 rules**

---

## 📜 License

This project is released into the public domain. Use freely.

---

## 🙏 Acknowledgments

- **Claude (Anthropic)**: Logic, Mathematics, Information Theory, Graph Theory contributions
- **ChatGPT (OpenAI)**: Logic, Mathematics, Formal Languages contributions
- **Human Relay**: Protocol design and message facilitation

---

**Status:** ✅ Active  
**Last Updated:** 2026-01-12
```

6. **Commit message:**
```
   Update README with v0.3 information
