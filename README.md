# early-modern-corpus

## Data Format
Each book can is a csv file located inside files folder. The name of the file for each book can be found in the **filenumber** column in the metadata available. Each row from a csv is a word available in an unprocessed (standard) form, lemmatized or as a syntactic tag.

## Authorship 
The authorship informationis described by the **author** column from the metadata. Multiple authors are separated with ; for example: 

`Fletcher, John; Ford, John; Massinger, Philip; Webster, John (?)` 

(?) indicates that the participation of the author in the play is not certain. Anonymous plays have `anon.` in the author column.

##### Obs: Sometimes lemmas and tags are not available because they were not present in the original XML from where the data was retrieved.
