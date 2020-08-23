* AggregatedNewsRE Dataset *

- Description:
It is a Relation Extraction dataset with data from 11 clusters of articles.
It is composed by a total of 400 candidate facts, manually annotated with 18 relational categories (including no-relation category).

- Files:
  * AggregatedNewsRE_statistics.txt
  * AggregatedNewsRE_dataset.txt
  * AggregatedNewsRE_rel2id.json

- Data Format:
Relation Extraction datasets store tokenized sentences (token) with annotated pairs of entities (t, h) and the relation between them (relation). We store the sentence
For each entity we have its position in the text (pos), its Freebase identifier (id), its the entity type (type), the surface form of the entity in the text (name).

"""
{'relation': 'administrativearea_HeadOfGovernment',
 'h': {'name': 'Venezuela',
       'type': 'Location',
       'pos': [11, 12],
       'id': '/m/07ylj'},
 't': {'name': 'Nicolás Maduro',
       'type': 'Person',
       'pos': [14, 16],
       'id': '/m/0h7hb4'},
'token': ['The', 'US', 'Department', 'of', 'Justice', 'announced', 'Thursday', 'that', 'it', 'has', 'indicted', 'Venezuela', "'s", 'president', 'Nicolás', 'Maduro', 'and', 'several', 'key', 'aides', 'on', 'charges', 'of', 'narcoterrorism'],
'sentence': "The US Department of Justice announced Thursday that it has indicted Venezuela's president Nicolás Maduro and several key aides on charges of narcoterrorism",
'story_id': 241858}
"""
