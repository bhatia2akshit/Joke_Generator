# Joke Maker using Mistral

## The notebook key_pharse_extraction:
### A pretrained Mistral 7b Instruct v0.2 model is used to extract list of topics from each dad joke
### Mistral is finetuned on the set of topics and the target joke using Autotrain


# Joke Maker using GPT2
## The notebook fine_tune_joke_maker:
### the same procedure as above

## At the moment, GPT2 was trained on only 2000 data elements, and Mistral is trained on 18000 elements. Definitely Mistral is performing better.
### I will update GPT2 on the same data and then will determine which is good

### To Do: make an evaluation function to find out which joke is good
