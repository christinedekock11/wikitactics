# wikitactics
Dataset for the paper "How to disagree well: Investigating the dispute tactics used on Wikipedia" by De Kock at al., published in EMNLP 2022.

Dataset consists of a list of dicts, each representing a disagreement. Each disagreement dict has 4 keys: `conv_id`, `utterances`, `split` and `escalation_label`.  `Split` refers to the split used by us, whereas `escalation_label` is a conversation-level constructiveness label from WikiDisputes (De Kock and Vlachos, 2021). 

The utterances are also a list of dicts, each containing `text`, `username`, `rebuttal_labels` and `coordination_labels`.  
