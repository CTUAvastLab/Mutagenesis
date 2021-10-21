# Datasets

This repository contains various datasets used in CTUAvastLab. 
Currently it contains only mutagenesis dataset.

## Mutagenesis dataset:

### Summary
The dataset comprises of 230 molecules trialed for mutagenicity on Salmonella typhimurium. A subset of 188 molecules
 is learnable using linear regression. This subset was later termed the ”regression friendly” dataset. The remaining
 subset of 42 molecules is named the ”regression unfriendly” dataset. 
(taken from [relational.fit.cvut.cz/](https://relational.fit.cvut.cz/dataset/Mutagenesis)).

Currently, this repository contains only `Mutagenesis_188`.

### Website
[relational.fit.cvut.cz/](https://relational.fit.cvut.cz/dataset/Mutagenesis) where the original data is hosted as 
SQL database.
[Original source](http://www.cs.ox.ac.uk/activities/machlearn/mutagenesis.html) 

### [License](LICENSE)

see separate file.

### Data structure

[mutagenesis/data.json](mutagenesis/data.json) contains data from dataset Mutagenesis_188, as list of 188 strucures, 
each representing one molecule, as a json.

[mutagenesis/meta.json](mutagenesis/meta.json) contains metadata about the dataset, as a json.
