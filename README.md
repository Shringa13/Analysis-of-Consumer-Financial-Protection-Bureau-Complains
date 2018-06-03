# Analysis-of-Consumer-Financial-Protection-Bureau-Complains
After reviewing the CFPB consumer complaint dataset we identified eight possible responses a consumer complaint may receive from a company. These company responses are our class labels and they are:
1. Closed with explanation: 494,738 records
2. Closed with monetary relief: 45,006 records
3. Closed with non-monetary relief: 84,818 records
4. Closed with relief: 5,252 records
5. Closed with without relief: 17,601 records
6. Closed: 15,796 records
7. In progress: 2,105 records
8. Untimely response: 3,507 records
Our purpose is to predict what a company’s response to a complaint would be. If we can find a pattern in the dataset of how companies respond to complaints of a certain category, we may be able to predict with some accuracy the probability of a complaint getting any of the eight response labels. We narrow our prediction scope to the first three labels because they make up over 93% of the entire dataset which contains 668,824 records.

