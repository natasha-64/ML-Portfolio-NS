# A Guide to Machine Learning: Understanding the Fundamentals and Techniques

Machine learning is a crucial part of modern technology in a wide range of fields. With the advancement of recent AI such as ChatGPT, machine learning will only continue to become increasingly influential in everyday life. This essay will address the three types of machine learning: supervised, unsupervised and reinforcement learning.

Supervised learning is trained on pre-labelled data and is commonly used for prediction. Essentially, the dataset is split into a training and test set. The model will then analyse the patterns found within the training dataset. This process is repeated until a data scientist decides the confusion matrix (performance measurement) is satisfactory. The test set will then be presented to the model to predict, which it will achieve through what it has observed through the training set. Therefore, the training model must be general to avoid “over-fitting”, where the model fails due to lack of variety in training data. This method of learning is highly effective for regression and classification problems. Regression problems involve continuous data, and can be used for prediction in areas such as stock prices and the impacts of medical drugs. Commonly, this will take the form of linear regression, but can also include others such as non-linear or Bayesian regression. Classification uses discrete data and is able to classify data into categories based on its predictions. Algorithms such as logistic regression, Naive Bayes Classification and Support Vector Machine can be used for tasks such as the identification of wildlife or customer behaviour prediction. Perhaps one of the most famous real-life examples of supervised learning is email spam detection, which utilises preexisting data to predict the likelihood of an email being spam. This technology is so potent that Google’s learning model has advanced to ~99.9% accuracy in detecting spam.

Unsupervised learning is used to analyse unlabelled data and is more useful for finding underlying patterns within a dataset, and predicting outputs based on these patterns. Two of the main categories within unsupervised learning are clustering and association. Clustering can be done through algorithms such as K-Means, and generally involve defining the number of clusters within the dataset, K, and then repeatedly correcting the centroid (centre) points of the clusters. The algorithm randomly assigns the centroids at first, and then repeatedly moves them to the mean of the input samples assigned to their cluster, which are determined through closeness. This repeats a stated number of iterations are completed, or until no more change occurs. Clustering is used for things like advertising or email marketing, where companies tailor the emails they send to customers in order to perform better. This is based on each individual’s statistics, for example, the percentage of emails opened or ads clicked. Association is similar to clustering, however, it focuses more on how one datapoint depends on others. It uses the Apriori, Eclat, and F-P Growth algorithms, and its uses include online shopping suggestions, data mining and medical diagnosis. Unsupervised learning is used across many projects, especially document clustering and music recommendations.

Reinforcement learning is the most similar to human learning, and used for bettering machines in their efficiency or skill. In this style of learning, the model (known as an agent) will decide on an action, and test it in an environment. Based on the resulting state, the model will receive a reward if it achieves a successful outcome. This process repeats itself, and the model will aim to only complete actions with rewards, thus ‘learning’ how to reach its end goal most efficiently and correctly. Reinforcement learning is highly useful in many areas including robot automation, language and image processing, gaming, healthcare and energy conservation. One of the most impressive instances of reinforcement learning within gaming is AlphaGo, the first computer program able to beat a world champion at Go. Go is considered to be the most challenging game for machines to master due to its enormous number of possibilities - at 10^170, the game has more board configurations than atoms in the universe. AlphaGo progressed through neural networks and reinforcement learning over 44 million training games to become the strongest Go player in the world and inventing winning moves never played before by humans. The power of this model within the Go world truly showcases the power of machine learning as a whole.

In summary, machine learning can be split into three categories; supervised learning aims to generate a model from labelled data, unsupervised learning categorises unlabelled data, and reinforcement learning uses an action-reward approach to improve efficiency and skill.

## Bibliography

9 real-life examples of reinforcement learning (2022) SCU. Available at: https://onlinedegrees.scu.edu/media/blog 9-examples-of-reinforcement-learning. 

AlphaGo (no date) Google DeepMind. Available at: https://www.deepmind.com/research/highlighted-research/alphago. 

Association rule learning (no date) www.javatpoint.com. Available at: https://www.javatpoint.com/

association-rule-learning#:~:text=Association%20rule%20learning%20is%20a,among%20the%20variables%20of%20dataset. 

Barreto, S. (2023) Real-life examples of supervised learning and unsupervised learning, Baeldung on Computer Science. Available at: https://www.baeldung.com/cs/examples-supervised-unsupervised-learning. 

Dada, E. et al. (2019) Machine learning for email spam filtering: Review, approaches and open research problems, Heliyon. Available at: https://www.sciencedirect.com/science/article/pii/S2405844018353404. 

Delua, J. (2021) Supervised vs. unsupervised learning: What’s the difference?, IBM Blog. Available at: https://www.ibm.com/blog/supervised-vs-unsupervised-learning/. 

Khandelwal, R. (2022) Supervised, unsupervised, and reinforcement learning, Medium. Available at: https://arshren.medium.com/supervised-unsupervised-and-reinforcement-learning-245b59709f68. 

Kumar, A. (2022) Classification problems real-life examples, Data Analytics. Available at: https://vitalflux.com/classification-problems-real-world-examples/. 

Mwiti, D. (2023) 10 real-life applications of reinforcement learning, neptune.ai. Available at: https://neptune.ai/blog/reinforcement-learning-applications. 

Picasso, G. (2022) Types of machine learning: Supervised, Unsupervised & Reinforcement, Sailthru. Available at: https://www.sailthru.com/marketing-blog/reinforcement-learning-machine-learning/.

Zach (2022) 5 examples of cluster analysis in real life, Statology. Available at: https://www.statology.org/cluster-analysis-real-life-examples/. 