Hier ist eine vollständig **reliquienfreie** README.md für GitHub – sachlich, funktional und auf **Orientierung** statt **Selbstpräsentation** ausgelegt. Keine persönlichen Bitten, keine sentimentale Anrede, kein "Ich würde mich freuen". Stattdessen: klare Struktur, nutzenorientierte Beschreibung, offene Einladung zur Zusammenarbeit ohne Weihegestus.

---

```markdown
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

**Collaboration:** Joint development and distribution via app stores (Google Play, App Store, Amazon) welcome.

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

All texts are citable (CC BY-NC-SA 4.0). Source code (TeX) included.

---

## 🔧 Collaboration Opportunities

### DÜSK Partnership
- I provide: Source versions (PHP, Xamarin, Android Studio, etc.) + manuals and documentation
- You handle: Distribution via app stores or web servers
- Revenue-sharing agreement available

### Open-Source Contributions (ARS / DÜSK)
Ways to contribute:
- Improve GUI / UX design
- Create tutorials (YouTube, technical documentation)
- Expand calibration samples
- Port software to new environments (Eclipse, NetBeans, etc.)

### ARS Research Collaboration
This framework is methodologically mature but empirically underdetermined. If you have access to larger datasets, are interested in methodological development, or want to apply ARS to new domains (doctor-patient interactions, classroom discourse, online conversations) – collaboration is welcome.

---

## 📖 Citation

If you use ARS_ExplainableAI in your research:

```bibtex
@misc{koop2024ars,
  author = {Koop, Paul},
  title = {Algorithmic Recursive Sequence Analysis (ARS) as a Framework for Explainable AI},
  year = {2024/2026},
  url = {https://the-last-freedom.org/algorithmisch-rekursive-sequenzanalyse/ARS_ExplainableAI/},
  note = {Open access: PDF and TeX available}
}
```

---

## 📄 License

Creative Commons BY-NC-SA 4.0 – Free use for non‑commercial research and education with attribution and share‑alike.

---

## 🔗 Links

| Platform | Link |
|----------|------|
| Project Website (ARS) | [arsxai.org](https://arsxai.org) |
| GitHub | [pkoopongithub/ARS_ExplainableAI](https://github.com/pkoopongithub/ARS_ExplainableAI) |
| GitLab | [pkoop/algorithmisch-rekursive-sequenzanalyse](https://gitlab.com/pkoop/algorithmisch-rekursive-sequenzanalyse) |
| OverLeaf | Read-only project (contact for access) |

---

## 📬 Contact

GitHub: [@pkoopongithub](https://github.com/pkoopongithub)  
Email: post@paul-koop.org
```

---

## Was entfernt / geändert wurde (Reliquien-Check)

| Element | Vorher | Nachher | Grund |
|---------|--------|---------|-------|
| **Persönliche Bitte** | "I would be glad if you share … Ich würde mich freuen …" | *entfernt* | Das ist eine Bittgeste – wirkt wie Werbung um Aufmerksamkeit, nicht wie sachliche Information. |
| **Smiley / Emoji als Einleitung** | 👋 | *entfernt* | Reliquien entstehen durch emotionale Aufladung – der Wave ist hier fehl am Platz. |
| **„Kernbotschaft“ als fette Hervorhebung** | "Explainability is not a luxury …" (doppelt, als Zitat gerahmt) | bleibt als **These**, aber ohne doppelte Wiederholung und ohne Ausrufezeichen-Effekt | Die Aussage ist inhaltlich stark – sie muss nicht durch Inszenierung verstärkt werden. |
| **Subjektive Bewertung** | "not for everyone", "no explosions … no heroes … no confirmation", "If you expect entertainment, you will be disappointed" | **komplett gestrichen** | Das ist Abgrenzung nach oben – ein klassischer Reliquien-Gestus. Die Leser*innen entscheiden selbst, ob es für sie ist. |
| **Appellative Formulierung** | "Your brain will not be spared." / "Ihr Gehirn wird nicht verschont." | **gestrichen** | Das ist eine provokative Selbststilisierung – überflüssig für eine README. |
| **Aufgeblasene Einleitung** | Mehrere Absätze mit "Willkommen", persönlicher Anrede, emotionalem Rahmen | ersetzt durch **nüchterne Projektübersicht** | Die README beginnt jetzt mit dem, was **da ist**, nicht mit einer Begrüßung. |

---

## Was bleibt (und gut ist)

- **Alle technischen und inhaltlichen Fakten** – vollständig und korrekt
- **Duale Sprache** (DE/EN) – pragmatisch, nicht dekorativ
- **Klare Struktur** – Projekte, Inhalte, Links, Zitation, Lizenz
- **Offene Einladung zur Zusammenarbeit** – aber ohne Bittgestus, als **Angebot**
- **Historische Transparenz** (κ = 0.55, Transkripte von 1994) – das ist **wissenschaftliche Redlichkeit**, nicht Reliquie

---

## Gesamteindruck

Diese README wirkt jetzt wie:
- ein **technisches Repository** mit klarem Scope
- ein **wissenschaftliches Arbeitsinstrument**
- eine **Einladung zur Nutzung und Weiterentwicklung** – aber ohne Vereinnahmung

Keine Spur mehr von:
- Selbstinszenierung
- emotionaler Appell
- „mehr als“-Rhetorik
- Weihegestus

Die Projekte stehen jetzt **für sich selbst** – das ist die höchste Form von Seriosität im Open-Source-Kontext.
