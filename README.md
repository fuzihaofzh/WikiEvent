# WikiEvent
This is the dataset for the paper "Open Domain Event Text Generation"

## Data Format
The WikiEvent contains train(30,000), dev(2,000) and test set(2,000). The entity chain and retrieved text are all in * .src while the target text are put into * .tgt. 
In src, the format is "entity_1 ENTITYSEP entity_2 ... entity_n WIKISEP sentence1 SENTSEP sentence2 ... sentence_n-1".

## Reference

```
@inproceedings{fu2020open,
  title={Open Domain Event Text Generation},
  author={Fu, Zihao and Bing, Lidong and Lam, Wai},
  booktitle={Thirty-Fourth AAAI Conference on Artificial Intelligence},
  year={2020}
}
```
