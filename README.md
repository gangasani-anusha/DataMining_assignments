Dataset is downloaded from: https://www.kaggle.com/shivamb/netflix-shows


# **Data Cleaning with Colab:**

### **Step1: Importing Data** 

Import all the necessary packages like pandas, numpy, sklearn etc.

Import the netflix dataset from google drive by mounting the gdrive

### **Step2: Data Cleaning**

**Handling the NULL values & Data types:**

Analyze the Null values and the data types of the dataset

Replace the null values of coulmns director and cast with the value "Other Director", "Other Cast" respectively  and also we can fill them with the nearest values without changing the basic statistics

Change the data types from string to numeric

### **Step3: Data Pre-processing**

**Feature Engineering**

Analyze the data, add the columns and separate the data within the columns by adding an extra column

**Outlier Analysis**

Plot a graph to predict the outilers of dataset

Remove the data from the dataset based on the outlier analysis and store them in a new dataset

### **Step4: Visualisation**

With the data obtained after data cleaning and pre-processing we have displyed the data via pie charts, bar graphs, scatter plots, 

strip and pairplots. Below are the plots:

1. Ratings on Netflix using Pie Chart

2. Types of shows added with rating using Bar Plots

3. Shows added over the years using Scatter Plots

4. Types of Rating

5. Frequency of Shows using Bar plots

6. Number of Shows released in 10 Countries

7. Shows and thier released years using Strip

8. Genres of Shows

9. Top 10 Actors in Shows using Bar plot

10. Pairplot of the Shows

### **Step5: Model Training**

**Scikit-Learn with Linear Regression:**

Select a model to instantiate for storing values. Then add the data to number of matricies and apply model to data to generate the slope, intercept. With that, evaluate the efficiency of the model by comparing it to a baseline developed with slope and intercept.

**Scikit-Learn Classification with Gaussian naive Bayes model:**

Exract the required data in the form of matrix and separate the data into a training and testing set. Apply the Gaussian navie Bayels model to calculate the accuracy. Now apply confusion matrix to compute the scikit learn and plot seaborn

**Cosine Similarity:**

Build a vectorizer which removes all the stop words in english and store it in a matrix. From that, extract the cosine similarity matrix and reset the index of the dataset. Now we can extract similar data by passing a column of data and cosine similarity data.




# **Data Cleaning with OpenRefine:**

**Import Data**

https://user-images.githubusercontent.com/90420965/135971292-bd8e7965-d3e4-4562-855a-44788403f288.mp4

**Handling Null values**

https://user-images.githubusercontent.com/90420965/135980380-e2ddab5e-ebb3-4601-833c-f02b4d8fe506.mp4

**Changing Data type and Feature Engineering**

https://user-images.githubusercontent.com/90420965/135982402-3e78c7f3-004c-4c31-a86e-965038d7d59c.mp4

**Outlier Analysis**

https://user-images.githubusercontent.com/90420965/135986830-2131a879-ffe2-4187-b6d4-9620dd641a8e.mp4

**Displaying the shows released in India**

https://user-images.githubusercontent.com/90420965/135985550-efad3dad-af8c-4f9f-95d2-79151eaffa7a.mp4

### **References:**

https://github.com/codebasics/py/blob/master/DataScience/BangloreHomePrices/model/banglore_home_prices_final.ipynb

https://scikit-learn.org/stable/tutorial/basic/tutorial.html

https://openrefine.org/documentation.html

https://www.kaggle.com
