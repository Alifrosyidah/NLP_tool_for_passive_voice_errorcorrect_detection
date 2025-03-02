**NLP Tool for Passive Voice Error Detection in Korean EFL Writing**

An NLP-based error detection tool designed to identify correct and incorrect passive voice usage in the writing of Korean EFL learners. This project integrates Learner Corpus Research (LCR) and Second Language Acquisition (SLA) theory to analyze cross-linguistic influence (CLI) in English learning.

📌 Project Overview
Korean learners of English often struggle with pseudo-passives due to L1 transfer effects. 
This project aims to:
Develop an automated NLP tool to detect passive voice errors in learner texts.
Use rule-based and hybrid NLP methods for accurate grammatical analysis.
Evaluate model performance using precision, recall, and F1-score.

📂 Dataset
- Gachon Learner Corpus (GLC) – A corpus of 16,112 texts (~2.5 million words) from Korean EFL learners.
- Annotated dataset of 50 argumentative essays, manually labeled for correct/error passive voice instances.
- Two human raters ensured high inter-annotator agreement for gold-standard data labeling.

🛠️ Methods & Tools
Corpus Preprocessing: Tokenization, lemmatization, POS tagging (spaCy, Pandas).
Grammar Rule Matching:
- Custom RegEx patterns to detect common passive voice structures.
- spaCy’s Matcher to classify correct vs. incorrect passive constructions.
Evaluation Metrics:
- Precision, Recall, F1-score computed using Scikit-learn.
- Validation across multiple test sets to refine detection accuracy.
Error Analysis & Rule Refinement:
- Identified false positives/negatives and iteratively refined grammar rules.
- Improved passive voice recognition for Korean L2 learners using linguistic insights.

🚀 Future Improvements
- Implement Transformer-based models (BERT, GPT-4, RoBERTa) for context-aware grammar detection.
- Expand dataset size for better generalization across L2 learner texts.
Develop an interactive grammar feedback tool for ESL learners.
