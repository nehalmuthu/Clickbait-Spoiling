# Clickbait-Spoiling


### Semeval 2023 : [link](https://pan.webis.de/semeval23/pan23-web/clickbait-challenge.html).


### Implementation of the Research Work: [paper](https://aclanthology.org/2022.acl-long.484.pdf)

- We have implemented the Sota Q&A models. 
- Our Novel Input - tackling the multi-part click-baits using summarization models.


## Models 
#### Our fintuned models can be found under the following links  
### Q&A:
- BERT: [model](https://drive.google.com/file/d/1BA4DpqpJtgJZPNkw5_w0__uPuyjZV5gQ/view?usp=share_link)
- RoBERTa: [model](https://drive.google.com/file/d/1RDMBrVld4909DyM0Cs8gcazjUAfPZCFF/view?usp=share_link)
- DeBERTa: [model](https://drive.google.com/file/d/1xJK-r6Z7Zubm1o8CCkFUKan3U-Q1CVkt/view?usp=share_link)

### Summarization:
- BART
- Promt Engineering with GPT


# Run the Code

## For Q&A models
#### For each Model we have a Train file and a Test file. All the Notebooks are well documented, so it can be followed from there.
#### TRAIN Files:
To train and finetune the model from scratch, use the Train file.
#### TEST Files:
To just predict and get the results using our finetuned model use the Test file.

## For Summarization Models
#### All the Notebooks are well documented, so it can be followed from there.



### Running Environment: 
Colab - GPU



## Results

#### Q&A Models - Phrase type Clickbaits
| Models | BLEU | METEOR|
| --- | --- | --- |
| BERT (baseline) |  58.25 | 55.24 |
| RoBERTa | 63.92 | 65.40 |
| DeBERTa | 65.43 | 66.04 |


#### Summarization Models - Multi-part type Clickbaits
| Models | BLEU | METEOR|
| --- | --- | --- |
| Promt-GPT | 63.38 | 57.53 |
| BART | -- | -- |







