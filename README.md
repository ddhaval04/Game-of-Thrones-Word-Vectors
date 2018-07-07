# Game of Thrones Word Vectors

![Search](https://github.com/ddhaval04/Game-of-Thrones-Word-Vectors/raw/master/images/got-header.jpg)

This repository consists code for creating word vectors from the first 3 Game of Thrones book and explore the semantic properties of its words.


## Overview

This notebook contains implementation of the word vectors created from the books. I have attempted to visualize the vectors into 2D space using t-SNE. Also, I have explored semantic properties like identifying the most similar word.

Example:

Input word: `Stark`
Output:
```
[('Eddard', 0.7075438499450684),
 ('Lyanna', 0.7025941610336304),
 ('Benjen', 0.6847219467163086),
 ('Winterfell', 0.6610473394393921),
 ('Hornwood', 0.6568844318389893),
 ('Tully', 0.6521530151367188),
 ('Roslin', 0.6456855535507202),
 ('Brandon', 0.645483672618866),
 ('Bael', 0.643380880355835),
 ('Robb', 0.6422325372695923)]
 ```
Input word: `Aerys`
Output:
```
[('Rhaegar', 0.8321652412414551),
 ('Targaryen', 0.830471396446228),
 ('knighted', 0.8012657165527344),
 ('Robert', 0.7990405559539795),
 ('Dome', 0.7933883666992188),
 ('Bael', 0.7919018268585205),
 ('Jaehaerys', 0.7889218330383301),
 ('Usurper', 0.7887647151947021),
 ('Daeron', 0.7878808975219727),
 ('reign', 0.786959171295166)]
```
## Data:

This notebook uses first 3 books of the Game of Thrones series to create word vectors.



## Dependencies (pip install)

```
numpy
pandas
matplotlib
gensim
nltk
sklearn
```

## Credits:

[Siraj Raval](https://twitter.com/sirajraval?ref_src=twsrc%5Egoogle%7Ctwcamp%5Eserp%7Ctwgr%5Eauthor)