# EmoWikipediaTalkPages Dataset

## Specifications table

|||
|------------------------------|-----------------------------------------------------------------------|
|Subject                       |Computer science (data science)                                        |
|Specific subject area         |Online discussions analysis                                            |
|Type of data                  |Text files                                                             |
|Description of data collection        |Annotations of discussions from [Conversations Gone Awry](https://github.com/CornellNLP/Cornell-Conversational-Analysis-Toolkit/blob/master/datasets/conversations-gone-awry-corpus/awry.README.v1.00.txt) dataset obtained with a survey filled in by the respondents with the use of Plutchik's model, extended with emotions scores calculated on the basis of [EmoWordNet](http://www.oma-project.com/ArSenL/EmoWordNet1.0.txt) lexicon             |
|Data format                   |JSON (table-oriented), CSV                                                              |
|Parameters for data collection|Total count of annotations (624), total count of annotated triplets (208), total count of distinct conversations (151), count of posts in conflict discussions (249), count of posts in non-conflict discussions (375), parameters for annotators' agreement: count of posts annotated unanimously (36), count of posts annotated with two different emotions (248), count of posts annotated with three different emotions (340)    |
|Description of dataset fields|**text** - content of the post, type: string                                             |
|                             |**conv_id** - id of the conversation from which the post is derived, type: string        |
|                             |**conv_title** - title of the conversation from which the post is derived, type: string  |
|                             |**conflict** - description whether the discussion from which the comment comes was conflict, i.e. contained at least one comment with personal attack, type: boolean|
|                             |**no.** - order number of the post in the conversation, type: integer                    |
|                             |**plutchik_emotion(1/2/3)** - three fields with emotions from the Plutchik's model the post was annotated with, each post was annotated by three respondents, type: string                                              |
|                             |**emowordnet_ * _score** - eight fields with scores of emotions (afraid, amused, angry, annoyed, happy, don't care, inspired, sad) calculated for the post basing on EmoWordNet lexicon, type: number                           |
|Data source location          |Faculty of Computing
|                              |Poznan University of Technology
|                              |ul. Piotrowo 3
|                              |60-965 Poznan, Poland
|Data accessibility            |Repository name: EmoWikipediaTalkPages                                                  |
|                              |Data identification number: <https://doi.org/10.5281/zenodo.3631670>                    |
|                              |Direct URL to data: <https://github.com/LAKE-PUT/EmoWikipediaTalkPages>                 |
|Related research article      |Maksymilian Marcinowski, Agnieszka Ławrynowicz, *On Emotions in Conflict Wikipedia Talk Pages Discussions*, submitted to ICWE2020 Conference                                                                          |
