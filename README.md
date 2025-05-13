# csce822-homework-1-knn-and-random-forest-solved
**TO GET THIS SOLUTION VISIT:** [CSCE822 Homework 1-KNN and Random Forest Solved](https://www.ankitcodinghub.com/product/csce822-homework-1-knn-and-random-forest-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;93301&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSCE822 Homework 1-KNN and Random Forest Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Attached melb_data.csv file is the Snapshot of Tony Pino’s Melbourne Housing Dataset. Do the following data preprocessing and apply KNN and RandomForest algorithms to classify the property prices.

1. Fill the missing values in the dataset using imputation approaches as we talked in class. You can use the scikit-learn’s module

from sklearn.impute import SimpleImputer

my_imputer = SimpleImputer()

data_with_imputed_values = my_imputer.fit_transform(original_data)

The default imputer use mean values to fill the missing values. You can try other imputation method as well.

2. Replace the categorical/nominal attributes with one-hot-encoding

You can use Category Encoders package for use with scikit-learn in Python

Read this blog for more approaches for data encoding

https://towardsdatascience.com/smarter-ways-to-encode-categorical-data-for-machine- learning-part-1-of-3-6dca2f71b159

3. Install Weka system on your computer

Sort all the property samples by the property prices and divide the samples equally into 5 categories/classes: Top value, High value, medium value, low value, bottom value. Change the labels to the classes so it becomes a 5-class classification problem.

Install Weka https://www.cs.waikato.ac.nz/ml/weka/ software

Step1: You need to split the whole dataset into training (75% samples), 10% for validation, and

15% for testing datasets

Step2: Apply the KNN algorithm of Weka with K=5 to 10 to classify the property instances into 5 classes. Calculate the accuracy for each K values on the validation set, pick the best K value, Kbestand then evaluate its performance on the test set.

Step3: repeat step1 and step2 10 times to get 10 test set performance and calculate mean and standard deviation.

4. Now do this same experiments using the RandomForest algorithm, but this time, we use scikit-learn package and report the performance.

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
CSCE822 Homework1

</div>
</div>
<div class="layoutArea">
<div class="column">
Test set performance.

K=5 K=6 K=7 K=8 K=9 K=10 KNN Average …

accuracy. RandomForest Average

accuracy

Write report to discuss the performances of KNN and randomforest on test sets. You are encouraged to compare the performance of different missing value imputation methods or the categorical encoding methods.

Hints:

a) random split function from scikit-learn

from sklearn.model_selection import train_test_split

xTrain, xTest, yTrain, yTest = train_test_split(x, y, test_size = 0.2, random_state = 0)

<ol start="2">
<li>b) &nbsp;random forest example of scikit-learn can be easily found online.</li>
<li>c) &nbsp;For problem3, you can also use sci-kit learn if you prefer.</li>
</ol>
</div>
</div>
</div>
