# Croatian-Language-Modeling
Resources for Croatian language modeling, classification and generation.
- [Datasets](#datasets)
- [Models](#models)
- [Corpora](#corpora)
- [Papers](#papers)
- [Libraries](#libraries)
- [Projects](#projects)

## <a name='Datasets'></a>Datasets
### NER
- The hr500k training corpus contains 506,457 Croatian tokens manually annotated on the levels of tokenisation, sentence segmentation, morphosyntactic tagging, lemmatisation, named entities and dependency syntax. [github](https://github.com/reldi-data/hr500k) [paper]()
- reldi_hr - This dataset is based on 3,871 Croatian tweets that were segmented into sentences, tokens, and annotated with normalized forms, lemmas, MULTEXT-East tags (XPOS), UPOS tags and morphological features, and named entities. [huggingface](https://huggingface.co/datasets/classla/reldi_hr) [paper](https://revije.ff.uni-lj.si/slovenscina2/article/view/7007)
### POS
- SETimes_sr [github](https://github.com/reldi-data/SETimes.SRPlus)
### Speech 
- The Croatian Parliamentary Spoken Dataset ParlaSpeech-HR 2.0 [huggingface](https://huggingface.co/datasets/classla/ParlaSpeech-HR)
### Classification
- Offensive language dataset of Croatian comments FRENK 1.0 [huggingface](https://huggingface.co/datasets/classla/FRENK-hate-hr) [paper](https://aclanthology.org/2022.parlaclarin-1.16)
### QA, Winograd
- (Multi-lingual exYU) LLM evaluation QA [github](https://github.com/gordicaleksa/serbian-llm-eval)

### Topic Modeling
- News topic modeling [github](https://github.com/dkorenci/topic_coverage)
  
### Sentiment

 - [Parla sent](https://www.clarin.si/repository/xmlui/handle/11356/1868) - Sentiment identification in parliamentary proceedings in the Croatian, Bosnian, Serbian parliament [paper](https://arxiv.org/abs/2309.09783). 6 level anotation schema.
### COPA - Choice of Plausible Alternatives
- The [COPA-HR dataset]()
  
## <a name='Models'></a>Models
- BERTić, CroSloEngBERT, XLM-RoBERTa - [huggingface](https://huggingface.co/classla), part of CLASSLA project
- YugoGPT - trained SOTA 7B LLM for Croatian, Bosnian, Serbian, Montenegrin lang [github](https://github.com/gordicaleksa)
- HR-LLM - Trained od BERTić + mc4 [paper](https://archive.ceciis.foi.hr/public/conferences/2024/Proceedings/S6/S6P3.pdf)
- 
## <a name='Corpora'></a>Corpora
- macocu_hbs, hr_news, mC4 (Multi-lingual), hrwac, classla_hr, cc100_hr, riznica, srwac, classla_sr, cc100_sr, bswac, classla_bs, cnrwac [huggingface](https://huggingface.co/datasets/classla/xlm-r-bertic-data)
- medical corpus A – MedCorA [paper](https://hrcak.srce.hr/file/356595)
- EUR-Lex 2/2016 parallel, EUR-Lex judgments parallel, MaCoCu Croatian Web v2, Open Parallel Corpus (OPUS), OpenSubtitles 2018, Riznica v0.1, CHILDES Croatian Corpus, Croatian parliamentary debates (ParlaMint 2.1), Croatian parliamentary debates (ParlaMint 2.1, CoNLL format), Croatian Web (hrWaC 2.2, ReLDI), Croatian Web (hrWaC 2.2, RFTagger), DGT-Translation Memory parallel – Croatian, ELEXIS Croatian Web 2020, ELEXIS Croatian Web 2020 (hrTenTen20) WSD sample, The CURLICAT Croatian corpus, SketchEngine Corpora [www](https://www.sketchengine.eu/corpora-and-languages/croatian-text-corpora/)
- European Language Grid [www](https://live.european-language-grid.eu/catalogue/)
## <a name='Papers'></a>Papers
- Agić & Ljubešić 2010 Lemmatization and Morphosyntactic Tagging of Croatian and Serbian [paper](https://aclanthology.org/W13-2408.pdf)
- Samardžić 2017 Universal Dependencies for Serbian in Comparison with Croatian and Other Slavic Language [paper](https://aclanthology.org/W17-1407)
- Ljubešić & Dobrovoljc 2019 What does Neural Bring? Analysing Improvements in Morphosyntactic Annotation and Lemmatisation of {S}lovenian, {C}roatian and {S}erbian [paper](https://www.aclweb.org/anthology/W19-3704)
- ...
## <a name='Libraries'></a>Libraries
- Terčon 2023 CLASSLA-Stanza: The Next Step for Linguistic Processing of South Slavic Languages: XPOS, UPOS, FEATS, ... [python](https://pypi.org/project/classla/) [paper](https://arxiv.org/pdf/2308.04255)

## <a name='Projects'></a>Projects
- CLASSLA - CLARIN Knowledge Centre for South Slavic Languages [www](https://www.clarin.si/info/k-centre/)
- TakeLab Retriever [www](https://retriever.takelab.fer.hr/)

