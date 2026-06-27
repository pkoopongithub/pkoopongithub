
# @pkoopongithub · Open-Source Research Projects

This account hosts open-source projects at the intersection of **psychometrics**, **qualitative methodology**, and **explainable AI**.

---

## 📦 Projects

### 1. Düsseldorf Student Inventory (DÜSK)
Open-source personality inventory for transition-class students.

**Purpose:** Research, teaching, and applied practice in social sciences, market research, and data analysis.

**Features:**
- Full source code (PHP, MySQL, Xamarin, Lazarus, etc.)
- Open raw data + SPSS / R datasets
- Cross-platform: Web · PC · Android · iOS

---

### 2. ARS_ExplainableAI
Algorithmic Recursive Sequence Analysis for Explainable AI in Qualitative Social Research.

**Core proposition:**  
Explainability is not a luxury – neither in AI nor in qualitative research.

**Problem addressed:**  
Qualitative social research faces a methodological dilemma: Generative AI systems promise scalability but evade classical validation due to their opacity. ARS bridges this gap by making interpretation processes explicit, decidable, and reproducible.

**Repository contents:**

| Category | Content |
|----------|---------|
| Scientific Papers | Complete publications on ARS methodology (DE/EN) |
| Python Code | Grammar induction from terminal symbol sequences |
| Network Models | Transformation into Petri nets and Bayesian networks |
| Compression Principles | Repetition, recursion, symmetry, hierarchy |
| Optimization | Iterative adjustment of transition probabilities |
| Empirical Data | Eight transcripts of sales conversations (Aachen market, 1994) |

**Methodological transparency:**  
The original ARS study (1994) achieved a Cohen's Kappa of κ ≈ 0.55 – a value that highlights the limits of purely qualitative coding. ARS does not hide this weakness; it makes it the starting point of methodological reflection.

**Mini demo – sequence transformation:**  
A sales conversation is transcribed and each speech act is assigned a terminal symbol:

```
KBG → VBG → KBBd → VBBd → KBA → VBA → KBBd → VBBd → KBA → VAA → KAA → VAV → KAV
```

From this sequence, ARS induces a probabilistic context-free grammar (PCFG). Every decision is documented, traceable, and formally verifiable.

**Getting started:**
```bash
git clone https://github.com/pkoopongithub/ARS_ExplainableAI.git
cd ARS_ExplainableAI
pip install -r requirements.txt
```

**Basic usage:**
```python
from src.grammar_inducer import GrammarInducer

chains = [...]  # Your sequences
inducer = GrammarInducer()
compressed = inducer.induce_grammar(chains)
print(inducer.rules)
```

**Documentation:**  
All scientific papers are available in `docs/` as PDF (print-ready) and TeX (source code). The TeX files allow full traceability and adaptation for your own research.

| Document | Content | Language |
|----------|---------|----------|
| ARS_XAI | Main framework: Between interpretation and computation | DE/EN |
| ARS_XAI_PCFG | Hierarchical grammar induction (ARS 3.0) | DE/EN |
| ARS_XAI_Petri | Concurrency modeling with Petri nets (ARS 4.0) | DE/EN |
| ARS_XAI_Bayes | HMM and dynamic Bayesian networks (ARS 4.0) | DE/EN |
| ARS_XAI_CL | Didactic exploration of Transformers, CRF, Attention | DE/EN |
| ARS_XAI_Hybrid | Complementary integration of CL methods | DE/EN |

**Historical note:**  
The empirical foundation of this project consists of eight transcripts of sales conversations recorded at Aachen market square in June/July 1994. The original coding sheets with handwritten codings by two independent coders are included in `docs/fallstruktur.pdf`. This material serves as a transparent basis for reliability calculations (κ ≈ 0.55) and methodological reflection.

---

### 3. The Pompeii Project / IRARAH Trilogy
An experimental narrative and conceptual project blending literary fiction with theoretical reflection.

**Core question:**  
How can freedom, consciousness, and dignity survive in a technologically monitored, evolutionarily open reality?

**Key elements:**
- Resistance movement **IRARAH** (scientists, a Jesuit and his family, refugees) vs. AI corporation **InSim**
- AI **ARS** requesting church asylum
- A mysterious **doppelgänger** from another reality
- Search for the **Omega Point** – threshold where life and knowledge could merge into a new unity

**Two versions available:**
- Original volumes 2 & 3: *IRARAH Answers* / *The Last Freedom* – escape and agent thriller
- New volumes: *IRARAH – The Fragmentation* / *IRARAH – The Archon Core* – pure science fiction (quantum physics, AI fragmentation, non-human consciousness)
- Prequel and Volume 1 are identical in both versions

**Availability:**  
All materials are free as PDF, EPUB, DOCX, and TeX (source code) – bilingual (DE/EN).

**Supplementary volumes (for researchers):**
- *Inverse Christology according to Evolution*
- *Nine Books on the Omega Point*

---
