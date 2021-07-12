# Cora Analysis

### Data Used
Exploring Cora dataset, consisting of 2708 scientific publications of 7 categories. 

### Utilized Techniques
1.	graph algorithms (breadth-first search) to find the shortest path from a publication to a paper subject
2.	dynamic programming (bellman-ford) to find the distribution of distances from the most cited publication to the rest of 2708 publications
3.	machine learning (logistic regression, decision tree, and kmeans) to accurately predict the subject of the paper.
 
### Key Finding

- Using Bellman-ford alorithm, our team found that paper with the most citations is 35, which means that other papers cited this specific paper 35 times.
- Average distance from the most cited paper to the rest of the papers is 4.1
- Observed the best performance in predicting 7 paper subjects from logistic regression and the worst performance from the kmeans as it was not able to properly identify the paper subject clusters.


