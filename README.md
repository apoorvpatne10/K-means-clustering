# K-means-clustering
K-Means is simple and widely-used clustering algo. Given value of k , it tries to build k clusters from samples in the dataset.

There's a big mall in a city that contains info about its clients, the clients that to the membership card. When the client subscribed to the card, they provide their general info like customer ID, gender, age and annual income and because they have this card they use it to buy all sorts of things in the mall, and therefore the mall has a purchase history of each of its client members and that's how they obtain a 'Spending Score' ,the last column of the dataset. Spending Score is a score that the manager computed for each client based on several criteria including for eg their income, number of times per week they show up in a mall and the amount of money (US dollars) they spent in a year and based on this he computed this metric that contains a value between 1 and 100, so the closer the spending score is to 1 and the less the client spends and closer the score is to 100 the more the client spends. 

Now what I've got to do is to segment this mall's clients into different groups based on these 2 metrics, the annual income and the spending score. And, since the mall has no idea what this client segments might be or how many segments there would be, this must be a clustering problem because we don't know the exact group of clients that the mall should target.

## Plot
![alt text](https://i.imgur.com/nuZnCgW.png)

## Conclusions
![#E81F1F](https://placehold.it/15/E81F1F/000000?text=+) C1 (Careful) : CLients in cluster 1 have high income and low spending scores, that is they have a high income but don't bother spending much money.

![#204DBB](https://placehold.it/15/204DBB/000000?text=+) C2 Standard : Clients in cluster 2 have average income and average spending scores

![#369F23](https://placehold.it/15/369F23/000000?text=+) C3 Targets : Clients in this cluster have high income and hight spending score, that is the cluster of clients that would be the main potential target of the mall marketing agents so it would be very insightful for the mall to understand what kind of products are by the customers in this cluster, so I'll call this cluster as 'targets', which is
pretty intutive

![#3EDCD0](https://placehold.it/15/3EDCD0/000000?text=+) C4 : Clients in this cluster have a low income but they don't care and spend much 

![#F065F0](https://placehold.it/15/F065F0/000000?text=+) C5 : Clients in this cluster have low income and low spending score, so I'll label them as 'sensible'
