# veld_data__apis_spacy_ner_models

This repo contains spacy NER models, trained on APIS ÖBL data and in this chain veld: 
https://github.com/veldhub/veld_chain__train_spacy_apis_ner

This data repo is hosted on github and our internal gitlab.

The public github repo ( https://github.com/veldhub/veld_data__apis_spacy_ner_models ) contains 
only metadata in the `main` branch, due to storage issues. The best performing models are published
on huggingface.

The internal gitlab repo ( https://gitlab.oeaw.ac.at/acdh-ch/nlp/veld_data_apis_spacy_ner_models )
additionally contains all models data in the branch `full_data`. In order to get to that data, add 
that remote with:
```
git remote add gitlab https://gitlab.oeaw.ac.at/acdh-ch/nlp/veld_data_apis_spacy_ner_models.git
```
and
```
git checkout gitlab/full_data
```

