## Project: Why don't people show up on their medical appointments?
What **factors** are important to **predict whether a patient will show up for their scheduled appointment or not**?  
We will find out during this project.

## Background
For one reason or another, people sometimes don't show up for their **medical appointments** which could cause the waste of the medical resources and other negative impact.  


## Date created
- README file: Apr-24-2019

- Project: Apr-20-2019

## Install
To run this project, you need:
- Install [Python 3](https://www.python.org/downloads/) and [Anaconda](https://www.anaconda.com/distribution/)

- Install [Jupyter Notebook](https://jupyter.org/install)

- Install `pandas`, `Numpy` and `matplotlib`  using Anaconda or pip.

## Dataset
The [dataset](https://s3.amazonaws.com/video.udacity-data.com/topher/2018/July/5b57919a_data-set-options/data-set-options.pdf) we used collected information from **100k medical appointments in Brazil** and is focused on the question of whether or not patients show up for their appointment.

_*The original source is on [Kaggle](https://www.kaggle.com/joniarroba/noshowappointments)._


## Files used

- noshowappointments.csv


## Questions to explore

- Did waiting time influence the show-up?
- Did Appointment day influence the show-up?
- Did the gender of patients influence the show-up?
- Did the age of patients influence the show-up?
- Did the welfare program influence the show-up ?
- Did the types of disease influence the show-up ?
- Did the SMS influence the show-up ?
- Were there people who missed the appointment more than once?



## Conclusions
### Results

**There are a few influencing factors that may related to missing appointment :**  

- **Appointment time**  
  Appointments that were made in weekends has a higher show-up rate compared with in weekdays.

- **Waiting time**   
 It seems that the longer waiting time was, the easier people were going to miss the appointment. Unfortunately, receiving SMS was not likely to help people show up on the appointment.

- **The age of patients**  
Teenagers and young adults are more likely to miss the appointment than children and old people.

- **The welfare program**  
People who enrolled in Brazilian Welfare Program were more likely to miss the appointment compared with people who don't have financial support.

- **Types of disease**  
The people who have Hypertension and Diabetes are more likely to show up in time to the appointment.

### Limitations
**There are a few limitations with our data:**  

- No inferential statistics

- More details is needed

- Lack of numerical data


## Credits
The data files and programming instructions are provided by Udactiy's [Data Analyst  Nanodegree Program](https://eu.udacity.com/course/data-analyst-nanodegree--nd002). :bowtie:
