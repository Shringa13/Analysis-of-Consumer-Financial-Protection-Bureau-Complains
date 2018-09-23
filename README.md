# Analysis-of-Consumer-Financial-Protection-Bureau-Complains

<p align="left">
  <img src="https://github.com/Shringa13/Analysis-of-Consumer-Financial-Protection-Bureau-Complains/blob/master/imgs/CFPB_RGB-1024x623.png" width="600" title="Crime Rate">
</p>

The Consumer Financial Protection Bureau is a U.S. government agency that makes sure banks, lenders, and other financial companies treat you fairly.Each week the CFPB sends thousands of consumers’ complaints about financial products and services to companies for response. Those complaints are published here after the company responds or after 15 days, whichever comes first. By adding their voice, consumers help improve the financial marketplace.

### Can you automatically suggest company responses to consumers?
Analysing Consumer Financial Protecĕon Bureau ( CFPB ) database which records complaints about financial products and services to companies for response. Every complaint provides insight into problems that people are experiencing, helping CFPB identify inappropriate practices and allowing us to stop them before they become major issues and creating an automated customer response system.

### Dataset Features

**Date Received  :**               Date on which CFPB receives complaint.  
**Date Sent to Company  :**        Date complaint sent to Company.  
**Product :**                      Type of Product Consumer describe in complaint.  
**Sub Product :**                  Type of Sub Product mentioned by Consumer.  
**Issue :**                        Issue Consumer raised in complaint.  
**Sub - Issue :**                  Sub Issue of the complaint.  
**Consumer Complaint Narrative :** Consumer narrates what happened. Consumer should also opt for sharing the narrative on which CFPB                                        takes required steps on complaint.  
**Company :**                      Company Name.  
**State :**                        Mailing state of the complaint.  
**Company Response to Consumer :** How company responded on complaint.  
**Timely Response ? :**            Yes or No.  

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

