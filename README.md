# WN-BERT


## Models

### WordNet Embeddings

To represent WordNet as embeddings we retrained [path2vec](https://github.com/uhh-lt/path2vec) (shortest path version) and [wnet2vec](https://github.com/nlx-group/WordNetEmbeddings) on all synsets of [WordNet](https://wordnet.princeton.edu/documentation/wnstats7wn). You can download these retrained models from the following links:

- [path2vec](https://1drv.ms/u/s!At3ltLAV9ZCg5wRWbhNcHTkuulej?e=eoYJdS)
    - size: increased from ~82k to ~88k.
    - PoS coverage: ~75k nouns, ~13k verbs.
- [wnet2vec](https://1drv.ms/u/s!At3ltLAV9ZCg5wisx4ZK2FkyF6o8?e=lPhGe8)
    - size: increased from ~60k to ~150k.
    - PoS coverage: all. 

### WN-BERT

- [P2V-BERT](https://1drv.ms/u/s!At3ltLAV9ZCg5wWRRYZ195D8RVQI?e=Yrkv2W) (SST-2)
- [WN2V-BERT](https://1drv.ms/u/s!At3ltLAV9ZCg5wf3yQVyKIBK_Yby?e=TMR0Ns) (SST-2)
