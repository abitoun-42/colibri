# Colibrie
 [![image](https://img.shields.io/pypi/v/colibrie.svg)](https://pypi.org/project/colibrie/) [![image](https://img.shields.io/pypi/l/colibrie.svg)](https://pypi.org/project/colibrie/)

Colibrie is a blazing fast tool to extract tables from PDFs 

## Why Colibrie?

- :rocket: **Efficient**: Colibrie is faster by multiple order of magnitude than any solution existing in his category
- :sparkles: **Fidel visual**: Colibrie can provide 1:1 HTML representation of any tables it'll find
- :books: **Reliable**: Colibri will find every valid tables without exception if the PDF is compatible with the core principle of Colibrie
- :memo: **Output**: Each table can be export into to multiple formats, which include : 
  - Pandas Dataframe.
  - HTML.

## Installation

### using source
```
pip install poetry

git clone https://github.com/abitoun-42/colibrie.git

cd colibrie

poetry install
```
### using pip
```
pip install colibrie
```

## Usage
```
from colibrie.extract_tables import extract_table

tables = extract_table('pdf_path')
```
