# Data analysis
This repository concentrate in data analysis and a prediction model. The dataset
rows describing different jobs IDs.

__The jobs' features are:__
* JobId – a numerical (key) index
* JobTitleId– the job title as explained above.
* CategoryId – The category as explained above
* State – the (short) name of the state in which the job is published.
* DescriptionLength – The length of the text of the job description.
* EducationLevel – A numerical value representing the educational level required
 for this job.


__The jobs' target variables are:__
* Clicks – the amount of times job seekers clicked on the ad on the job and
viewed it.
* Applicants – the amount of time a job seeker who viewed a job continued with
the application process to apply for the job.


## The notebook structure:
1. __Question 1__ - The first part is about asking some questions on the data
for better understanding it through exploring the data.
2. __Question 2__ - The second part concentrate on the data integrity issues. We
will try detect all those issues by following an organized procedure for finding
issues in a logical way.
3. __Question 3__ - The last part will use all the knowledge we have gained in
the previous parts, to build 2 prediction's models. Those models will help us
predict the target variables of two new jobs, which we only know their features.
