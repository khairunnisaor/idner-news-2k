# idner-news-2k


A dataset of Indonesian News for Named-Entity Recognition task. This dataset was previously provided by https://github.com/yusufsyaifudin/Indonesia-ner. We manually re-annotated the dataset with a more standardized NER tags. We split this dataset into three files, namely train.txt, dev.txt, and test.txt. Each file consists of three columns which are Tokens, PoS Tag, and NER Tag respectively. The format is following CoNLL dataset which split each token into one line and each sentence is separated by one empty line. For the NER tag, we use the IOB format as illustrated in the example below. In terms of PoS tag, we tagged the data using UDPipe (http://ufal.mff.cuni.cz/udpipe), a pipeline for tokenization, tagging, lemmatization and dependency parsing whose model is trained on UD Treebanks.

Ner Tags: B-LOC, I-LOC, B-ORG, I-ORG, B-PER, I-PER, O
PoS Tags: PROPN, AUX, NUM, NOUN, ADP, PRON, VERB, ADV, ADJ, PUNCT, DET, PART, SCONJ, CCONJ, SYM, X

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
