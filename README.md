# Semantic-Graphs

This repository provides the codes and dataframes related to our paper entitled **"Who does What to Whom? Graph Representations of Action-Predication in Speech Relate to Psychopathological Dimensions of Psychosis"**. 
In this paper we have used Semantic Role Labeling (SRL) to produce graphical representations of speech based on the two universal relations of action (i.e. what entities act upon each other) and predication (i.e. what activities are performed). 
The codes are part of language processing pipeling developed at Tang Lab, Feinstein Institutes for Medical Research, to process clinical speech samples.

## Codes

The codes are available in the following documents:

For semantic role labeling please refer to: **6_semantic_role_labeling.ipynb**

For graph formation please refer to: **7_graph_formation.ipynb**

We have used [transformer-srl](https://github.com/Riccorl/transformer-srl/) repository to perform SRL. More details on installing and using the model is available in the original repository provided by [Riccardo Orlando](https://github.com/Riccorl).

## DataFrames

You can use a publicly available dataframe, **filtered_words_youtube.csv**, and run it through above-mentioned pieces of our pipeline.

Graph features and clinical data used in our paper are also available in two csv files for *Picture Description* and *Open-ended Narrative* tasks.
