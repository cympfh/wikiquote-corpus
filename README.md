# Wikiquote の最初の段落を抜き出して文区切りにしてPOSタグを附ける

Wikipedia よりも短い文章なので

## Wikiquote list

`urls`

## requires

- JVM
- stanford-corenlp: `CORENLP=/share/tools/stanford-corenlp-full-2013-11-12/stanford-corenlp-3.3.0.jar`
- stanford-posttagger: `POSTTAGGER=~/Tools/stanford-postagger-full-2014-01-04/stanford-postagger.jar`

## usage

```
./run
```

`wikiquote` file should be output.

- 1line=1sentence
- WORDs split by space
- WORD is a pair of English word and its POS tag
    - like `He_PRP won_VBD the_DT Nobel_NNP Prize_NNP`

