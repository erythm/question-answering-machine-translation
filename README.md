# question-answering-machine-translation

**General Questions**

* Does using smaller LLMs count as an extension?

---

## **Proposed Extensions**

1. Multilingual ASKQE.
2. Multi-turn QA (follow-up questions, recursive questioning, conversational QA).
3. Domain adaptation (legal, travel/tourism, etc.).
4. Replace or improve the answer-overlap metric.
5. Data enrichment techniques (NER swaps, negations, numeric perturbations, pronoun switches)——>Then measure ASKQE’s ability to detect them.
6. Ablation study (remove NLI filtering, remove back-translation, remove fact extraction, QG without atomic facts) —>Measure impact on performance.

---

## **Proposed Extensions**

1. **Binary question generation** to remove the need for back-translation.
2. **Domain extension** to additional knowledge areas.
3. **Error localization**:

   * Adaptive question generation (ask more targeted questions to locate the error).
   * Post-editing using LLMs to correct wrong answers.
   * Explain to the user where the mistake is.
4. **Improved similarity metrics** between (A_{\text{srs}}) and (A_{\text{target}}).
5. **Improved contraTICO** 
