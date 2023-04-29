# Automatic-Poem-Generator

#### Authors: Atul Krishnan, Gayatri Praharshita Prabhala, Harsh Hardikar

The Automatic Poem Generator is a NLP based project that can create poems based on a query given by a user.
There are 6 different models that are trained for 6 different topics. 
The framework chunks the input and assigns POS tags from which we find 'Key Words'.
These Keywords are used to analyze what category the poem should fall under using WordNet similarity.
We then use WordNet to find words similar to the seed words that form the key aspect of the generation. 
The better the Seed Words, the better the poem. 
We generate 4 lines of poem with each line consisting of 6 words. 

## Getting Started
1. Three notebooks are provided in this repository.
2. The Data Processing notebook takes a publicly available dataset, Poems Dataset (NLP) and processes it into multiple datasets based on categories. (This step can be skipped as the datasets are available in this repo and on Kaggle)
3. The Model Training notebook was used to train 6 different models for each topic. We ran it for around 50 epochs each, which took us between 1-3 hours. The models links are available in this repository.
4. The Final Model is where everything comes together. All the below mentioned datasets and models must be added as input data. The notebook can be run. When prompted, enter the kind of poem expected. Within a few mins, a poem will be generated for you!

Original Dataset Link: https://www.kaggle.com/datasets/michaelarman/poemsdataset

<b>Links of Datasets to be used in this project:</b>

1. Emotions Datset: https://www.kaggle.com/datasets/atulkrishnan25/emotions
2. Virtues Dataset: https://www.kaggle.com/datasets/atulkrishnan25/virtues
3. Fantasy and Nature Dataset: https://www.kaggle.com/datasets/harshhardikar/nature
4. Seasons Dataset: https://www.kaggle.com/datasets/gayatriprabhala/seasons
5. Other Topics Dataset: https://www.kaggle.com/datasets/gayatriprabhala/othertopics

<b>Models used in the Dataset</b>

1. Emotions Model: https://www.kaggle.com/datasets/atulkrishnan25/emotions-model
2. Virtues Model: https://www.kaggle.com/datasets/atulkrishnan25/virtues-model
3. Nature Model: https://www.kaggle.com/datasets/harshhardikar/nature-model
4. Fantasy Model: https://www.kaggle.com/datasets/harshhardikar/fantasy-model
5. Seasons Model: https://www.kaggle.com/datasets/gayatriprabhala/seasons-nlp
6. Other Topics Model: https://www.kaggle.com/datasets/gayatriprabhala/othertopics-model

## Hope this poem generator generates a lot of fun!
