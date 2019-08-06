# Minor-Project

Project title: Finding the liklihood of a disease based on a patient's data using data mining.

Description:-

Our project aims to provide the liklihood of a disease that might be contracted by a person after analysing his or her medical data. It is to be noted that the functioning of our project seems to perform a predictive analysis. But in fact, our project just provides a vague estimation that a given person is very likely to suffer from a certain disease, let's say diarrhoea, instead of diseases like malaria.

For providing such functionality to our project, we are using Apriori algorithm. It is an algorithm which is used to implement association rule mining, which is a data mining technique used to find underlying relations among seemingly unrelated data items.

On the basis of tasks and domain, we can divide our project into various modules:-

1. Data Module

-----> This module functions around the data that we are working on.
-----> It has two aspects: a) Data Science b) Data Mining.

The data science aspect involves data cleaning, data preprocessing and data visualization. The first two steps are implemented before initiating association rule mining. The data visualization step will be implemented throughout the project at few times to aid in analyzing the results.

The data mining aspect involves applying the apriori algorithm to a given dataset that has been processed already. The association rules will be stored in a python data structure (lists or dictionary) for accessing them in further usage, since we cannot do the processing every time our software is built. The use of a data structure will also allow us to analyze different datasets and further refine our association rules.

2. GUI Module

---------> This module involves on providing a user interface.
---------> The GUI is for 2 kinds of users: a) Doctors b) General Public

Our project is mainly focused to be used by the doctors. Based on a patient's medical  data, the software would suggest an initial approach to the doctor for diagnosing the disease which has the higher likelihood. Also some few additional details about the disease, such as the cause, geographical data, tests recommended, ratio of population etc, along with a visualisation of the patient's data in comparison with the population data will be provided.

It is to be noted that the doctor may or may not follow the suggestions made by the software. Our project has the primary focus of consultation, not direction. In addition to that, a feedback form is also provided to the user regarding the suggestion provided.

The structure and functioning of the gui for the general public will be similar to one for doctors, except for the fact that instead of showing recommended tests our software would provide the necessary precautions to take to the user.  

The user will only interact with the GUI module. He/she will have nothing to do with the Data module.
