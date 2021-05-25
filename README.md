# Jeopardy-Topic-Modeling

## Project description 
This project is about topic modeling on all past questions asked at Jeopardy! show. Our dataset contains 216,930 Jeopardy questions, which is approximately 83% of the questions ever asked on the game show since its inception. In this project we used topic modeling techniques, especially non-negative matrix factorization (NMF) to investigate topics of the show over time. 

## Questions we addressed include:
    1)  For each year, what are the topics of questions asked in "Jeopardy", "Double Jeopardy" and "Final Jeopardy" respectively?
    
    2)  For "Jeopardy", "Double Jeopardy" and "Final Jeopardy", did the topics of questions change over time? Are there any noticeable trend?
    
    3)  Are the topics of harder questions (more monetary values) inherently different than topics of easier questions (less monetary values)?
    
    4)  What are the dynamics of the questions? What topics were considered easy/difficult over time? Are there any trends?
    
## Note: 
There are two main approaches for topic modeling:
    
    1)  Non-negative factorization (NMF)

    2)  Latent Dirichlet Allocation (LDA)
    
They are both unsupervised algorithms. NMF is a matrix decomposition method, and the identified topics are disjoint, meaning one document/article can only belong to one topic. LDA is a probabilistic method that identifies the probability of each document belong to each topic. LDA replies on multinomial-Dirichlet Bayesian model and allows for overlapping topics (e.g: Document 1 belongs to environmental topic with 40% probability and belongs to regulation topic with 60% probability) 

 

         
