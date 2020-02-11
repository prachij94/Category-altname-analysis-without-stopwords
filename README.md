# Attribute extraction by removing Stopwords from alternate mcat name

The main aim of this activity is to get a string for each microcategory which may directly affect the alternate name it currently has and may lead to vague mapping. This string does not have any stopwords and is called attribute for that mcat id.

An input file contains the stopwords for each of the subcategory id's and this is merged with their mcats using other data files. Once the huge merged data has the columns 'MCAT_ID','MCAT_Name','Alt_Name','Subcat_ID','Stopword','Attribute', the 'Attribute' columns is populated by removing the stopwords from the alt mcat name and returned as it is if no matching stopword is found.

## Usage:
```
python altnameStopwords.py
```
