# Paper Title: Performance Analysis of Ensemble Based Data Balancing Approaches in Class Imbalance Problem Using Normalization

In this paper, we have implemented two state-of-the-art data balancing approaches(Undersampling and Oversampling) ensembled by AdaBoost algorithm. 
Then we have investigated and compared the two methods with a recently developed method called Random Splitting data balancing method with and without applying normalization. 
For normalization, three well known normalization techniques are used such as min-max, z-score and robust-scaling normalization. 
Our concerned approach Random Splitting based data balancing method is an ensemble method which firstly converts imbalanced data set into several balanced data set.
Then from that balanced data set multiple classification models are built using a specific classification algorithm.
Finally, the classification models are combined using max ensemble rules.The empirical analysis using fifteen imbalanced data set show that Random Splitting based data balancing 
method with min-max normalization is dominant over the other methods for Random Forest classifier.


