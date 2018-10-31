# A-look-into-Netflix-Challenge-Making-better-recommendations
Solves the netflix challenge with a beginner friendly documentation.Explores various techniques used in practiacal recommender sysetms.


![netflix](https://github.com/vin136/A-look-into-Netflix-Challenge-Making-better-recommendations/blob/master/netflix.png)
## THIS REPO CONTAINS  TWO NOTEBOOKS:


####  Note : The author has only tried on 20k users and 2k movies.Bigger datasets will give better results in general.

### ONE NAMED DeepNetflix contain a deep learning based model,while the other one contains a host of classical techniques including (matrix factorization,similarity based techniques {user-user},{movie-movie},ensembling techniques and a ton more.)


Deepnetflix includes lot of explanation and links to further resources.Here let's take a look at the approach taken in NETFLIX NOTEBOOK.(For the code implementation refer notebook)

### We typically have two popular approaches to Recommender systems :


* Content Based : Consider you are starting an online apparel store.It makes sense to customize each user's home page based on his buying history but you haven't yet got enough traffic.You might show recommendations based on demographics or general popularity.After a while you could slowly leverage the data and start to personalize for each user.We could start to recommend each user based on their nearest('some metric to determine similarity like *cosine*..' ) user's buying history.Host of other similar techniques and heuristics can be put under cotent based recommender systems.


* Collaborative Filtering:This refers to Matrix factorization technques  - > largely became popular after the official netflix challenge.(refer *DeepNetflix*)



![whyntDL](https://github.com/vin136/A-look-into-Netflix-Challenge-Making-better-recommendations/blob/master/whyntDL.png)


NOTE:
In real life making a good recommender system involves lot's of controlled experiments(A/B tests) and many iterations of continuous improvement.This repo just contains some easily demonstable techniques.I suggest if you have real-life use case at your work then take look at model based systems..say in this case  start by modeling the user whose preferences are updated based on his click-behaviour(simple probability based).This has the advantage of being simple and found to work remarkably well in practice.

* [Christopher Bishop is writing a new book along these lines](http://mbmlbook.com/)




