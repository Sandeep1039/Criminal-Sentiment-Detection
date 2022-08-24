# Criminal-Sentiment-Detection
The aim of the project is to predict early signs of criminal sentiments through social media text mining.

Social media sentiment analysis is the process of interpreting and determining whether the social media collected text data is positive, negative, or neutral. It goes beyond just collecting and counting the number of mentions, comments, or hashtags. Analyzing sentiment gives you deeper insight into the attitudes, opinions, and emotions behind the text. Social media data also have curse of dimension problem i.e. high dimension nature of data that required specific pre-processing and feature extraction, which leads to improve classification accuracy.

### ALGORITHMS USED:

Random Forest
KNN
SVM
Naive Bayes
Decision Tree
### DEMO:
![image](https://user-images.githubusercontent.com/65500415/186336301-a3599ebc-52f0-41a4-b210-720d50abac2d.png)

Negative denotes that it is the highest level where criminal sentiments and anxiety symptoms are being detected through the user’s tweets. The more negative words the user uses mean the more negative emotion the tweet has.

![image](https://user-images.githubusercontent.com/65500415/186336386-a63d2163-e60c-410f-9c9c-bd75cc82e934.png)

Postive, this mean that person is unlikely to have criminal sentiments or anxiety.

![image](https://user-images.githubusercontent.com/65500415/186336410-b2158507-363e-498b-92be-17bbc6aa638e.png)

Neutral, This is the middle level wherein the user may or may not have criminal sentiments but may also be more prone to being affected by it.

###RESULTS

![image](https://user-images.githubusercontent.com/65500415/186336581-24b9d11f-c93a-4d31-b90f-f8c42af50a27.png)

It can be observed that the training performance of Naïve Bayes, Support vector machine, K-Nearest Neighbor, Random Forest were appreciable, but these models did not perform well for testing sets. It can be observed that Decision Tree produced better performances for training, validation, and testing sets.
