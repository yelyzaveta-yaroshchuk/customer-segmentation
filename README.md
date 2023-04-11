# customer-segmentation

The customer analysis and customer segmentation were made in order to understand who are our "alive", active users and who are ready to buy. The next step was customer segmentation and labeling our customers. In the end, I tried to create a model to predict who is who based on the first-day data.

The dataset contains 11436 users and information about session in the game for the first 7 days from registration.

Let's think about how we can understand whether the customer is highly involved in the game. First of all, he spends a lot of time in the game. But let's dive deeper.

Let's analyze how time spends in the game changes with days.
let's check how the winning affects time spent in the game
let's check whether spending soft/hard money results in making a purchase
Is there any difference between game modes for customers involved? And if there is a correlation between customers' behavior and which mode customers choose to play first.
what are main groups of customers we have.

The pipeline for the research is:
1. Loading Data
2. Data Cleaning and Preprocessing 
3. Dimenionality reduction (PCA)
4. Clustering (Agglomerative Clustering)
5. Data balancing
6. Modeling (Random Forest)
7. Reccomendations for future research

In summary we have 4 clusters ( one was deleted because of small number of observation. The model's performance of class predicting based on the first day-data is not satisfactory, especially for classes 1 and 4, where precision and recall are both very low. This indicates that the model is not able to correctly classify samples from these classes. Further analysis and improvement of the model are needed.
