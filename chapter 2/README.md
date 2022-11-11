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
# Features And Labels

<div style={{ border:"solid #888", position: "relative" ,opacity: 1 ,borderRadius: "20px" ,overflow: "hidden" }  }>
  <div align="center">
    <div style={{ border: '1px solid #888', padding: '0rem 1rem', textAlign: 'center' }}>
      <h2 align="left">Author</h2>
      <p align="center">
        <img style={{ border:"solid #888", position: "relative" ,opacity: 1 ,borderRadius: "20px" ,overflow: "hidden" }  } src="https://github.com/Subham-Maity/machine-learning-tutorial/blob/main/chapter%202/Original%20Gif%20for%20chapter%202/ezgif-1-964738a622.gif?raw=true"/>
      </p>
      Here you will learn about the features and labels of the dataset.
      <h7 align="center">
        **Are you exited to learn about the features and labels of the dataset?**
      </h7>
    </div>
  </div></div>


In this chapter 2 we'll discuss two important conceptual definition of machine learning. These are features and labels. These are the most important part of machine learning. So, let's get started.

## Features

### What is a feature?
<Callout type="info" emoji="💡">
 In simple words, features are the input variables of the dataset.
</Callout>

In machine learning algorithm it takes input data to generate the output.
Input data in a tabular form is called dataset. Dataset is a collection of rows and columns. Each row represents a single data point and each column represents a feature of that data point. So, features are the columns of the dataset.
Rows(instances or observations) are called as samples and columns(variable or attribute) are called as features.

### Example of features
- Suppose we need to predict an animal's species based on its weight and height. So, in this case weight and height are the features of the dataset.
- Suppose we need to predict the price of a house based on its area, number of rooms, number of bathrooms, etc. So, in this case area, number of rooms, number of bathrooms, etc. are the features of the dataset.
- Suppose we need to predict the price of a car based on its mileage, engine size, number of cylinders, etc. So, in this case mileage, engine size, number of cylinders, etc. are the features of the dataset.

So now we can say **features are characteristics of observations**

### Measurements of features

#### Example 1
Suppose we have a thermometer and we want to measure the temperature of a room.
Now let's say that thermometer take the temperature record of the room every 10 minutes.
After recording it for 24 hours, we get a table of temperature record of the room for 24 hours.
We get a table like this:
<div className="flex justify-between">
<p align="center">
  <img  src="https://user-images.githubusercontent.com/97989643/201364393-84cbb342-a306-479d-bfd0-b79874adf07e.gif"/>
</p>


  <div style={{ border:"solid #888", position: "relative" ,opacity: 1 ,borderRadius: "20px" ,overflow: "hidden" }  }>
| Time | Temperature |
|------|-------------|
| 10:00 AM | 25°C |
| 10:10 AM | 26°C |
| 10:20 AM | 27°C |
| 10:30 AM | 28°C |
| 10:40 AM | 29°C |
| 10:50 AM | 30°C |
| 11:00 AM | 31°C |
| 11:10 AM | 32°C |
| 11:20 AM | 33°C |
| 11:30 AM | 34°C |
| 11:40 AM | 35°C |
| 11:50 AM | 36°C |

  </div>

</div>

The thermometer performs measurements whose result constitutes a table of observations.The value associated with each measurement corresponds to a feature “temperature”.

#### Example 2

A police radar measures the speed of cars passing by. The speed of each car is recorded as a feature of the dataset.
In the computer where each row contains the license plate number of a car and its speed in this case  license plate ID or index of the dataset and the speed are the features.
If we want to predict what cars use a certain street, we can use the license plate number as a feature not the index of the dataset.
<div style={{ border:"solid #888", position: "relative" ,opacity: 1 ,borderRadius: "20px" ,overflow: "hidden" }  } className="flex justify-between">
  <p align="center">
    <img  src="https://cdn.dribbble.com/users/988103/screenshots/10824258/01-radar-gun.gif" width="350"  />
  </p>
  <p align="center">
    <img  src="https://i.pinimg.com/originals/df/0a/d7/df0ad71d0da0d9dc89b4fbab658c96da.gif" width="350"  />
  </p>
  <div >

| Car's License Plate | Speed |
|------|-------------|
| 1234 | 60 km/h |
| 5678 | 70 km/h |
| 9012 | 80 km/h |

  </div>
</div>

### Identification of Features

Above example shows that we alternatively use the license plate number or the index of the dataset as a feature.
So it ultimately depends on the task we want to perform or we can say depends on the objective of the task.
So **nobody approaches a problem without background knowledge and expectations about that problem’s characteristics, we can say that our expectations shape our measurements**

| Car's License Plate | Speed |
|------|-------------|
| 1234 | 60 km/h |
| 5678 | 70 km/h |
| 9012 | 80 km/h |

so here which will be the feature it depends on the task we want to perform.

## Labels
### What is a label?
<Callout type="info" emoji="💡">
  In simple words, labels are the output variables of the dataset.
</Callout>


In machine learning algorithm it takes input data to generate the output.

For example
<div style={{ border:"solid #888", position: "relative" ,opacity: 1 ,borderRadius: "20px" ,overflow: "hidden" }  } >
  <p align="center">
    <img  src="https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Ft1.daumcdn.net%2Fcfile%2Ftistory%2F99BCF3335D7E7DAE02"   />
  </p>
</div>

In the above example, the input data is the image of a cat and the output is the label of the image which is cat.
### Labels vs Features
We can understand the difference between both of them with a simple example of an image dataset of animals. So, height, weight, color, etc., are the features. Whereas it is a cat or dog, these are the labels.

### What is data labeling?
If we input a vast amount of raw data to a Machine Learning model and expect it to learn from it, then it is not enough. We need to label the data. So, labeling is the process of assigning labels to the data. It is a very important step in machine learning. So, we need to label the data properly. If we label the data properly then the model will perform well. If we label the data improperly then the model will perform poorly.

**Hence, we can define it as, "Data labelling is a process of adding some meaning to different types of datasets, so that it can be properly used to train a Machine Learning Model. Data labelling is also called as Data Annotation (however, there is minor difference between both of them)."**

### Labeled Data vs. Unlabelled Data

<div className="flex justify-between">

- **Labeled Data:** Labeled data is data that has some predefined tags such as name, type, or number. For example, an image has an apple or banana.
- **Unlabeled Data:**  At the same time, unlabelled data contains no tags or no specified name.

- **Labeled Data:** Labeled data is used in Supervised Learning techniques
- **Unlabeled Data:**  Unlabelled data is used in Unsupervised Learning.

- **Labeled Data:** Labeled data is difficult to get
- **Unlabeled Data:**  Unalabled data is easy to acquire.

</div>

### How does Data Labelling Work?


Today, most machine learning models use supervised learning techniques to map an input variable to an output variable and predict its value.For supervised learning, we need the labeled dataset to train the model so that it can make accurate predictions.The Data labeling begins with a process of "Human-in-the-loop" or HITL participation, where humans are asked to make a judgment for the given unlabelled data. For example, a human labeler may be asked to tag an image dataset, where "does the image contain a cat" is true.

![main](https://user-images.githubusercontent.com/97989643/201407204-8077d8ea-0c35-4aa8-a698-0b40603215a6.png)


ML models learn from human-provided labels, which is called a model training process, and then they can predict with new data or test data using the trained model.
