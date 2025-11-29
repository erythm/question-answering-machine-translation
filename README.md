1. Multilingual ASKQE
Extend the framework to multiple languages (source/target, questions, answers, etc.).


2. Multi-turn / conversational QA
Support for:

follow-up questions,

recursive questioning,

dialogue/conversational QA to clarify or refine answers.



3. Domain adaptation / domain extension
Adapt ASKQE to specific domains (e.g., legal, travel/tourism) and additional specialized knowledge areas.


4. Data enrichment & robustness testing
Apply controlled transformations to the data to test ASKQE’s sensitivity, e.g.:

NER swaps (named entity swapping),

negations,

numeric perturbations,

pronoun switches, etc.,
and measure the system’s ability to detect them.



5. Improved similarity metrics (replacement of answer-overlap)
Replace or enhance the current answer-overlap metric with richer similarity metrics between  and .


6. Binary question generation (yes/no)
Generate binary questions to reduce or eliminate the need for back-translation in evaluation.


7. Ablation study of the ASKQE pipeline
Systematically remove components and measure their impact on performance, e.g.:

remove NLI filtering,

remove back-translation,

remove fact extraction,

perform QG without atomic facts.



8. Error localization & assisted post-editing

Adaptive question generation: ask targeted questions to better localize errors.

LLM-based post-editing: use LLMs to propose corrections to wrong answers.

User-facing explanations: explain to the user where and why the error occurs.



9. Improved contraTICO
Improve the contraTICO component/benchmark (e.g., coverage of phenomena, balance, translation/contradiction quality, etc.).


