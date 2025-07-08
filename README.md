# <ins>vestas-internship
# Internship Log for Avneet Kaur Anand at Vestas, Chennai


## Week 1

<ins> Onboarding and Introduction </ins>
- Met with the Plant Monitoring and Reliability team.
- Set-up company credentials and tools.
- Meeting with manager and mentors:
    - **Mr. Mallikarjun Narayanpur**, <manaa@vestas.com>, Manager, Sub-Module Owner for Plant Monitoring & Reliability
    - **Dr. Rohit Gunerkar**, <rohgn@vestas.com>, Mentor, Lead Engineer in Plant Monitoring & Reliability
    - **Mr. Manik Singh**, <mksgh@vestas.com>, Mentor, Data Scientist in Plant Monitoring & Reliability
- Completed company learning modules on:
    - Welcome to Vestas
    - History, Vision, and Values
    - An Interactive Experience: What We Do at Vestas
    - Navigating our Matrix Organisation
    - Inclusion Powers the Solution
    - Safety Awareness Induction
    - Training on Psychological Safety
    - Code of Conduct
    - Anti-Sexual Harassment
    - Activity Based Working
    - Sustainability

<ins> Skill Development </ins>
- Started crash course in Machine Learning.
- Shadowed Mr. Mallik in official meeting.
- Introduction to software used ---
- Meeting with **Mr. Navin B**, <nabib@vestas.com>, Lead P&C Business Partner for APAC. Discussed:
    - The work culture at Vestas
    - Goals for my internship
    - Development of soft and technical skills expected over the period of next 2 months
    - Insights on future opportunities.
- Introduction and meeting with **Mr. Rahul Jacob**, <rjabw@vestas.com>, Head of Product and Customer Operatons. Discussed his work with the Scipher platform and team.


## Week 2

<ins> Monday </ins>
- Continued with ML crash course.
- Did research on the following models for catching anomalies in data:
    - Support Vector Machine (Hyper Plane Model)
    - Isolation Forest (Tree Model)
    - Autoencoder (Neural Network Model)
- Learnt about **autoencoder** in detail to apply it in anomaly detection in time series. Learnt:
    - Architecture of autoencoder
    - Loss function of autoencoder
    - Types of autoencoder
    - Previewed sample python code for autoencoder

<ins> Tuesday </ins>
- Meeting with Dr. Rohit to discuss non-linear regression models to analyze power quality data:
    - Touched up on autencoders and how they can help in our case of anomaly detection.
    - Discussed starter project for analysing anomalies in time series.
    - Assigned work for developing standard python templates for:
        - Data statistics
        - Autoencoder
        - Decision tree

<ins> Wednesday </ins>
- Visited the **Oragadam Factory** with:
    - **Mr. Sahil Bundela**, <sabne@vestas.com>, Data Engineer in Plant Monitoring & Reliability
    - **Dr. Monojit Das**, <moida@vestas.com>, Assistant Lead Engineer in Plant Monitoring & Reliability
    - **Mr. Ganesh Sukumar**, <gasku@vestas.com>, Data Scientist in Plant Monitoring & Reliability
- Took a tour of the plant, led by **Mr. Manikandan Eswaran**, <mkdes@vestas.com>, Sr. PEX & Project Engineer in Oragadam Nacelles.
- Explored:
    - Training room: used to familiarize new employees with the equipment.
    - VSM (Value Stream Mapping) room.
    - DMM (Daily Management Meeting) board: learnt about their organisation and division of tasks.
    - Drive Train and Assembly Line.
- Learnt about:
    - The scale of the factory.
    - Production and transportation costs.
    - Yearly capacity for production.
    - Supply chain of materials.
    - Practicalities of the 2 MW and 4 MW turbines.
    - Manufacturing and testing process and their time period.
- After coming back, began looking for a base for Autoencoder:
    - Browsed GitHub repositories and GeeksforGeeks for sample code.
    - Looked at other ML models that could be applied to the problem.

<ins> Thursday </ins>
- Started working on Autoencoder to predict output of given data (excel sheet):
    - Adapted sample code to `Python 3.13.5` (sample code not supported by `Python 3.13.5`).
    - Coded a basic autoencoder with 4 inputs and 1 output and trained it on randomly generated data.
    - Employed the basic autoencoder to train it on the excel sheet of data.
- Participated in company fire drill.

<ins> Friday </ins>
- Completed autoencoder template, [`autoencoder_template.ipynb`](./autoencoder_template.ipynb), began training it on different data sets.
- Completed a template for finding the basic data statistics in a data file and their visualizations, [`statistics_template.ipynb`](./statistics_template.ipynb).
- Started working on decision-tree model, [`census_income_decision_tree.ipynb`](./census_income_decision_tree.ipynb), for the given data set: [`census income data`](./census%20income%20data/)


## Week 3

<ins> Monday </ins>
- Meeting with Dr. Rohit, discussed:
    - Progress up until now and next steps
    - How to make the autoencoder better
    - Data visualizations required
- Continued working on autoencoder:
    - Began testing on other sheets in the data file.
    - Tried to improve performance by adding more layers in the neural network, didn't work.

<ins> Tuesday </ins>
- Tried to fix the autoencoder by changing learning rate and epochs to fit the larger number of layers.
- When that didn't work, reverted back to the original (most efficient) model.
- Began analysing the visualizations to see where the model was going wrong with its predictions.

<ins> Wednesday </ins>
- Worked on visualizing autoencoder predictions.
- Explored GeeksForGeeks to understand R<sup>2</sup> in regression models like this one and how to visualize it.
- Completed working on testing the autoencoder, [`autoencoder_testing.ipynb`](./autoencoder_testing.ipynb). Noticed some inconsitency in results; contacted Dr. Rohit and Mr. Manik and scheduled a meeting to discuss the issue.

<ins> Thursday </ins>
- Attempted to make the autoencoder model work with more consistency.
- Meeting with Dr. Rohit and Mr. Manik to discuss inconsistency in results.
- Made a list of improvements to be made and also took up recommendation of looking in AutoML models.

<ins> Friday </ins>
- Studied up on AutoML models


## Week 4

<ins> Monday </ins>
- Continued studying AutoML models
- Meeting with Dr. Rohit and Mr. Manik to discuss progression in work.
    - Discussed current autoencoder: [`autoencoder_testing.ipynb`](./autoencoder_testing.ipynb).
    - Assigned work on in-depth EDA of data, began modifying `statistics_template.ipynb` for that.
    - Discussed future steps to complete project.

<ins> Tuesday </ins>
- Finished working on `statistics_template.ipynb`, renamed it [`data_eda_template.ipynb`](./data_eda_template.ipynb)
