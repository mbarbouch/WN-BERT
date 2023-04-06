# WN-BERT
Welcome to WN-BERT repository. This repo is set up for the research entiteld "WN-BERT: integrating WordNet and BERT for lexical semantics in
Natural Language Understanding". We publish here source code and our own trained models that we have worked with.

## Models

We distinguish two types of models: models that convert WordNet to embeddings and models where we realize an integration with BERT for enriched deep language modeling.

### WordNet Embeddings

To represent WordNet as embeddings we retrained [path2vec](https://github.com/uhh-lt/path2vec) (shortest path version) and [wnet2vec](https://github.com/nlx-group/WordNetEmbeddings) on all synsets of [WordNet](https://wordnet.princeton.edu/documentation/wnstats7wn). You can download these retrained models from the following links:

- [path2vec](https://condiver-my.sharepoint.com/:u:/g/personal/m_barbouch_condiver_nl/EbaCCxn1NLBJvNP8gavMHIgB7_pJVcd7_ZBYZ5ELBkVS3g?e=6h2EaA)
    - size: increased from ~82k to ~88k.
    - PoS coverage: ~75k nouns, ~13k verbs.
- [wnet2vec](https://condiver-my.sharepoint.com/:u:/g/personal/m_barbouch_condiver_nl/EUqe820VKw1MrFMV3Ek3WCEB71z6HBgdHE2KqJigsiCjvw?e=QeZTvV)
    - size: increased from ~60k to ~150k.
    - PoS coverage: all. 

### WN-BERT

- [P2V-BERT](https://condiver-my.sharepoint.com/:u:/g/personal/m_barbouch_condiver_nl/EcbWdjEh3lJCmG8LJhYNmp0BdPGdmrJKL1ct3Zrv_CsjBw?e=CenxGY) (SST-2)
- [WN2V-BERT](https://condiver-my.sharepoint.com/:u:/g/personal/m_barbouch_condiver_nl/EdqFuZrJSKpEiBMq9vwlRlEBfRQABOSNgkPmN7QJRhU12Q?e=RdlbWz) (SST-2)
- [BERT](https://condiver-my.sharepoint.com/:u:/g/personal/m_barbouch_condiver_nl/EcVU6fMJH85KvpdBHfS3_zoBOoEGFxkc-ecU-6IWgim9fw?e=7Dd2ff)
