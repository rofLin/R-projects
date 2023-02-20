In this project, I used a web crawler to extract topics, textual content, and other features from a public opinion website. My aim was to investigate how the comment count and emotional language impact the final support count after a period of 3 months.

I found a linear correlation between both positive and negative comment counts and the final support count. It is reasonable to assume that popularity drives these factors, which are influenced by how many people are interested in the topic.

I attempted to measure emotional language using various methods, and use it to predict whether articles would receive enough support to cross the threshold. However, the results were unsatisfactory. On the other hand, the popularity of the article (i.e. agree or disagree count) on the first day proved to be a better predictor.

I also attempted to classify the articles into different fields based on the textual content. Through text clustering and word clouds, we gained insight into the most popular topics on the website.

I further attempted to use PCA to classify topics into broader fields, hoping to identify those that were more likely to receive support. However, the results were not significant, and the only conclusion I could draw was that PC4 was related to traffic issues.

