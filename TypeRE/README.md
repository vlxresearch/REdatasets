# TypeRE Dataset

## Description:
TypeRE is a supervised large-scale relation extraction dataset made from aligning public relation extraction datasets relations into a unified ontology.
The public datasets used are: Wiki80, KBP37 and KnowledgeNet.
The dataset includes a total of 30923 sentences annotated with 28 relational categories (including the no-relation category).

## Files:
  * typere_train.txt
  * typere_test.txt
  * typere_dev.txt
  * typere_statistics.json
  * typre_rel2id.json


## Data Format:
TypeRE dataset stores tokenized sentences (token) with annotated pairs of entities (t, h) and the relation between them (relation).
For each entity we store its position in the text (pos), its Freebase identifier (id), the entity type (type), the surface form of the entity in the text (name). We also store the origin public dataset for each sentence (origin_dataset).

```
{'relation': 'person_Parent',
 'h': {'id': '/m/015b_v',
       'name': 'Karl Wilhelm von Feuerbach',
       'pos': [0, 4], 
       'type': 'Person'},
 't': {'id': '/m/064dr',
       'name': 'Paul Johann Anselm Ritter von Feuerbach',
       'pos': [23, 29], 
       'type': 'Person'},
'token': ['Karl', 'Wilhelm', 'von', 'Feuerbach', '(', '30', 'May', '1800', '–', '12', 'March', '1834', ')', 'was', 'a', 'German', 'geometer', 'and', 'the', 'son', 'of', 'legal', 'scholar', 'Paul', 'Johann', 'Anselm', 'Ritter', 'von', 'Feuerbach', ',', 'and', 'the', 'brother', 'of', 'philosopher', 'Ludwig', 'Feuerbach', '.'],
'origin_dataset': 'KnowledgeNet'}
```

## License
[MIT](https://choosealicense.com/licenses/mit/)
