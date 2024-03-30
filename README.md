# Learning_Labs-5-Sentiment-Analysis-using-R/ Natural Language Processing
## Sentiment Analysis using R, of the US presidential debate 2016

### What is Sentiment Analysis?

It is the process of analyzing pieces of text from PDFs, webpages, social media posts, etc. to understand the kinds of emotions being expressed. Millions of texts are being sent every day on tonnes of subjects, and it would be impossible to extract actionable insights from this data simply by reading each text, each Facebook post, and each tweet.
![image](https://github.com/LangatErick/Learning_Labs-5-Sentiment-Analysis-using-R/assets/124883947/1f280284-cbff-473c-ab93-64a8ae0e8b1c)

Sentiment Analysis provides an easy way of extracting actionable insights through algorithms developed for programming Languages. For Python check out some of the packages designed for sentiment analysis here. For R users some - packages include;
- tidyr
- tm
- sentiment analysis
- tidytext
- quanteda
For this Analysis, I will use the tidytext package because of its easy implementation alongside the tidyverse package. Find the data used here and as well the R script

![image](https://github.com/LangatErick/Learning_Labs-5-Sentiment-Analysis-using-R/assets/124883947/242f18f0-b687-4fd9-8fab-d2e8d2473381)

From the plot above, *Trump* and *Clinton* more than anyone else have more word frequencies, so let us place a little more interest in them. Let's examine how sentiments vary throughout their speeches.

![image](https://github.com/LangatErick/Learning_Labs-5-Sentiment-Analysis-using-R/assets/124883947/01eb58c4-8411-406d-b365-67da3884918e)

It appears they both used quite several negative words in their speeches as compared to positive ones, so let's compare the speaker's use of both words.

![image](https://github.com/LangatErick/Learning_Labs-5-Sentiment-Analysis-using-R/assets/124883947/9ce76d67-1d05-400f-a52f-c8bdc4975871)

Finally, let us create a word cloud of these words, visualizing positive vs negative

![image](https://github.com/LangatErick/Learning_Labs-5-Sentiment-Analysis-using-R/assets/124883947/2112c4b5-b842-4f70-8cf4-a8d7aab0909c)
