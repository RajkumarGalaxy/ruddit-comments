# ruddit-comments
Ruddit Comments extracted from Reddit using Python Web Scraper PRAW

# Original Work
**Ruddit: Norms of Offensiveness for English Reddit Comments** is a dataset of English language Reddit comments that has fine-grained, real-valued scores between -1 (maximally supportive) and 1 (maximally offensive). Data sampling procedure, annotation, and analysis have been discussed in detail in the accompanying paper. Authors have provided the comment IDs, post IDs and not the bodies, in accordance to the GDPR regulations. They have suggested that the comments and post bodies can be extracted from any Reddit API using the IDs provided.

The original paper can be found here: [Ruddit: Norms of Offensiveness for English Reddit Comments](https://aclanthology.org/2021.acl-long.210/)

The source github repo can be found here: [https://github.com/hadarishav/Ruddit](https://github.com/hadarishav/Ruddit)

Acknowledgement to Original work:

`@inproceedings{hada-etal-2021-ruddit,
    title = "Ruddit: {N}orms of Offensiveness for {E}nglish {R}eddit Comments",
    author = "Hada, Rishav  and
      Sudhir, Sohi  and
      Mishra, Pushkar  and
      Yannakoudakis, Helen  and
      Mohammad, Saif M.  and
      Shutova, Ekaterina",
    booktitle = "Proceedings of the 59th Annual Meeting of the Association for Computational Linguistics and the 11th International Joint Conference on Natural Language Processing (Volume 1: Long Papers)",
    month = aug,
    year = "2021",
    address = "Online",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2021.acl-long.210",
    doi = "10.18653/v1/2021.acl-long.210",
    pages = "2700--2717",
    abstract = "On social media platforms, hateful and offensive language negatively impact the mental well-being of users and the participation of people from diverse backgrounds. Automatic methods to detect offensive language have largely relied on datasets with categorical labels. However, comments can vary in their degree of offensiveness. We create the first dataset of English language Reddit comments that has fine-grained, real-valued scores between -1 (maximally supportive) and 1 (maximally offensive). The dataset was annotated using Best{--}Worst Scaling, a form of comparative annotation that has been shown to alleviate known biases of using rating scales. We show that the method produces highly reliable offensiveness scores. Finally, we evaluate the ability of widely-used neural models to predict offensiveness scores on this new dataset.",
}`

# Comment Extraction
I have used **PRAW**, a python library to communicate with **Reddit API** to extract the comment texts using given comment ids and post ids.
