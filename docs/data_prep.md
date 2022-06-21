# Data preparation stage

- Convert my data intow train and test in 70:30 ration
```
data.xml
    |-train.tsv
    |test.tsv

```
- We selecting three tags from the xml data 
1. row id
2. title and body 
3. tags (stackoverflow tags)


|Tags|feature names|
|-|-|
|row Id| row ID|
|title and body |text|
|stackoverflow tags |Label -python| 