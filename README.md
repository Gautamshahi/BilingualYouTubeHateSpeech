# Hate Speech Detection Using Cross-Platform Social Media Data in English and German Language

This GitHub repository corresponds to our research article titled **Hate Speech Detection Using Cross-Platform Social Media Data in English and German Language**.

Hate speech has grown into a pervasive phenomenon, intensifying during times of crisis, elections, and social unrest. Multiple approaches have been developed to detect hate speech using artificial intelligence, however, a generalized model is yet unaccomplished. The challenge for hate speech detection as text classification is the cost of obtaining high-quality training data. This study focuses on detecting bilingual hate speech in YouTube comments and measuring the impact of using additional data from other platforms in the performance of the classification model. We examine the value of additional training datasets from cross-platforms for improving the performance of classification models. We also included factors such as content similarity, definition similarity, and common hate words to measure the impact of datasets on performance. Our findings show that adding more similar datasets based on content similarity, hate words, and definitions improves the performance of classification models. The best performance was obtained by combining datasets from YouTube comments, Twitter, and Gab with an F1-score of 0.74 and 0.68 for English and German YouTube comments.

## Data 
We have collected the data from existing resources and self-developed a Python program from YouTube. Due to [YouTube Data Sharing Policy](https://www.youtube.com/howyoutubeworks/our-commitments/protecting-user-data/), we are not allowed to share the full video information and comments, but it can be shared based on mutual agreement for research purposes. The data folder contains two files for fake and real videos in the following format.
**videoID** - unique ID of a YouTube video

#### How do I cite this work?

Please cite the [(WEBIST 2024 Paper)](https://www.scitepress.org/Papers/2024/130700/130700.pdf):
```
@InProceedings{shahiecir2024,
author="Shahi, Gautam Kishore and Jaiswal, Amit Kumar and Mandl, Thomas",
title="FakeClaim: A Multiple Platform-Driven Dataset for Identification of Fake News on 2023 Israel-Hamas War",
booktitle="Advances in Information Retrieval",
year="2024",
publisher="Springer Nature Switzerland",
address="Cham",
pages="66--74"
}
```
## Contact information
For help or issues using data, please submit a GitHub issue.

For personal communication related to our work, please contact Gautam Kishore Shahi(`gautamshahi16@gmail.com`)
## More update
For more updates on the related publication on the topic of FakeCovid, please visit [WarClaim: 2023-Israel-Hamas-war Dataset](https://github.com/Gautamshahi/WarClaim/) 
