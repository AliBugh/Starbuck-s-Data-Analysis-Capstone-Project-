# Starbuck-s-Data-Analysis-Capstone-Project-

This project is a part of Udacity Data Science Nanodegree

### Table of Contents

1. [Project Overview](#overview)
2. [Problem Statement](#components)
3. [Motivation](#Motivation)
4. [Installation](#installation)
5. [File Descriptions](#files)
6. [Acknowledgements](#licensing)
7. [Results](#results)
### 1. Project Overview<a name="overview"></a>

* The program used to create the data simulates how people make purchasing decisions and how those decisions are influenced by promotional offers.

* Each person in the simulation has some hidden traits that influence their purchasing patterns and are associated with their observable traits. People produce various events, including receiving offers, opening offers, and making purchases.

* As a simplification, there are no explicit products to track. Only the amounts of each transaction or offer are recorded.

* There are three types of offers that can be sent: buy-one-get-one (BOGO), discount, and informational. In a BOGO offer, a user needs to spend a certain amount to get a reward equal to that threshold amount. In a discount, a user gains a reward equal to a fraction of the amount spent. In an informational offer, there is no reward, but neither is there a requisite amount that the user is expected to spend. Offers can be delivered via multiple channels.

* The basic task is to use the data to identify which groups of people are most responsive to each type of offer, and how best to present each type of offer.



### 2. Problem Statement<a name="components"></a>

* Exploring the Starbuck’s Dataset how people make purchasing decisions and how those decisions are influenced by promotional offers.

* There are three types of offers that can be sent: buy-one-get-one (BOGO), discount, and informational.

* I’m going to analyze Starbuck’s Dataset for example: General overview of Starbucks customers including there ages , income and genders.

* Build model to Predict if a customer would view then complete an offer or no. 


### 3. Motivation<a name="Motivation"></a>
- This project to complete udacity Data Scientist Nanodegree.
- Found dataset so interesting how people make purchasing decisions and how those decisions are influenced by promotional offers.

### 4. Installation<a name="installation"></a>

 This project was written in Python, using Jupyter Notebook. The relevant Python packages for this project are as follows:

- pandas
- numpy
- math
- json
- matplotlib
- seaborn
- sklearn.model_selection (train_test_split module)
- sklearn.preprocessing (StandardScaler )
- tensorflow

### 5. File Descriptions<a name="files"></a>

The data is contained in three files:

* portfolio.json - containing offer ids and meta data about each offer (duration, type, etc.)
* profile.json - demographic data for each customer
* transcript.json - records for transactions, offers received, offers viewed, and offers completed

Here is the schema and explanation of each variable in the files:

**portfolio.json**
* id (string) - offer id
* offer_type (string) - type of offer ie BOGO, discount, informational
* difficulty (int) - minimum required spend to complete an offer
* reward (int) - reward given for completing an offer
* duration (int) - time for offer to be open, in days
* channels (list of strings)

**profile.json**
* age (int) - age of the customer 
* became_member_on (int) - date when customer created an app account
* gender (str) - gender of the customer (note some entries contain 'O' for other rather than M or F)
* id (str) - customer id
* income (float) - customer's income

**transcript.json**
* event (str) - record description (ie transaction, offer received, offer viewed, etc.)
* person (str) - customer id
* time (int) - time in hours since start of test. The data begins at time t=0
* value - (dict of strings) - either an offer id or transaction amount depending on the record

### 6. Acknowledgements<a name="licensing">

This project was completed as part of the [Udacity Data Science Nanodegree]. The dataset used in this project contains simulated data that mimics customer behavior on the Starbucks rewards mobile app. [Starbucks® Rewards program: Starbucks Coffee Company](https://www.starbucks.com/rewards/).

### 7. Results<a name="results"></a>
The main observations of the code are published on medium [here](https://medium.com/@aalboughbar/starbuck-s-data-analysis-capstone-project-4955e4f217d)

