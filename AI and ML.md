ARTIFICIAL INTELLIGENCE:-
It is a word used to refer to the system as a whole. AI is a way of giving machines to operate in an intelligent way i.e the appropriate way it is to be opearted. We cannot say it mimicks human behaviour or intelligence, it has its own intelligence like human intelligence. AI is often powered by a model that enables this intelligence. For example think of ChatGPT it is an large example of AI and it is powered by a large language model(LLM). People working in big tech companies with AI may refer to it as using deep learning models to perform specific tasks that extract useful patterns and information to be used for prediction. Examples are self-drining cars, chatbots, voice assistants.
MACHINE LEARNING:-It is a part of AI that uses algos trained on data to produce models to perform tasks.
DEEP LEARNING:-It is a subset of ML that uses advanced models built using neural networks to perform taks in the world of ML.

MACHINE LEARNING:-
ML models powers AI. ML algos are those which learns from data. Some examples are linear regression, logistic regression, decision trees, support vectors. They alone cannot do anything they learn patterns from the data which they are feeded into and predict outcomes from the unseen data. One example is house price prediction.
BUILDING A ML MODEL:-
1.Choose a ML algo.(SVM,LR,DT).
2.Feed training data to allow it to learn patterns.
3.Correct the algo iteratively inoder to improve its learning.
4.Here you have the model and validate it on testing the model.
At first we choose an ML algo and thentrain the data inorder to learn and update the parameters. Once the model is trained then it can be evaluated if it is usable. Then we can deploy the model and predict based on the unseen data. Models needs to retrained and redeployed as the data changes in the day to day life rapidly and it is usable only if it is updated according to the latest info available in the real world.
      Features or x variables are the ones that are fed in through the training data. The prediction that the model is making that is spam/ham,yes/no are called label,target or y variables.
 ML models are referred to as garbage in and garbage out. The ML models are best based on the quality of data used to train the model, if you train the model using low quality data whatever algo is used the model will perform poorly.
The types of ML models:-
1.CLASSIFICATION:-Used to predict categorical values, has discrete output.
2.REGRESSION:-Used to predict numerical or continous values, has a range of values or not discrete output.
3.CLUSTERING:-Used to find logical groups in data, aloows us to see different groups of data.
HISTORY OF ML:-
We talk about machine learning a lot asa technology that has gained steam in the last ten years,but machine learning has existed since the 1940s.It was in 1943 that the first neural network usingan electric circuit was developed by Warren McCulloch and Walter Pitts.The goal of the problem was to try and solve communication between computers.So how could computers communicate with one another?In 1950, Alan Turing proposed something that's known as the Turing Test.This is a test of artificial intelligence that involves figuring out whethera machine can act like a human,or if humans can't tell the difference between a human and machine,given answers to questions.Humans pose questions to machines and receive answers,and they try to figure out whether it's a machine answering themor a human being.Doesn't matter if the answers are true or false,the idea is to figure out whether humans can tell the difference.In 1952, Arthur Samuel, who's considered a pioneer in machine learning,is credited with creating the first computer programto play championship-level checkers.In 1957, Frank Rosenblatt, who was a psychologist, developed the Perceptron.This can be thought of as the first neural network unit and algorithm,and you can trace a direct line from the neural networks of todayto the perceptron, first created in 1957.The goal of the perceptron was to learn from data by adjusting its parameters until it reached an optimal solution.
Back in the 50s there were symbolic andasymbolic systems.
1.SYMBOLIC AI:- It focused on processing symbols and concepts rather than numeric data. These are knowledge-based systems. Also known as classical AI nad relies on manipulation of symbols and use of explicit rules for problem solving.
2.SUBSYMBOLIC AI:- Information is processed numerically using calculations using simple interconnected neurons or units rather than symbols and explicit rules. 
SUBSYMBOLIC AI is what we use today.

SUPERVISED LEARNING TECHNIQUES:-
These involve the use of labelled data for traing and testing i.e, the data contains both x variables and y variables. Thenjob is to learn the relationship between x variables and y variables and make predictions on the unseen data. These solves the problems of the form y=f(x). The objective of the model is prediction. One of the limiting factor while using SL is the limited availability of labelled data.
eg:-Regression,classification,sentiment analysis.

UNSUPERVISED LEARNING TECHNIQUES:-
These are used when the labelled data is not available. These are models in such a way to learn from the x variables or features and learn from the data itself. Here the model seeks to find intrinsic patterns in the data instead of relationship between x and y. Also most of the data available are unlabelled data, so it is easy to work with and can produce powerful models.
eg:-Clustering

REGRESSION:-
It is a SL technique that needs labelled data to train the model and predicts continous values. It is used often in cause-effect analysis. 
eg:-House price prediction, given hours of study predict the gpa of student.
A curve or a line in your data is a good fit if the distances of the points in your data from the curve is minimized. If you have lowest distances from the curve that you are using to model the data then it is a good fit. An overfitting curve(a curve that touches alll points in your data) reduces predictive accuracy of your model, it is useless.
1.Linear regression finds the best fit of line in your data(i.e, the line that is as close as possible to the data points). The best fit line can be evaluated or the model can be measured it's best line of fit using the R-squared metric. It will be high for best fit else low, also its value is generally expressed between 1 and 0 or as percentage. It is also referred to as coefficient of determination or coefficient of multiple determination in multiple regression.
A good model minimizes the distance between the fitted line and the original data points.
Differences between the observed values and the predicted values of the best model are small and ubiased.

CLASSIFICATION:-
It isa SL technique that requires labelled data. If there are two output categories, it is called binary classification problem. The predciction of a classfiication problem is a discrete or categorical variable. It there are more than 2 possible classifications then it is multi-class classification.  Every output category has a probability score and the one which has the highest score will be the prediction. Evaluating lassification model:-
1.Accuracy(fraction of correct predictions made). A model with high accuracy need not be a good model .
2.Precision(Fraction of positive identifications that the model was correct.
3.Recall.
4.Confusion matrix.

CLUSTERING:-
It is a ML techniques and most commonly and widely used  USL technique, i.e, the data will not have any associated target values or labels. It is used to find the logical groupings in the data. We take all the data points and represent them in the n-dimensional space and then find the logical clusters that exist among these groups. Data points that are similar will be grouped together or nearby in space. 
1.Elbow method:-Finding the optimal number of clusters in a dataset.
2.Silhouette score:-A measure of how similar an object is to its own cluster compared to other clusters.


TRADITIONAL ML MODELS:-
These use a fundamental algorithmic structure to solve a given problem. It can be anything like fitting a line and using it to make predictions. It requires extraction of data, preprocess the data and then train the model and use it for prediction of raw data.

LINEAR,MULTIPLE REGRESSION:-
The regression algorithm remain same but it varies in types depending on the variables to be predicted . If there is only single variable then it is simple regression and if there is multiple variables then multiple regression and so on.

LOGISTIC REGRESSION:-
It is basically a classification model. It is used to model the probability of a certain class or event occuring such as pass/fail, true/false, etc. The class with higher probability will be the prediction of the model.

ENSEMBLE LEARNING:-
It a ML technique that combines the predictions of multiple base models often reffered to as weak learners or base classifiers to improve overall predictive performance. There are different types of methods based on how different individual learners in the ensemble learn from the underlying data and how individual predictions are combined together:-
1.BAGGING:-It comes from bootstrap aggregating, where multiple base models are trained on random subsets of data with replacement. It helps reduce overfitiing on training data. A model is not trained with the whole data available, a asubset is used to train the model and that is done with replacement. Each time a random amount of data is picked and after use it is replaced and another set is taken. This type is called bootstrap sampling which means that osme data points might be selected multiple times and some may not be selected at all. For combining the predictions of individual base learners there are several methods. For classification problems it uses voting, classes with maximum votes are the prediction. For regression problems it uses average voting. 
2.BOOSTING:-It is different from bagging in the way it combines output of different base learners. If you start with the original training data tha is the input (X) and you train  model1 using this original data. After training this base learner might have done well on some data points and poorly on other data points. Now the data points that were misclassified or mislabelled by the original model is upweighted and  is then used to train or solve the complexity of these data by the model2 and then it repeats iteratively. This allows the next base learner to focus on the mislabelled or misclassified data points errors and mistakes. This continues until the certain desired condition is met. The combining process can use the ones similar to the ones bagging uses.
3.STACKING:- It involves training a meta model to learn how to combine the predictions of the base models effectively. In this we start with a diverse set of base learners, base learners might be of different algorithms, their decision tress may be trained on different datasets, etc. The dataset is then slipt into 2 parts. The first part is used to train the base model and the second part to train the meta model, second part is sometimes called the holdout dataset. The base model is trained with the first part and then makes predictions with the holdout dataset. The predictions from these base models are then fed into the meta model for training them. Once the trained meta model is obtained then we make predictions finally.
