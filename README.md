# OneDirectionTracks
Assigment2 | Collecting Data | Digital Humanities RUG

## One Direction Songs Corpus
The corpus contains lyrics from One Direction's first two albums; "Up All Night" and "Take Me Home".

This corpus is intended for scholars or enthusiasts interested in analysing One Direction's early lyrics. It can be used, for example, for sentiment analysis. One Direction Sentiment file is an example of the usage of this corpus. The study was made with pandas and nltk.

The two albums are originally only in English, and I have decided to solely use the first two albums even though they have five albums in total. I was interested in using the corpus to analyse how the lyrics helped One Direction skyrocket their fame particularly if their notably positive lyrics played a role in making them globally popular.

### Hypothesis:
Did the lyrics from One Direction's first two albums help them become globally famous? 

## Data Collection Process
Lyrics were collected from this website: https://www.onedirectionmusic.com/gb/home.html
The website mentioned is the original website and it is where I scrapped all the data.
The lyrics are organized in folders corresponding to their albums. They are saved as text files.
All the lyrics are analysed in a CSV file

## CSV File Structure
The CSV file contains:
1. filename: which corresponds with the name of the .txt file
2. title: name of the song
3. artist: One Direction
4. album: either "Take Me Home" or "Up All Night"
5. document: full lyrics text
6. tokens: tokenized words from the lyrics
7. lemmas: lemmatized form of each token
8. tags: part-of-speech tags for each token

## Annotations and Tools
Tokenization, lemmatization and part-of-speech tagging were performed using SpaCy.



