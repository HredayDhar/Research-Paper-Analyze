# Paper Verification Protocol

Use this checklist for **every candidate research paper** before including it in a literature review. Fill every field with a web-verified fact and a source. Never fabricate a DOI, indexing status, quartile, impact factor, CiteScore, dataset, result, or other bibliographic/research information — write **"Not verified"** where a fact cannot be confirmed.

---

## Step 1 — Identify the Publication

-  Exact paper title
-  Authors
-  Publication year
-  DOI
-  Publisher
-  Exact journal/conference name
-  Volume, issue, and pages / article number
-  Publication type (journal article, conference paper, review, etc.)

## Step 2 — Verify the Journal / Venue

-  Journal or conference?
-  ISSN / eISSN, if applicable
-  Publisher
-  Scopus indexing status
-  Web of Science indexing status (if applicable)
-  Journal quartile (Q1/Q2/Q3/Q4), if applicable — **do not guess**
-  Subject category the quartile applies to
-  Whether the quartile applies to the paper's publication year specifically
-  CiteScore, if available
-  Impact Factor (JCR), if available
-  Whether the journal/venue is currently active
-  Any journal-quality concerns (predatory publisher lists, delisting, retraction concerns, etc.)

> If different databases or subject categories disagree on ranking, list them **separately** and explain the discrepancy — don't collapse them into one answer.

## Step 3 — Verify the Paper Itself

-  Research problem
-  Research objective
-  Research question(s), if stated
-  Dataset(s) / data source(s) used
-  Method / model / algorithm
-  Baseline methods compared against
-  Evaluation metrics
-  Main results
-  Main contribution
-  Limitations
-  Research gap addressed
-  Is the methodology reproducible?
-  Any code, dataset, supplementary material, or implementation publicly available?

## Step 4 — Research Relevance

Explicitly connect the paper's:

- Research problem
- Research objective
- Dataset/data source
- Methodology
- Results
- Contribution

back to **the user's research topic / thesis topic**.

Clearly state:

- What aspects overlap with the research topic
- What aspects are different
- What methodological or dataset gaps remain
- Whether the paper is directly relevant, partially relevant, or only useful as background

Do **not** assume relevance merely because the paper belongs to a broadly related field.

## Step 5 — Source Verification

Prioritize sources in this order:

1. Official journal / publisher page
2. Scopus
3. Web of Science
4. Journal Citation Reports (JCR), if available
5. Crossref
6. Official DOI record
7. Official conference/publisher proceedings page
8. The paper's full text/PDF
9. Other reputable academic databases or institutional sources

Every non-trivial factual claim must carry a source.

---

# Final Output Table

| Item                        | Verified information           |
| --------------------------- | ------------------------------ |
| Paper title                 |                                |
| Authors                     |                                |
| Year                        |                                |
| Journal / Conference        |                                |
| Publisher                   |                                |
| DOI                         |                                |
| Publication type            |                                |
| Scopus                      |                                |
| Web of Science              |                                |
| Quartile                    |                                |
| Quartile category           |                                |
| Quartile year               |                                |
| CiteScore                   |                                |
| Impact Factor               |                                |
| Dataset / Data source       |                                |
| Method                      |                                |
| Baselines                   |                                |
| Evaluation metrics          |                                |
| Main results                |                                |
| Main contribution           |                                |
| Limitation                  |                                |
| Research gap                |                                |
| Reproducibility             |                                |
| Relevance to research topic |                                |
| Recommended use             | Core / Supporting / Background |

---

## 1. Publication & Journal Verification

Explain exactly where the paper was published.

Verify:

- Journal/conference name
- Publisher
- DOI
- Volume/issue/pages or article number
- ISSN/eISSN
- Indexing status
- Quartile
- Quartile category
- Quartile year
- CiteScore
- Impact Factor

Clearly distinguish:

**Current journal metrics**
from
**Metrics/ranking applicable to the paper's publication year.**

If a metric cannot be historically verified, write **"Not verified"** rather than using the current value as a substitute.

---

## 2. Research Summary

Provide a concise academic summary covering:

### Research Problem

What problem does the paper attempt to solve?

### Objective

What does the study aim to achieve?

### Research Question

State the research question(s), if explicitly provided by the authors.

### Dataset / Data

What data was used?

Include:

- Dataset name
- Data source
- Number of samples/records, if verified
- Features, if relevant
- Classes/labels, if relevant
- Train/test split, if relevant

### Methodology

Explain the methodology, model, algorithm, framework, or experimental approach.

### Baselines

Identify the methods/models used for comparison.

### Evaluation

List the evaluation metrics and experimental setup.

### Results

Report the main results exactly as supported by the paper.

### Contribution

Explain what the authors claim as the main contribution.

### Limitations

Report limitations stated by the authors.

Also identify important limitations that are directly evident from the methodology, but clearly label them as **researcher interpretation** rather than attributing them to the authors.

---

## 3. Research Gap Analysis

Identify:

### Gap addressed by the paper

What previously existing limitation/problem does the paper attempt to address?

### Remaining gap

What important problems remain unresolved after this study?

### Dataset gap

Are there limitations related to dataset size, quality, diversity, realism, recency, class imbalance, or availability?

### Methodological gap

Are there limitations in the proposed methodology, model, experimental design, or comparison?

### Generalization gap

Does the method generalize across datasets, environments, devices, domains, or real-world conditions?

### Reproducibility gap

Can another researcher realistically reproduce the experiments from the information provided?

Do not invent gaps. Distinguish clearly between:

- **Author-stated limitations**
- **Evidence from the paper**
- **Researcher interpretation**

---

## 4. Relevance to the Research Topic

Explain specifically how the paper relates to the user's research topic.

Use this structure:

**Direct overlap:**
What part of the user's research topic does the paper directly address?

**Partial overlap:**
Which aspects are related but not directly addressed?

**Missing aspects:**
What important parts of the research topic are absent?

**Potential usefulness:**
How could the paper support the literature review or future research?

---

## 5. Reproducibility Assessment

Assess whether the study can realistically be reproduced based only on publicly available information.

Check:

- Dataset availability
- Source-code availability
- Feature/preprocessing description
- Model/hyperparameter details
- Experimental configuration
- Train/test methodology
- Evaluation methodology
- Hardware/software environment
- Random seeds or reproducibility information, if relevant

Use:

**Reproducibility: High / Moderate / Low / Not verified**

Explain the basis for the assessment.

---

## 6. Evidence Classification

For important findings, clearly distinguish:

### A. Author Statements

What the authors explicitly claim.

### B. Evidence

What is directly supported by the paper, dataset, experiment, or verified external source.

### C. Researcher Interpretation

Your analytical interpretation of the paper's strengths, weaknesses, gaps, or implications.

Never present researcher interpretation as if it were an author's statement.

---

## 7. Citation Recommendation

Determine whether the paper is appropriate for the literature review based on its verified relevance and research quality.

Use only:

- **Core** — directly relevant and useful for the central research discussion
- **Supporting** — relevant to a specific method, dataset, theory, comparison, or secondary aspect
- **Background** — useful for context or foundational understanding
- **Not recommended** — insufficient relevance, unverifiable publication information, or other substantial concerns

Explain the recommendation using **specific factual reasons**.

Do not assign arbitrary numeric scores.

---

## 8. Red Flags / Verification Warnings

Report any issues such as:

- DOI mismatch
- Title mismatch
- Author mismatch
- Publication-year discrepancy
- Journal/venue discrepancy
- Unverified indexing
- Unverified quartile
- Quartile category mismatch
- Current ranking incorrectly being presented as historical ranking
- Retracted paper
- Expression of concern
- Duplicate publication
- Suspicious publisher information
- Missing methodology
- Unavailable dataset
- Unsupported performance claims
- Insufficient experimental details
- Other important verification concerns

If no significant issue is found, state:

**No major verification concerns identified from the sources checked.**

---

# Final Academic Assessment

End with a concise assessment containing:

**Publication status:**
Verified / Partially verified / Not verified

**Research relevance:**
Direct / Partial / Background / Not relevant

**Methodological usefulness:**
Explain briefly.

**Main contribution:**
Explain briefly.

**Main limitation:**
Explain briefly.

**Research gap:**
Explain briefly.

**Literature-review use:**
Core / Supporting / Background / Not recommended

**Reason:**
Provide a concise evidence-based explanation.

---

# Strict Rules

1. **Search the web before making substantive factual claims.**
2. Never rely on memory alone for publication, indexing, ranking, or bibliographic information.
3. Never fabricate a DOI.
4. Never fabricate Scopus or Web of Science indexing.
5. Never assume a journal is Q1/Q2/Q3/Q4.
6. Never fabricate CiteScore or Impact Factor.
7. Never confuse a journal's quartile with the quality of an individual paper.
8. Always identify the **subject category** for a quartile.
9. Always distinguish **current ranking** from the ranking applicable to the **paper's publication year**.
10. If historical ranking cannot be verified, write **"Not verified."**
11. If a fact cannot be verified, write **"Not verified"**.
12. Never fabricate datasets, sample sizes, methods, results, limitations, or contributions.
13. Do not infer information that the paper does not provide.
14. Clearly distinguish author claims from your own research interpretation.
15. Every non-trivial factual claim must have a source.
16. Prefer primary sources over secondary sources.
17. If sources disagree, report the disagreement rather than choosing one without explanation.
18. Do not use the journal's reputation as evidence that the individual paper is high quality.
19. Do not recommend a paper solely because it is published in a high-quartile journal.
20. Verify the actual paper, not merely its abstract or search-engine result.
21. If the full paper is available, prioritize the paper itself for methodology, datasets, experiments, results, and limitations.
22. Never present an unverified claim as a fact.
23. If information is unavailable, explicitly write **"Not verified."**
24. Keep the analysis academically neutral and evidence-based.
25. Do not omit important negative findings simply because they reduce the apparent value of the paper.
