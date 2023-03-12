This repository contains a file which is divided into two parts - 

**1) Online product review** 
Analysed the dataset 'product_review.csv' which contains consumer reviews of some selected online shopping products. The goal of the task is to perform some data explorations on it. Then generate training, validation and test datasets before model building and prediction. 

**Description of the data:**

- Each observation (row) in this dataset is a review of a particular product by a particular user.
- The **date** column is the date when the review was provided.
- The **product** column is the name of the product reviewed.
- The **category** column is the primary category of the product reviewed.
- The **text** column is the review text.
- The **user** column is the name of the user who gives the review
- The **rating** column is the number of stars (1 through 5) assigned by the reviewer to the product. (Higher stars is better.) In other words, it is the rating of the product by the user who wrote the review.

**2) Chatbot**
Created a chatbot using the concepts of vectorization and cosine similarity. For the purposes of the chatbot to be created, I used a repository of questions and answers gathered from online shopping website for electronic items. Being trained on Q&A data for electronic items,the chatbot could be deployed as automated Q&A support under the Electronic Items section. The corpus Electronics_QA.json is in a JavaScript Object Notation (JSON)-like format. It contains multiple features for each pair of Q&A, but I have used only the feautres question and answer.
