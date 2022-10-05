One of the hot topics in the current era is the use of recommender systems. A
recommender system is a subclass of an information filtering system that seeks to predict a
user's rank or preference in a particular case. Examples of such systems include movie
streaming websites that offer movies to users based on their history, or an online shopping
site that offers another product based on a user's previous purchase. In such systems, the
computer uses the data it has already collected from its users to try to predict the vague
opinions of users on specific topics and use this conjecture to persuade the user to use the
platform more.
The purpose of this project was to implement a recommender system and adjust its
parameters to obtain the minimum error and compare its performance with other
recommender systems. The algorithm used to implement this system in the project was matrix
factorization algorithm. In this algorithm, two matrices P and Q are formed and attempts are
made to adjust the indices of these two so that the product of the multiplication of these two
matrices is close to the user-vote matrix. Once these two matrices are formed, it is easy to
predict users' votes for movies they have not seen. After implementing this algorithm, its
hyper parameters were tuned so that the output had the lowest error, and then this error was
compared to the error of other methods such as RBM, which performs this operation using
neural networks. The results of this study showed that in this implementation, the predicted
output differs from the actual output by an average of about 14% and this error is accepted
and appropriate for such systems. Also, this method performed better than the RBM method
which had an error of about 17%.
