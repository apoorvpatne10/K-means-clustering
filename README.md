# K-means-clustering
K-Means is simple and widely-used clustering algo. Given value of k , it tries to build k clusters from samples in the dataset.

There's a big mall in a city that contains info about its clients, the clients that to the membership card. When the client subscribed to the card, they provide their general info like customer ID, gender, age and annual income and because they have this card they use it to buy all sorts of things in the mall, and therefore the mall has a purchase history of each of its client members and that's how they obtain a 'Spending Score' ,the last column of the dataset. Spending Score is a score that the manager computed for each client based on several criteria including for eg their income, number of times per week they show up in a mall and the amount of money (US dollars) they spent in a year and based on this he computed this metric that contains a value between 1 and 100, so the closer the spending score is to 1 and the less the client spends and closer the score is to 100 the more the client spends. 

Now what I've got to do is to segment this mall's clients into different groups based on these 2 metrics, the annual income and the spending score. And, since the mall has no idea what this client segments might be or how many segments there would be, this must be a clustering problem because we don't know the exact group of clients that the mall should target.

![alt text](https://imgur.com/a/oMNXV.png)
