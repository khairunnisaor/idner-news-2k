# idner-news-2k


A dataset of Indonesian News for Named-Entity Recognition task. This dataset was previously provided by Syaifudin & Nurwidyantoro (2016) (https://github.com/yusufsyaifudin/Indonesia-ner). We manually re-annotated the dataset with a more standardized NER tags. We split this dataset into three files, namely train.txt, dev.txt, and test.txt. Each file consists of three columns which are Tokens, PoS Tag, and NER Tag respectively. The format is following CoNLL dataset which split each token into one line and each sentence is separated by one empty line. For the NER tag, we use the IOB format as illustrated in the example below. In terms of PoS tag, we tagged the data using UDPipe (http://ufal.mff.cuni.cz/udpipe), a pipeline for tokenization, tagging, lemmatization and dependency parsing whose model is trained on UD Treebanks.

Ner Tags: B-LOC, I-LOC, B-ORG, I-ORG, B-PER, I-PER, O
PoS Tags: PROPN, AUX, NUM, NOUN, ADP, PRON, VERB, ADV, ADJ, PUNCT, DET, PART, SCONJ, CCONJ, SYM, X

Example:
```
Menurut ADP O
Haposan NOUN B-PER
, PUNCT O
permintaan NOUN O
itu DET O
disampaikan VERB O
ke ADP O
Sjahril PROPN B-PER
dan CCONJ O
diteruskan VERB O
kepadanya ADP O
. PUNCT O

Di ADP O
PPP PROPN B-ORG
terdapat VERB O
wacana NOUN O
mengsung VERB O
calon NOUN O
presiden NOUN O
non-kader PROPN O
PPP PROPN B-ORG
untuk ADP O
maju VERB O
pada ADP O
pemilihan NOUN O
presiden NOUN O
2014 NUM O
. PUNCT O
```

# Research Paper
This work has been accepted by AACL-IJCNLP SRW 2020. If you are using this dataset in your work, please cite the following paper:

```
@inproceedings{khairunnisa2020,
  title={Towards a Standardized Dataset on Indonesian Named Entity Recognition},
  author={Siti Oryza Khairunnisa and Aizhan Imankulova and Mamoru Komachi},
  booktitle={Proceedings of the 1st Conference of the Asia-Pacific Chapter of the Association for Computational Linguistics and the 10th International Joint Conference on Natural Language Processing: Student Research Workshop}
  year={2020}
}
```

# MIT License

Copyright (c) 2020 khairunnisaor

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
