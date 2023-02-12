| Topic  | Document-level Grammar Error Correction | 
| ------------- | ------------- |
| Issue | Currently, all GEC systems process each sentence independently. However, document-level context may be needed to correct certain errors (e.g. present or past tense). Also, processing at the sentence level may lead to inconsistent modifications throughout whole document. |
| Solution | Incorporate document-level context |
| Contributions | <ol><li>Propose document-level GEC systems</li> <li>Employ three-step training strategy</li> <li>Compare with NMT-based models for document-level context evalutation</li></ol> |
| Model | Sentence level (baseline): encoder-decoder transformer </br> Document-context level: (1) Single Encoder Model, (2) Multi-encoder encoder side, (3) Multi-encoder decoder side |
| Single Encoder Model | Same architecture as the baseline model for sentence level. However, the difference is that this model considers context by concatenating previous sentence(s) to current sentence.