In this project, I use crawler to get topics, text contents, and other features from public opinion website.
I tried to explore how comments count and emotional words affect the final support count after 3 months.

I found that both positive and negative comment counts are linear correlated with final support count.
It is reasonable that these two factors are both driven by popularity. How many people care about the topics?

I tried manys way to measure emotional words, and tried to use them to predict whether the articles would get enough support counts to cross the threshold or not.
However, they did not work well.
On the other hands, the popularity (agree or disagree count) in the first day do a better job on it.

Also, I tried to classify these articles to different field through text contents.
With text clusturing and word cloud, we can take a glimpse of those different fields.
There are some most popular topics on the website.

I also tried to use PCA to classify topics to coarser fields, 
hope to find the issue which is easier to be supported.
But it does not work well, too. 
I can only interpret that PC4 is clearly about traffic issues.


