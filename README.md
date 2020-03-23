# word_count
Functions that render the frequencies with which words occur in any text file 

## How to Use and Syntax
1. download the file wordcount.py in the same directory as your text file
2. open terminal and use command

```
python .\wordcount.py flag file_name
```

### Flags
Currently, one of the two flags may be used
` --count` 
` --topcount`
    

## `--count`
use of this flag prints each word that appears in the text file along with the number of times the word appears in the following format

> word1 count1
> word2 count2

### Features

1. words appear in alphabetically sorted order
2. all words are considered in their lowercase forms
>example: 'WE', 'We', 'we' and 'wE' will be considered as the same word and their frequencies will add up
3. punctuations will be considered as discrete words and will appear above letter containing words

## `-topcount`
use of this flag prints the top 20 most occuring words (or all the words- whichever is lower) in the text file in the following format

> word1 count1
> word2 count2

### Features

1. words will appear in the decreasing order of frequency
2. words with the same frequency will appear in alphabetically sorted order
3. if total number of distinct words in the file is less than 20, then all the words in the file will appear with their frequencies, in decreasing order of their frequency
4. All words are considered in their lowercase form (same as in --count flag)
5. punctuations will be considered as discrete words and will appear above letter containing words
