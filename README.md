# GOLD_Polish-TrOntonotes

This repository contains hand-labeled EN SRL lables for Polish.

### Process:
- A subset of EN-Ontonotes data is translated (TROntonotes) to Polish using PONS English-Polish translator.
- For each sentence, Stanza parser 1.2.3 version is applied to obtain all syntactic information.
- All the sentence then are manually labeled uisng EN propbank labels.

### Contributor
- Michał Ulewicz, Kyndryl, Poland




If you use this data in your work, please cite the following paper:

```
@InProceedings{jindal-EtAl:2022:LREC,
  author    = {Jindal, Ishan  and  Rademaker, Alexandre  and  Ulewicz, MichaÅ‚  and  Linh, Ha  and  Nguyen, Huyen  and  Tran, Khoi-Nguyen  and  Zhu, Huaiyu  and  Li, Yunyao},
  title     = {Universal Proposition Bank 2.0},
  booktitle      = {Proceedings of the Language Resources and Evaluation Conference},
  month          = {June},
  year           = {2022},
  address        = {Marseille, France},
  publisher      = {European Language Resources Association},
  pages     = {1700--1711},
  url       = {https://aclanthology.org/2022.lrec-1.181}
}
```
