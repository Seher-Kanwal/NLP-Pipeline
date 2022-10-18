![head](https://nlpforhackers.io/wp-content/uploads/2018/03/spaCy.png)
# NLP-Pipeline
NLP Pipeline is a set of steps followed to build an end to end NLP software. In pipeline, we make a set of functions, the output of the first functions act as an imput for the other functions.

## Here I'm discussing the spaCy NLP pipeline:

When you call nlp on a text, spaCy first tokenizes the text to produce a Doc object. The Doc is then processed in several different steps – this is also referred to as the processing pipeline. The pipeline used by the trained pipelines typically include a tagger, a lemmatizer, a parser and an entity recognizer. Each pipeline component returns the processed Doc, which is then passed on to the next component.
<img src = "https://spacy.io/pipeline-fde48da9b43661abcdf62ab70a546d71.svg">

There are different components in the spaCy pipeline. Some are given below:
- # Tokenization:
Tokenization is a simple process that takes raw data and converts it into a useful data string. While tokenization is well known for its use in cybersecurity and in the creation of NFTs, tokenization is also an important part of the NLP process. Tokenization is used in natural language processing to split paragraphs and sentences into smaller units that can be more easily assigned meaning.   

The first step of the NLP process is gathering the data (a sentence) and breaking it into understandable parts (words). Here’s an example of a string of data:  

“What restaurants are nearby?“

In order for this sentence to be understood by a machine, tokenization is performed on the string to break it into individual parts. With tokenization, we’d get something like this:  

‘what’ ‘restaurants’ ‘are’ ‘nearby’  

- # Tagger:
 A trainable pipeline component to predict part-of-speech tags for any part-of-speech tag set.
Spacy provides a bunch of POS tags such as NOUN (noun), PUNCT (punctuation), ADJ(adjective), ADV(adverb), etc. It has a trained pipeline and statistical models which enable spaCy to make classification of which tag or label a token belongs to. For example, a word following “the” in English is most likely a noun.

- # Named Entity Recognition (NER):
Entities are the most important chunks of a particular sentence such as noun phrases, verb phrases, or both. Named Entity Recognition NER works by locating and identifying the named entities present in unstructured text into the standard categories such as person names, locations, organizations, time expressions, quantities, monetary values, percentage, codes etc. Spacy comes with an extremely fast statistical entity recognition system that assigns labels to contiguous spans of tokens.

<img src = "https://confusedcoders.com/wp-content/uploads/2019/11/image2.png">
Spacy has the ‘ner’ pipeline component that identifies token spans fitting a predetermined set of named entities. These are available as the ‘ents’ property of a Doc object.
