# WikiEvent

## Data Format
The WikiEvent contains train(30,000), dev(2,000) and test set(2,000). The entity chain and retrieved text are all in * .src while the target text are put into * .tgt. 
In src, the format is "entity_1 ENTITYSEP entity_2 ... entity_n WIKISEP sentence1 SENTSEP sentence2 ... sentence_n-1".
