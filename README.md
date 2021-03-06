# Knowledge Graph Embeddings Papers
List of latest Knowledge Graph Embedding papers with their performance on Link Prediction task.

## Performance on Link Prediction Task
### FB15K

| Modelname     |  MR   |  MRR |Hits@1| Hits@3 |Hits@10  |
|:---------:    |:-----:|:----:|:----:|:------:|:-------:|
| **TransE**    |   -   | 46.3 | 29.7 |  57.8  |   74.9  |
|**DistMult**   |   42  | 79.8 |  -   |   -    |   89.3  |
| **ComplEx**   |   -   | 69.2 | 59.9 |  75.9  |    84   |
| **R-GCN**     |   -   | 69.6 | 60.1 |   76   |   84.2  |
| **ConvE**     |   64  | 74.5 |  67  |  80.1  |   87.3  |
| **TuckER**    |   -   | 79.5 | 74.1 |   83.3 |   89.2  |
| **RotatE**    |   40  | 79.7 | 74.6 |   83   |   88.4  |
| **D4-STE**    |   -   | 73.3 | 64.1 |   80.3 |   87.7  |
| **D4-Gumbel** |   -   | 72.8 | 64.8 |   78.2 |   86.4  |

### WN18

| Modelname     |  MR |  MRR |Hits@1| Hits@3 | Hits@10 |
|:---------:    |:---:|:----:|:----:|:------:|:-------:|
| **TransE**    |  -  | 49.5 | 11.3 |  88.8  |   94.3  |
| **DistMult**  | 655 | 79.7 |  -   |   -    |   94.6  |
| **ComplEx**   |  -  | 94.1 | 93.6 |  94.5  |   94.7  |
| **R-GCN**     |  -  | 81.4 | 69.7 |  92.9  |   96.4  |
| **ConvE**     | 504 | 94.2 | 93.5 |  94.7  |   95.5  |
| **TuckER**    |   - | 95.3 | 94.9 |  95.5  |   95.8  |
| **RotatE**    | 309 | 94.9 | 94.4 |  95.2  |   95.9  |
| **D4-STE**    |  -  | 94.6 | 94.2 |  94.8  |   95.2  |
| **D4-Gumbel** |  -  | 94.6 | 94.2 |  94.9  |   95.4  |

### FB15K-237

|   Model       |  MR |  MRR |Hits@1| Hits@3 | Hits@10 |
|:--------:     |:---:|:----:|:----:|:------:|:-------:|
| **TransE**    | 357 | 29.4 |   -  |    -   |   46.5  |
| **DistMult**  | 254 | 24.1 | 15.5 |  26.3  |   41.9  |
| **ComplEx**   | 339 | 24.7 | 15.8 |  27.5  |   42.8  |
| **R-GCN**     |  -  | 24.8 | 15.3 |  25.8  |   41.7  |
| **ConvE**     | 246 | 31.6 | 23.9 |   35   |   49.1  |
| **TuckER**    |   - | 35.8 | 26.6 |  39.4  |   54.4  |
| **RotatE**    | 177 | 33.8 | 24.1 |  37.5  |   53.3  |
| **D4-STE**    |  -  | 32.0 | 23.0 |  35.3  |   50.2  |
| **D4-Gumbel** |  -  | 30.0 | 20.4 |  33.2  |   49.6  |

### WN18RR

|   Model       |  MR  |  MRR |Hits@1| Hits@3 | Hits@10 |
|:--------:     |:----:|:----:|:----:|:------:|:-------:|
| **TransE**    | 3384 | 22.6 |   -  |    -   |   50.1  |
| **DistMult**  | 5110 |  43  |  39  |   44   |    49   |
| **ComplEx**   | 5261 |  44  |  41  |   46   |    51   |
| **R-GCN**     |   -  |   -  |   -  |    -   |    -    |
| **ConvE**     | 5277 |  46  |  39  |   43   |    48   |
| **TuckER**    |   -  | 47.0 | 44.3 |  48.2  |   53.6  |
| **RotatE**    | 3340 | 47.6 | 42.8 |  49.2  |   57.1  |
| **D4-STE**    |   -  | 48.0 | 45.2 |  49.1  |   53.6  |
| **D4-Gumbel** |   -  | 48.6 | 44.2 |  50.5  |   55.7  |


## Papers

  1. **DihEdral**: Relation Embedding with Dihedral Group in Knowledge Graph - ACL-2019 [[Paper](https://arxiv.org/pdf/1906.00687.pdf)][[Code]()]
  2. **RotatE**: Knowledge Graph Embedding by Relational Rotation in Complex Space - ICLR 2019 [[Paper](https://openreview.net/forum?id=HkgEQnRqYQ)][[Code](https://github.com/DeepGraphLearning/KnowledgeGraphEmbedding)]
  3. **TuckER**: Tensor Factorization for Knowledge Graph Completion - ArXiv [[Paper](https://arxiv.org/pdf/1901.09590.pdf)][[Code](https://github.com/ibalazevic/TuckER)]
