# Parallel-recommendationSystem-in-a-Distributed-Environment
Parallel product recommendor system

There are many recommendation sytems present out there that work really well but the problem
with them is

1.Popularity bias: the problem that arises when users give high rating because of their favourite
actor,director or just when if any of cast member dies they get carried away by emotions.

2.Cold-start problem: some really good movies are hidden from recommendation system, because to
when movies added to the catalogue have either none or very little amount of people watch it
while recommender rely on the movie’s interactions to make recommendations

3.Scalability issue: lack of the ability to scale to much larger sets of data when more and more users
and movies added into our database


The method used in this project is matrix factorization algorithm that work by decomposing
the user-item interaction matrix into the product of two lower dimensionality rectangular
matrices.One matrix can be seen as the user matrix where rows represent users and columns are
latent factors. 
            Model learns to factorize rating matrix into user and movie representations, which
allows model to predict better personalized movie ratings.The idea behind matrix factorization is
to use latent factors to represent user preferences or movie topics in a much lower dimension
space
