![head](https://nlpforhackers.io/wp-content/uploads/2018/03/spaCy.png)
# NLP-Pipeline
NLP Pipeline is a set of steps followed to build an end to end NLP software. In pipeline, we make a set of functions, the output of the first functions act as an imput for the other functions.

## Here I'm discussing the spaCy NLP pipeline:

When you call nlp on a text, spaCy first tokenizes the text to produce a Doc object. The Doc is then processed in several different steps – this is also referred to as the processing pipeline. The pipeline used by the trained pipelines typically include a tagger, a lemmatizer, a parser and an entity recognizer. Each pipeline component returns the processed Doc, which is then passed on to the next component.
<img src = "https://spacy.io/pipeline-fde48da9b43661abcdf62ab70a546d71.svg">

