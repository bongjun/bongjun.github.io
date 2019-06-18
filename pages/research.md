---
layout: page
title: Research
description: Bongjun Kim's research
---



#### <u>Weakly Labeled Audio Event Classification</u>
*We describe a novel weakly labeled Audio Event Classification approach based on a self-supervised attention model. The weakly labeled framework is used to eliminate the need for expensive data labeling procedure and self-supervised attention is deployed to help a model distinguish between relevant and irrelevant parts of a weakly labeled audio clip in a more effective manner compared to prior attention models. We also propose a highly effective strongly supervised attention model when strong labels are available. This model also serves as an upper bound for the self-supervised model. The performances of the model with self-supervised attention training are comparable to the strongly supervised one which is trained using strong labels. We show that our self-supervised attention method is especially beneficial for short audio events.*

<br/>
<br/>

#### <u>Improving Content-based Audio Retrieval by Vocal Imitation Feedback</u>
*Content-based audio retrieval including query-by-example (QBE) and query-by-vocal imitation (QBV) is useful when search-relevant text labels for the audio are unavailable, or text labels do not sufficiently narrow the search. However, a single query example may not provide sufficient information to ensure the target sound(s) in the database are the most highly ranked. In this paper, we adapt an existing model for generating audio embeddings to create a state-of-the-art similarity measure for audio QBE and QBV. We then propose a new method to update search results when top-ranked items are not relevant: The user provides an additional vocal imitation to illustrate what they do or do not want in the search results. This imitation may either be of some portion of the initial query example, or of a top-ranked (but incorrect) search result. Results show that adding vocal imitation feedback improves initial retrieval results by a statistically significant amount.*

[Paper ![pdf]({{ BASE_PATH }}/pages/icons16/pdf-icon.png)]({{ BASE_PATH}}/pages/files/icassp19_Kim.pdf)

<br/>
<br/>

<!-- #### <u>Vocal Imitation Set: a dataset of vocally imitated sound events using the AudioSet ontology</u>
*Query-By-Vocal Imitation (QBV) search systems enable searching a collection of audio files using a vocal imitation as a query. This can be useful when sounds do not have commonly agreed-upon text-labels, or many sounds share a label. As deep learning approaches have been successfully applied to QBV systems, datasets to build models have become more important. We present Vocal Imitation Set, a new vocal imitation dataset containing 11, 242 crowd-sourced vocal imitations of 302 sound event classes in the AudioSet sound event ontology. It is the largest publicly-available dataset of vocal imitations as well as the first to adopt the widely-used AudioSet ontology for a vocal imitation dataset. Each imitation recording in Vocal Imitation Set was rated by a human listener on how similar the imitation is to the recording it was an imitation of. Vocal Imitation Set also has an average of 10 different original recordings per sound class. Since each sound class has about 19 listener-vetted imitations and 10 original sound files, the data set is suited for training models to do fine-grained vocal imitation-based search within sound classes. We provide an example of using the dataset to measure how well the existing state-of-the-art in QBV search performs on fine-grained search.*

[Paper ![pdf]({{ BASE_PATH }}/pages/icons16/pdf-icon.png)]({{ BASE_PATH}}/pages/publications/icassp19_Kim.pdf) -->

<!-- Note: this is how to write a comment in HTML. Everything in here won't show up on your webpage.-->

<!--
To increase the size of the title, use fewer # in front of the paper title.
To decrease the size of the title, use more #. 
To remove the italics, remove the * before and after the description
To remove the underline from the title, remove the <u> tags (<u> and </u>)
-->