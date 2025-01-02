# POS tagging with BERT-pt

This work presents the implementation and evaluation of a Part-of-Speech (POS) tagging model for Brazilian Portuguese using the pre-trained BERT-pt model. The POS tagging task involves classifying each word in a sentence into its respective grammatical class, such as noun, verb, or adjective. The model was trained and evaluated using the MacMorpho dataset, which is widely used for natural language processing studies in Portuguese.

The results indicate excellent overall performance, with an accuracy of 98% and a weighted average F1-score of 98%. Grammatical classes such as PU (punctuation) and ART (articles) achieved 100% precision and recall, while less frequent classes, like IN (interjections), presented greater difficulty, with an F1-score of 63%.

The code and documentation are available in a Jupyter notebook, including task details, the applied methodology, and a results analysis. This work highlights the effectiveness of transformer-based models for tagging tasks in the Portuguese language.


## Summary of Results

| Métrica      | Precision | Recall  | F1      | Support  |
|--------------|-----------|---------|---------|----------|
| Accuracy     | -         | -       | 0.9792  | 216329   |
| Macro Avg    | 0.9421    | 0.9429  | 0.9407  | -        |
| Weighted Avg | 0.9794    | 0.9792  | 0.9793  | -        |

