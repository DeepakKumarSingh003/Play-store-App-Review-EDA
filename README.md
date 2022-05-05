# Exploratory Data Analysis on Play Store App Reviews

## 1.Abstract:
* **Google play store serves as the official app store for devices running on the Android OS . With over 3.15 Million apps Google play store is a Biggest App store platform in the world of application service providers.**
* **Play store Data has immense potential of digging out the business value needed by the developers. As of today’s competitive market taking business decision based on some analysis could help the stakeholders and other senior managers in increasing the business volume.**
* **The dataset provided with us has very useful information related with App making business. In this EDA on Play Store we will go through some of the very useful insights that would probably help to increase the economic volume of the App making business. This EDA will mainly give you the users response to different category of Apps. We have tried our best to find out as many insight as possible in order to discover key factors responsible for app engagement and success..**

## 2.Introduction:
* **We are provided with two datasets:**
 * **Play_store_data: It contains the basic details of the app like number of user reviews, ratings, etc.**
 * **User_reviews: It contains the user reviews and its sentiment score for the respective app. We need to explore and analyze the data to discover key factors responsible for app engagement and success.**

### The contents of play_store_data are:
* **App:** It contains the name of the app with a short description (optional).
* **Category:** This section gives the category to which an app belongs. In this dataset, the apps are divided among 33 categories.
* **Size:** The disk space required to install the respective app.
* **Rating:** The average rating given by the users for the respective app. It can be in between 1 and 5.
* **Reviews:** The number of users that have dropped a review for the respective app.
* **Installs:** The approximate number of times the respective app was installed.
* **Type:** It states whether an app is free to use or paid.
* **Price:** It gives the price payable to install the app. For free type apps, the price is zero.
* **Content rating:** It states which age group is suitable to consume the content of the respective app.
* **Genres:** It gives the genre(s) to which the respective app belongs.
* **Last updated:** It gives the day in which the latest update for the respective app was released.
* **Current Ver:** It gives the current version of the respective app.
* **Android Ver:** It gives the android version of the respective app.

### The contents of user_reviews are:
* **App:** It contains the name of the app with a short description (optional).
* **Translated_Review:** It contains the English translation of the review dropped by the user of the app.
* **Sentiment:** It gives the attitude/emotion of the writer. It can be ‘Positive’, ‘Negative’, or ‘Neutral’.
* **Sentiment_Polarity:** It gives the polarity of the review. Its range is [-1,1], where 1 means ‘Positive statement’ and -1 means a ‘Negative statement’.
* **Sentiment_Subjectivity:** This value gives how close a reviewer’s opinion is to the opinion of the general public. Its range is [0,1]. Higher the subjectivity, closer is the reviewer’s opinion to the opinion of the general public, and lower subjectivity indicates the review is more of a factual information.

### 3.Data Processing:
* **Once we have defined and understood the columns and the type of data it contains, it is necessary to eliminate the obvious errors, NaN values, and duplicates. Apart from this in some cases it is necessary to convert the datatype of the entries in the columns into more appropriate datatype.**

### 4.Challenges Faced:
* **Reading the dataset and comprehending the problem statement.**
* **Examining the business KPIs for app development and devising a solution to the problem.**
* **Handling the error, duplicate and NaN values in the dataset.**
* **Designing multiple visualizations to summarize the information in the dataset and successfully communicate the results and trends to the reader.**

## 5.Conclusion:



