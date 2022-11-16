<Callout type="info" emoji="💡">
  <div >
    <h5 className="text-left h-10 text-gray-400 font-extrabold md:text-1xl mt-0 mb-0" > Click here if you would like to modify or contribute </h5>
    <a href="https://github.com/Subham-Maity/machine-learning-tutorial" target="_blank">
      <img align="left"
           alt="GitHub"
           src="https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white"
      />
      <p align="left">
        <img src="https://media1.giphy.com/media/2HCaWITqHdJmmEA2b7/giphy.webp?cid=ecf05e47oblnld6xqs4q4svq3w8lnpcltavzi667j872uwq7&rid=giphy.webp&ct=s"  width="50"/>
      </p>
    </a>
  </div>
</Callout>

# a. Supervised And Unsupervised Learning

## Message from the Writer
<div class="pb-4"></div>

<div style={{ border:"solid #888", position: "relative" ,opacity: 1 ,borderRadius: "20px" ,overflow: "hidden" }  }>
  <div align="center">
    <div style={{ border: '1px solid #888', padding: '0rem 1rem', textAlign: 'center' }}>
      <h2 align="left">Author</h2>
      <p align="center">
        <img style={{ border:"solid #888", position: "relative" ,opacity: 1 ,borderRadius: "20px" ,overflow: "hidden" }  } src="https://media3.giphy.com/media/B3e4dAhcp36C4Pwpkj/giphy.gif?cid=ecf05e47w96dh0lryx2mqgv8c7e3kmoeiw44bmwgh9rzw4t3&rid=giphy.gif&ct=g"/>
      </p>
      Here you will learn about Supervised and Unsupervised Learning. I hope you will enjoy it. If you have any questions, please feel free to ask me in the comment section. I will try to answer your questions as soon as possible. Thank you for reading this article. Have a nice day.
      <h7 align="center">
        **Are you exited to learn about the Machine Learning?**
      </h7>
    </div>
  </div></div>

## a. Supervised learning
<div class="pb-4"></div>
### What is supervised learning?
<div class="pb-4"></div>


<Callout type='warning'>
In simple term: Supervised learning is a machine learning technique where the model is trained using labeled data. The model learns from the labeled data and then predicts the output for the new data.The labelled data means some input data is already tagged with the correct output.
</Callout>


<div class="font-bold pt-4">
<Feature id="highlighting-card">
  Supervised learning is a process of providing input data as well as correct output data to the machine learning model. The aim of a supervised learning algorithm is to find a mapping function to map the input variable(x) with the output variable(y).
<Callout type= "none">
  In the real-world, supervised learning can be used for the following tasks:
  <ul>
    <li>Image classification</li>
    <li>Speech recognition</li>
    <li>Text classification</li>
    <li>Medical diagnosis</li>
    <li>Stock market prediction</li>
    <li>Weather forecasting</li>
  </ul>
</Callout>
</Feature>
</div>



### Supervised Learning Works
<div class="pb-4"></div>
<Feature id="highlighting-card">
In Supervised Learning, models are trained using labelled dataset where the input data is already tagged with the correct output.Once the training process is completed, the model is tested using the test dataset. The test dataset is the dataset that the model has never seen before. The model is tested on the test dataset to check the accuracy of the model. The accuracy of the model is measured by comparing the predicted output with the actual output.


  <p align="center">
    <img style={{ marginTop:"12px", border:"solid #888" , borderRadius: "15px" , padding :"8px"}} src="https://user-images.githubusercontent.com/97989643/202047710-bdf1475d-e3c1-470c-9ff8-ae69073aab92.png"/>
  </p>



Suppose we have a dataset of different types of shapes which includes square, rectangle, triangle, and Polygon. Now the first step is that we need to train the model for each shape. For training the model, we need to provide the input data and the correct output data. The input data is the image of the shape and the correct output data is the name of the shape. The model is trained using the input data and the correct output data.

-  If the given shape has four sides, and all the sides are equal, then it will be labelled as a Square.
-  If the given shape has four sides, and all the sides are not equal, then it will be labelled as a Rectangle.
-  If the given shape has three sides, then it will be labelled as a Triangle.
-  If the given shape has more than four sides, then it will be labelled as a Polygon.
- If the given shape has less than three sides, then it will be labelled as a None.
- if the given shape has six equal sides and six equal angles, then it will be labelled as a Hexagon.

The machine is already trained on all types of shapes, and when it finds a new shape, it classifies the shape on the bases of a number of sides, and predicts the output.

</Feature>

### Steps Involved
<div class="pb-4"></div>
<Feature id="highlighting-card">
  <ul>
    <li class= "pt-4" >→ First Determine the type of training dataset</li>
    <li class= "pt-4" >→ Collect the training dataset</li>
    <li class= "pt-4" >→ Split the dataset into training , testing dataset and validation dataset</li>
    <li class= "pt-4" >→ Determine the suitable algorithm for the model, such as support vector machine, decision tree, etc. </li>
    <li class= "pt-4" >→ Train the model using the training dataset</li>
    <li class= "pt-4" >→ Execute the algorithm on the training dataset. Sometimes we need validation sets as the control parameters, which are the subset of training datasets. </li>
    <li class= "pt-4" >→ Evaluate the accuracy of the model by providing the test set. If the model predicts the correct output, which means our model is accurate.</li>
  </ul>
</Feature>



### Types
<div class="pb-4"></div>

<p align="center">
    <img style={{ marginTop:"12px", border:"solid #888" , borderRadius: "15px" , padding :"8px"}} src="https://user-images.githubusercontent.com/97989643/202091118-5c02575a-9327-4462-ae32-ffd75bca5f01.png"  width = "500px"/>
</p>




#### 1. Regression
<div class="pb-4"></div>


<div class="font-bold pt-4">
  <Feature id="highlighting-card">
    Regression algorithms are used if there is a relationship between the input variable and the output variable. It is used for the prediction of continuous values. For example, if we want to predict the price of a house, then we can use regression algorithms. The output of the regression algorithm is a continuous value.

    Below are some examples of regression algorithms:
    <Callout type= "none">
      <ul>
        <li class= "pt-4" >→ Linear Regression</li>
        <li class= "pt-4" >→ Regression Trees</li>
        <li class= "pt-4" >→ Non-Linear Regression</li>
        <li class= "pt-4" >→ Bayesian Linear Regression</li>
        <li class= "pt-4" >→ Polynomial Regression</li>
      </ul>

    </Callout>
  </Feature>
</div>


#### 2. Classification
<div class="pb-4"></div>
<div class="font-bold pt-4">
<Feature id="highlighting-card">
  Classification algorithms are used when the output variable is categorical, which means there are two classes such as Yes-No, Male-Female, True-false, etc. For example, if we want to predict whether the customer will buy the product or not, then we can use classification algorithms. The output of the classification algorithm is a discrete value.

  Below are the Spam Filtering,
<Callout type= "none">
  <ul>
    <li class= "pt-4" >→ Random Forest</li>
    <li class= "pt-4" >→ Decision Trees</li>
    <li class= "pt-4" >→ Logistic Regression</li>
    <li class= "pt-4" >→ Support vector Machines</li>
  </ul>

</Callout>
</Feature>
</div>
### Advantages
<div class="pb-4"></div>

- With the help of supervised learning algorithms, we can predict the future outcomes.
- In supervised learning, we can have an exact idea about the classes of objects and the relationship between the input and output variables.
- Supervised learning model helps us to solve various real-world problems such as fraud detection, spam filtering, etc.
- Supervised learning algorithms are easy to implement and understand.
- Supervised learning algorithms are used for both classification and regression problems.

### Disadvantages
<div class="pb-4"></div>

- Supervised learning models are not suitable for handling the complex problems.
- Supervised learning cannot predict the correct output if the test dataset is not similar to the training dataset.
- Training required lots of computation power and time.
- In supervised learning, we need enough knowledge about the dataset to train the model.
- Supervised learning algorithms are not suitable for handling the missing values in the dataset.
- Supervised learning algorithms are not suitable for handling the noisy data.
- Supervised learning algorithms are not suitable for handling the outliers in the dataset.

<div class="mb-6 mt-6 gradient-border " id="box"> </div>

## b. Unsupervised Learning
<div class="pb-4"></div>
### What is Unsupervised learning?
<div class="pb-4"></div>


<Callout type='warning'>
In simple term In unsupervised learning, models are trained on unlabeled data and allowed to act on that data without supervision.
</Callout>

The problem with unsupervised learning is that unlike supervised learning, we don't have corresponding output data, only input data.Unsupervised learning is about finding the underlying structure of a dataset, grouping it based on similarity, and represent that dataset in a compressed format.

<p align="center">
  <img style={{ marginTop:"12px", border:"solid #888" , borderRadius: "15px" , padding :"8px"}} src="https://media1.giphy.com/media/p2BUA5lTw4Jaw/giphy.gif?cid=ecf05e473aok21bdb6jbyy05xciojwv4drd6hsgy9x4z73gv&rid=giphy.gif&ct=g"/>
</p>


Example: Suppose we provide a cat and dog dataset to our unsupervised learning model. The algorithm never trained upon the given dataset which means it does not have any idea about the features of the dataset. Unsupervised learning algorithms identify images' features on their own. Clustering the image dataset into groups based on similarities between images will be performed by an unsupervised learning algorithm.

### Why We Use ?
<div class="pb-4"></div>
<Feature id="highlighting-card">

  - Unsupervised learning is used to find the hidden patterns in the data.
  - Unsupervised learning is much similar as a human learns to think by their own experiences, which makes it closer to the real AI.
  - Unsupervised learning relies on data that is unlabeled and uncategorized, which makes it more valuable.
  - We sometimes do not have input data corresponding to output in the real world, so we need unsupervised learning to deal with such cases.


  </Feature>



### Unsupervised Learning Works
<div class="pb-4"></div>
Working of unsupervised learning can be understood by the below diagram:

<Feature id="highlighting-card">
<p align="center">
  <img style={{ marginTop:"12px", border:"solid #888" , borderRadius: "15px" , padding :"8px"}} src="https://user-images.githubusercontent.com/97989643/202231143-4ba43544-e03e-4c98-8c33-33406334f14d.png"/>
</p>
</Feature>

Here you can see we take an unlabeled dataset and train the model on it. The model will try to find the hidden patterns in the dataset.Firstly, it will interpret the raw data to find the hidden patterns from the data and then will apply suitable algorithms such as k-means clustering, Decision tree, etc.Once it applies the suitable algorithm,
the algorithm divides the data objects into groups according to the similarities and difference between the objects.

### Types
<div class="pb-4"></div>

<p align="center">
  <img style={{ marginTop:"12px", border:"solid #888" , borderRadius: "15px" , padding :"8px"}} src="https://user-images.githubusercontent.com/97989643/202243870-1cd9237b-81f6-4098-8b1d-f977ea086183.png"  width = "500px"/>
</p>


#### 1. Clustering:
<div class="pb-4"></div>

In clustering, objects are grouped so that objects with similar properties remain in a group and have fewer or no similarities with objects from other groups. The cluster analysis finds commonalities between data objects and categorizes them according to the presence or absence of those commonalities.


<div class="font-bold pt-4">
  <Feature id="highlighting-card">


    Below are some examples of Clustering:
    <Callout type= "none">
      <ul>
        <li class= "pt-4" >→ K-Means Clustering</li>
        <li class= "pt-4" >→ Hierarchical Clustering</li>
        <li class= "pt-4" >→ Density-Based Clustering</li>
        <li class= "pt-4" >→ Gaussian Mixture Model</li>
      </ul>

    </Callout>

  </Feature>
</div>

#### 2. Association
<div class="pb-4"></div>

An association rule is an unsupervised learning method that is used for finding the relationships between variables in a large database. It determines the set of items that occurs together in the dataset. The association rule improves the effectiveness of marketing strategies. Such as people who buy X items (suppose a bread) also tend to purchase Y (Butter/Jam) items. Market Basket Analysis is a typical example of an association rule.

<div class="font-bold pt-4">
  <Feature id="highlighting-card">


    Below are some examples of Clustering:
    <Callout type= "none">
      <ul>
        <li class= "pt-4" >→ Apriori Algorithm</li>
        <li class= "pt-4" >→ Eclat Algorithm</li>
      </ul>

    </Callout>

  </Feature>
</div>
### Algorithms
<div class="pb-4"></div>
Below are some of the algorithms used in unsupervised learning:
<Callout type= "none">
<ul>
  <li class= "pt-4" >→ K-means clustering</li>
  <li class= "pt-4" >→ KNN (k-nearest neighbors)</li>
  <li class= "pt-4" >→ Hierarchical clustering</li>
  <li class= "pt-4" >→ Anomaly detection</li>
  <li class= "pt-4" >→ Neural Networks</li>
  <li class= "pt-4" >→ Principle Component Analysis</li>
  <li class= "pt-4" >→ Independent Component Analysis</li>
  <li class= "pt-4" >→ Apriori algorithm</li>
  <li class= "pt-4" >→ Singular value decomposition</li>
</ul>
</Callout>


### Advantages

<div class="pb-4"></div>

<Feature id="highlighting-card">
  <ul>
    <li class= "pt-4" >→ Unsupervised learning is used to find the hidden patterns in the data.</li>
    <li class= "pt-4" >→ Unsupervised learning is much similar as a human learns to think by their own experiences, which makes it closer to the real AI.</li>
    <li class= "pt-4" >→ Unsupervised learning relies on data that is unlabeled and uncategorized, which makes it more valuable.</li>
    <li class= "pt-4" >→ We sometimes do not have input data corresponding to output in the real world, so we need unsupervised learning to deal with such cases.</li>
  </ul>
</Feature>

### Disadvantages

<div class="pb-4"></div>

<Feature id="highlighting-card">
  <ul>
    <li class= "pt-4" >→ Unsupervised learning is intrinsically more difficult than supervised learning as it does not have corresponding output.</li>
    <li class= "pt-4" >→ Unsupervised learning is not suitable for the prediction of future events.</li>
    <li class= "pt-4" >→ Unsupervised learning algorithms are less accurate since the input data is not labeled, and algorithms cannot predict the exact output.</li>
  </ul>
</Feature>

<div class="mb-6 mt-6 gradient-border " id="box"> </div>

## Supervised Learning vs Unsupervised Learning

<div class="pb-4"></div>
<div style={{ marginTop:"12px", border:"solid #492965" , borderRadius: "25px" , opacity:"80%", padding :"8px"}}>
Supervised  Learning | Unsupervised Learning
--- | ---
Trained with labeled data | Trained with unlabeled data
takes direct feedback to check if it is predicting correct output or not | does not take direct feedback
predicts the output for the given input | finds the hidden patterns in data.
input data is provided to the model also with the output data | only input data is provided to the model.
purpose is when we provide the data model can predict the output | purpose is when we provide the data model can find the hidden patterns and useful insights from the unknown dataset
Needs supervision to train the model | does not need supervision to train the model
Supervised learning can be categorized in Classification and Regression problems. | Unsupervised learning can be categorized in Clustering and Association problems.
Can be used for those cases where we know the input as well as corresponding outputs. | Can be used for those cases where we know the input but not the corresponding outputs.
Model produces an accurate result | Model produces an approximate result may give less accurate result
Not close to true Artificial intelligence as in this, we first train the model for each data, and then only it can predict the correct output | More close to the true Artificial Intelligence as it learns similarly as a child learns daily routine things by his experiences.
Linear Regression, Logistic Regression, Support Vector Machine, Multi-class Classification, Decision tree, Bayesian Logic, etc. are some of the examples of Supervised Learning. | K-means clustering, KNN (k-nearest neighbors), Hierarchical clustering, Anomaly detection, Neural Networks, Principle Component Analysis, Independent Component Analysis, Apriori algorithm, Singular value decomposition are some of the examples of Unsupervised Learning.

</div>
