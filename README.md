### Exploring the Potential of Large Language Models (LLMs) for Low-resource Languages: A Study on Named-Entity Recognition (NER) and Part-Of-Speech (POS) Tagging for Nepali Language
Description:
Significant progress in Natural Language Processing (NLP) has been achieved thanks to the advancements made by Large Language Models (LLMs), which demonstrate exceptional performance across a range of NLP tasks. 
This research specifically delves into assessing the capabilities of LLMs especially BERT variants in Named Entity Recognition (NER) and Part-of-Speech (POS) tagging, focusing on Nepali, a language with limited resources. 
The objective is to examine how effectively these models perform in languages with constrained resources through experimentation and evaluation on two datasets: ILPRL and EBIQUITY. 
In this study, we explore the efficacy of eight LLMs specifically for Nepali NER and POS tagging tasks.

Note: This work has been accepted in LREC-COLING 2024 - The 2024 Joint International Conference on Computational Linguistics, Language Resources and Evaluation Lingotto Conference Centre - Torino (Italia) (https://lrec-coling-2024.org/)

Datasets:
ILPRL(CoNLL-2003 IOB): https://ilprl.ku.edu.np/  or contact (bal@ku.edu.np)

EBIQUITY (BIO Taggig scheme): https://github.com/oya163/nepali-ner/blob/master/data/ebiquity/stemmed/total.txt   

Usage:
1. Please specify the correct dataset path in the code implementation
2. Change labels to "ner" or "pos" depending on your data
3. Specify models. Please refer to https://simpletransformers.ai/docs/ner-specifics/ and hugging face library: https://huggingface.co/models
4. Train and test

## Citation

If you find this work or the associated datasets/models useful, please cite our paper:

**Exploring the Potential of Large Language Models (LLMs) for Low-resource Languages: A Study on Named-Entity Recognition (NER) and Part-Of-Speech (POS) Tagging for Nepali Language** *Bipesh Subedi, Sunil Regmi, Bal Krishna Bal, and Praveen Acharya* **LREC-COLING 2024**

[[Paper PDF]](https://aclanthology.org/2024.lrec-main.611/) [[ACL Anthology]](https://aclanthology.org/2024.lrec-main.611.pdf)

### BibTeX

<details>
<summary>Click to expand</summary>

```bibtex
@inproceedings{subedi-etal-2024-exploring,
    title = "Exploring the Potential of Large Language Models ({LLM}s) for Low-resource Languages: A Study on Named-Entity Recognition ({NER}) and Part-Of-Speech ({POS}) Tagging for {N}epali Language",
    author = "Subedi, Bipesh  and
      Regmi, Sunil  and
      Bal, Bal Krishna  and
      Acharya, Praveen",
    editor = "Calzolari, Nicoletta  and
      Kan, Min-Yen  and
      Hoste, Veronique  and
      Lenci, Alessandro  and
      Sakti, Sakriani  and
      Xue, Nianwen",
    booktitle = "Proceedings of the 2024 Joint International Conference on Computational Linguistics, Language Resources and Evaluation (LREC-COLING 2024)",
    month = may,
    year = "2024",
    address = "Torino, Italia",
    publisher = "ELRA and ICCL",
    url = "[https://aclanthology.org/2024.lrec-main.611/](https://aclanthology.org/2024.lrec-main.611/)",
    pages = "6974--6979"
}
