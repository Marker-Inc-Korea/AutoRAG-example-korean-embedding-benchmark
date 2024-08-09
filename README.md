# Korean Embedding Benchmark with AutoRAG

This is a benchmark of Korean embedding models. 
With [AutoRAG](https://github.com/Marker-Inc-Korea/AutoRAG), you can make this kind of benchmark easy and fast.


# Result

### Top-k 1

| Model name                            | F1         | Recall     | Precision  | mAP        | mRR        | NDCG       |
|---------------------------------------|------------|------------|------------|------------|------------|------------|
| paraphrase-multilingual-mpnet-base-v2 | 0.3596     | 0.3596     | 0.3596     | 0.3596     | 0.3596     | 0.3596     |
| KoSimCSE-roberta                      | 0.4298     | 0.4298     | 0.4298     | 0.4298     | 0.4298     | 0.4298     |
| Cohere embed-multilingual-v3.0        | 0.3596     | 0.3596     | 0.3596     | 0.3596     | 0.3596     | 0.3596     |
| openai ada 002                        | 0.4737     | 0.4737     | 0.4737     | 0.4737     | 0.4737     | 0.4737     |
| multilingual-e5-large-instruct        | 0.4649     | 0.4649     | 0.4649     | 0.4649     | 0.4649     | 0.4649     |
| Upstage Embedding                     | 0.6579     | 0.6579     | 0.6579     | 0.6579     | 0.6579     | 0.6579     |
| paraphrase-multilingual-MiniLM-L12-v2 | 0.2982     | 0.2982     | 0.2982     | 0.2982     | 0.2982     | 0.2982     |
| openai_embed_3_small                  | 0.5439     | 0.5439     | 0.5439     | 0.5439     | 0.5439     | 0.5439     |
| ko-sroberta-multitask                 | 0.4211     | 0.4211     | 0.4211     | 0.4211     | 0.4211     | 0.4211     |
| openai_embed_3_large                  | 0.6053     | 0.6053     | 0.6053     | 0.6053     | 0.6053     | 0.6053     |
| KU-HIAI-ONTHEIT-large-v1              | 0.7105     | 0.7105     | 0.7105     | 0.7105     | 0.7105     | 0.7105     |
| **KU-HIAI-ONTHEIT-large-v1.1**        | **0.7193** | **0.7193** | **0.7193** | **0.7193** | **0.7193** | **0.7193** |
| kf-deberta-multitask                  | 0.4561     | 0.4561     | 0.4561     | 0.4561     | 0.4561     | 0.4561     |
| gte-multilingual-base                 | 0.5877     | 0.5877     | 0.5877     | 0.5877     | 0.5877     | 0.5877     |

### Top-k 3

| Model name                            | F1         | Recall     | Precision  | mAP        | mRR        | NDCG       |
|---------------------------------------|------------|------------|------------|------------|------------|------------|
| paraphrase-multilingual-mpnet-base-v2 | 0.2368     | 0.4737     | 0.1579     | 0.2032     | 0.2032     | 0.2712     |
| KoSimCSE-roberta                      | 0.3026     | 0.6053     | 0.2018     | 0.2661     | 0.2661     | 0.3515     |
| Cohere embed-multilingual-v3.0        | 0.2851     | 0.5702     | 0.1901     | 0.2515     | 0.2515     | 0.3321     |
| openai ada 002                        | 0.3553     | 0.7105     | 0.2368     | 0.3202     | 0.3202     | 0.4186     |
| multilingual-e5-large-instruct        | 0.3333     | 0.6667     | 0.2222     | 0.2909     | 0.2909     | 0.3856     |
| Upstage Embedding                     | 0.4211     | 0.8421     | 0.2807     | **0.3509** | **0.3509** | 0.4743     |
| paraphrase-multilingual-MiniLM-L12-v2 | 0.2061     | 0.4123     | 0.1374     | 0.1740     | 0.1740     | 0.2340     |
| openai_embed_3_small                  | 0.3640     | 0.7281     | 0.2427     | 0.3026     | 0.3026     | 0.4097     |
| ko-sroberta-multitask                 | 0.2939     | 0.5877     | 0.1959     | 0.2500     | 0.2500     | 0.3351     |
| openai_embed_3_large                  | 0.3947     | 0.7895     | 0.2632     | 0.3348     | 0.3348     | 0.4491     |
| KU-HIAI-ONTHEIT-large-v1              | 0.4386     | 0.8772     | 0.2924     | 0.3421     | 0.3421     | 0.4766     |
| KU-HIAI-ONTHEIT-large-v1.1            | **0.4430** | **0.8860** | **0.2953** | 0.3406     | 0.3406     | **0.4778** |
| kf-deberta-multitask                  | 0.3158     | 0.6316     | 0.2105     | 0.2792     | 0.2792     | 0.3679     |
| gte-multilingual-base                 | 0.4035     | 0.8070     | 0.2690     | 0.3450     | 0.3450     | 0.4614     |

### Top-k 5

| Model name                            | F1         | Recall     | Precision  | mAP        | mRR        | NDCG       |
|---------------------------------------|------------|------------|------------|------------|------------|------------|
| paraphrase-multilingual-mpnet-base-v2 | 0.1813     | 0.5439     | 0.1088     | 0.1575     | 0.1575     | 0.2491     |
| KoSimCSE-roberta                      | 0.2164     | 0.6491     | 0.1298     | 0.1751     | 0.1751     | 0.2873     |
| Cohere embed-multilingual-v3.0        | 0.2076     | 0.6228     | 0.1246     | 0.1640     | 0.1640     | 0.2731     |
| openai ada 002                        | 0.2602     | 0.7807     | 0.1561     | 0.2139     | 0.2139     | 0.3486     |
| multilingual-e5-large-instruct        | 0.2544     | 0.7632     | 0.1526     | 0.2194     | 0.2194     | 0.3487     |
| Upstage Embedding                     | 0.2982     | 0.8947     | 0.1789     | **0.2237** | **0.2237** | 0.3822     |
| paraphrase-multilingual-MiniLM-L12-v2 | 0.1637     | 0.4912     | 0.0982     | 0.1437     | 0.1437     | 0.2264     |
| openai_embed_3_small                  | 0.2690     | 0.8070     | 0.1614     | 0.2148     | 0.2148     | 0.3553     |
| ko-sroberta-multitask                 | 0.2164     | 0.6491     | 0.1298     | 0.1697     | 0.1697     | 0.2835     |
| openai_embed_3_large                  | 0.2807     | 0.8421     | 0.1684     | 0.2088     | 0.2088     | 0.3586     |
| KU-HIAI-ONTHEIT-large-v1              | 0.3041     | 0.9123     | 0.1825     | 0.2137     | 0.2137     | 0.3783     |
| KU-HIAI-ONTHEIT-large-v1.1            | **0.3099** | **0.9298** | **0.1860** | 0.2148     | 0.2148     | **0.3834** |
| kf-deberta-multitask                  | 0.2281     | 0.6842     | 0.1368     | 0.1724     | 0.1724     | 0.2939     |
| gte-multilingual-base                 | 0.2865     | 0.8596     | 0.1719     | 0.2096     | 0.2096     | 0.3637     |

### Top-k 10

| Model name                            | F1         | Recall     | Precision  | mAP        | mRR        | NDCG       |
|---------------------------------------|------------|------------|------------|------------|------------|------------|
| paraphrase-multilingual-mpnet-base-v2 | 0.1212     | 0.6667     | 0.0667     | **0.1197** | **0.1197** | 0.2382     |
| KoSimCSE-roberta                      | 0.1324     | 0.7281     | 0.0728     | 0.1080     | 0.1080     | 0.2411     |
| Cohere embed-multilingual-v3.0        | 0.1324     | 0.7281     | 0.0728     | 0.1150     | 0.1150     | 0.2473     |
| openai ada 002                        | 0.1563     | 0.8596     | 0.0860     | 0.1051     | 0.1051     | 0.2673     |
| multilingual-e5-large-instruct        | 0.1483     | 0.8158     | 0.0816     | 0.0980     | 0.0980     | 0.2520     |
| Upstage Embedding                     | 0.1707     | 0.9386     | 0.0939     | 0.1078     | 0.1078     | 0.2848     |
| paraphrase-multilingual-MiniLM-L12-v2 | 0.1053     | 0.5789     | 0.0579     | 0.0961     | 0.0961     | 0.2006     |
| openai_embed_3_small                  | 0.1547     | 0.8509     | 0.0851     | 0.0984     | 0.0984     | 0.2593     |
| ko-sroberta-multitask                 | 0.1276     | 0.7018     | 0.0702     | 0.0986     | 0.0986     | 0.2275     |
| openai_embed_3_large                  | 0.1643     | 0.9035     | 0.0904     | 0.1180     | 0.1180     | 0.2855     |
| KU-HIAI-ONTHEIT-large-v1              | 0.1707     | 0.9386     | 0.0939     | 0.1105     | 0.1105     | **0.2860** |
| KU-HIAI-ONTHEIT-large-v1.1            | **0.1722** | **0.9474** | **0.0947** | 0.1033     | 0.1033     | 0.2822     |
| kf-deberta-multitask                  | 0.1388     | 0.7632     | 0.0763     | 0.1        | 0.1        | 0.2422     |
| gte-multilingual-base                 | 0.1675     | 0.9211     | 0.0921     | 0.1066     | 0.1066     | 0.2805     |

### Top-k 50

| Model name                            | F1         | Recall     | Precision  | mAP        | mRR        | NDCG       |
|---------------------------------------|------------|------------|------------|------------|------------|------------|
| paraphrase-multilingual-mpnet-base-v2 | 0.0320     | 0.8158     | 0.0163     | 0.0233     | 0.0233     | 0.1529     |
| KoSimCSE-roberta                      | 0.0368     | 0.9386     | 0.0188     | 0.0270     | 0.0270     | 0.1758     |
| Cohere embed-multilingual-v3.0        | 0.0382     | 0.9737     | 0.0195     | 0.0220     | 0.0220     | 0.1763     |
| openai ada 002                        | 0.0375     | 0.9561     | 0.0191     | **0.0295** | **0.0295** | 0.1789     |
| multilingual-e5-large-instruct        | 0.0378     | 0.9649     | 0.0193     | **0.0295** | **0.0295** | **0.1804** |
| Upstage Embedding                     | **0.0392** | **1.0000** | **0.0200** | 0.0206     | 0.0206     | 0.1776     |
| paraphrase-multilingual-MiniLM-L12-v2 | 0.0313     | 0.7982     | 0.0160     | 0.0218     | 0.0218     | 0.1503     |
| openai_embed_3_small                  | 0.0382     | 0.9737     | 0.0195     | 0.0202     | 0.0202     | 0.1731     |
| ko-sroberta-multitask                 | 0.0354     | 0.9035     | 0.0181     | 0.0245     | 0.0245     | 0.1691     |
| openai_embed_3_large                  | 0.0382     | 0.9737     | 0.0195     | 0.0210     | 0.0210     | 0.1741     |
| KU-HIAI-ONTHEIT-large-v1              | 0.0385     | 0.9825     | 0.0196     | 0.0212     | 0.0212     | 0.1758     |
| KU-HIAI-ONTHEIT-large-v1.1            | 0.0385     | 0.9825     | 0.0196     | 0.0206     | 0.0206     | 0.1750     |
| kf-deberta-multitask                  | 0.0351     | 0.8947     | 0.0179     | 0.0228     | 0.0228     | 0.1654     |
| gte-multilingual-base                 | **0.0392** | **1.0000** | **0.0200** | 0.0259     | 0.0259     | **0.1834** |

# Installation

```bash
pip install -r requirements.txt
```

# Running the project

1. Make `.env` file using `.env.template` file. You have to prepare three api keys, openai, cohere, and upstage.
2. Run evaluator with the following command.

```bash
python main.py --project_dir ./project_dir
```

3. Check the result in the project_dir folder.
