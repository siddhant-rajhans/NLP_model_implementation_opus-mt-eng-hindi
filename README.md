# NLP_model_implementation_opus-mt-eng-hindi
Implementation of [Helsinki-NLP/opus-mt-en-hi model](https://huggingface.co/Helsinki-NLP/opus-mt-en-hi)


* dataset: opus
* model: transformer-align
* source language(s): eng
* target language(s): hin
* model: transformer-align
* pre-processing: normalization + SentencePiece (spm32k,spm32k)
* download: [opus-2021-02-19.zip](https://object.pouta.csc.fi/Tatoeba-MT-models/eng-hin/opus-2021-02-19.zip)
* test set translations: [opus-2021-02-19.test.txt](https://object.pouta.csc.fi/Tatoeba-MT-models/eng-hin/opus-2021-02-19.test.txt)
* test set scores: [opus-2021-02-19.eval.txt](https://object.pouta.csc.fi/Tatoeba-MT-models/eng-hin/opus-2021-02-19.eval.txt)

## Benchmarks

| testset | BLEU  | chr-F | #sent | #words | BP |
|---------|-------|-------|-------|--------|----|
| newsdev2014.eng-hin 	| 7.0 	| 0.297 	| 520 	| 9538 	| 1.000 |
| newstest2014-hien.eng-hin 	| 9.9 	| 0.323 	| 2507 	| 60878 	| 0.938 |
| Tatoeba-test.eng-hin 	| 16.1 	| 0.447 	| 5000 	| 32904 	| 1.000 |
| tico19-test.eng-hin 	| 13.6 	| 0.338 	| 2100 	| 62738 	| 0.844 |

## To clone the original repo
```bash
  git lfs install
  git clone https://huggingface.co/Helsinki-NLP/opus-mt-en-hi
```
### if you want to clone without large files – just their pointers. prepend your git clone with the following env var:
```bash 
GIT_LFS_SKIP_SMUDGE=1
```


