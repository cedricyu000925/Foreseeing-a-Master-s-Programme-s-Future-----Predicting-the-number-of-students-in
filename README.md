# {Data Analytics Training Bootcamp Project}

# [Foreseeing a Master's Programme's Future-----Predicting the number of students in future academic years]

# INTRODUCTION
This is my first data project, which I completed after I finish my data analytics training bootcamp. The goal of this project is to predict the number of students admitted in a Master's degree programme in the next few years from the moment I started this project. 
I also attempted to predict the ratio of male and female students in the future in the future as well. The Master's Degree Programme is about theories related to linguistics. Students in this programme are mainly from educational sectors, mostly teachers or private English tutors.

The project has two objectives. I would like to find out:

  **1) How many students are the programme going to admit in the next few years? Will the number of students admitted be impacted by potential job vacancy and job market in the educational sector? Or is there any other factor in the play as well?**
  
  **2) Will the programme admit more female students and less male students? Or maybe is the other way around?**
  
After I performed the analysis, I found out that the job market and the number of job vacancies out there were not very essential in affecting the performance of admission. On the other hand, admission quotas imposed by the Faculty is the biggest factor of impacting the number of students the programme has admitted. My prediction indicate that less male students will be admitted in the future.

# Background
The data used for this project comes from a real professional setting. It came from the current student list (by the time I am doing this project) and the alumni namelist of a Master programme I am currently working for. The dataframe consists only ID number (for convenience sake when I have to know the number of data entries I made), the cohort that particular student was in, and their gender. This measure was implemented to make sure no personal information that could identify an individual person was leaked, especially if those information were not essential to the analysis.

Every year, the Programme Office was required to submit an admission summary that lists out the number of sstudents admitted, the number of male and femaale students admitted, and their occupation when applying for admission. Therefore, there is a need professionally at my workplace to predict these statistics for future academic years.

In 2023, the Faculty started to impose an admission quota, to demand our programme to admit a certain nmumber of students, which that quota actually doubles the amount of students we have admitted in the previous admission exercise. To a certain extent, this had put not only certain pressure in out gatekeeping mechanics of allowing candidates with the best potential into our programme, but also the fact that we had a hard time allocating enough amount of teachers, tutors and assignment markers to maintain the operational needs of our programme. It would be very beneficial if a prediction model can be successfully developed in order to know as soon as possible how the resources at our hand can be allocated to solve the challenges ahead of us... especially when we do not know the reasons behind these admission quotas  imposed by the Faculty.

# Content
The data in dataframe CSV file was obtained at my full-time deskjob. The CSV file contains of the cohort a particular student was in, with the number srepresenting the academic year there were in, and FT (full-time) or PT (part-time) as their study mode. 
The last column contains the gender of each student, either in M (male) or female (F).

The "Cohort Trend Analysis" file is a bar chart I plotted using Python to give myself a more easily comprehensible view of what were the changes of the number of students admitted in this particular Master's degree programme all along the years.

The "Prediction version 2" file is a Python command that, using the abovementioned dataframe, to make the prediction. I used different models to train the machine and predict what I would like to see.
