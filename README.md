# Data_Visualization
PISA 2012 - Exploratory and Explanatory Data Visualization

This report is the exploratory part of a data visualization project. The report explores the PISA 2012 dataset that can be found [here](https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud507/pisa2012.csv.zip&sa=D&ust=1551376898573000). Since the PISA 2012 dataset is a complex huge dataset, this report is going to focus on specific variables related to the evaluation of the mathematics level of students in three countries: Finland, United Arab Emirates, and Unites States of America.

An explanation of the variables used:

- COUNTRY: 3 countries (Finland, United Arab Emirates, United States of America)
- GENDER: 2 genders (Female, Male)
- ENJMATH: answers to "Do you (the student) enjoy mathematics?" 4 answers (Strongly disagree, Disagree, Agree, Strongly agree)
- PARENJMATH: answers to "Do your parents (the student's parents) enjoy mathematics?" 4 answers (Strongly disagree, Disagree, Agree, Strongly agree)
- WEALTH: a float that is calculated by number of questions in the PISA 2012 dataset to measure wealth of the family of the student
- TEACHERCLASSMANAG: a float that is calculated by number of questions in the PISA 2012 dataset to measure class management by the teacher
- COGNITIVEACTIV: a float that is calculated by number of questions in the PISA 2012 dataset to measure the cognitive activation of mathematics by the student
- TEACHSTUDRELAT: a float that is calculated by number of questions in the PISA 2012 dataset to measure the relationship between the teacher and the student
- PV1MATH, PV2MATH, PV3MATH, PV4MATH, PV5MATH: 5 plausible values to the mathematical literacy of the students

The main findings of this report are:

The mathematical literacy of Finland in highest between the countries of interest, then USA, and UAE is lowest. The mathematical literacy is positively correlated to congnitive activation of mathematics by students. That relationship holds true when observed per country. Finally, both teacher's class management and teacher-student relationship are positively correlated to student's cognitive activation with a specific rules. Thus, we can recommend working on increasing the teacher's class management efforts and a better teacher-student relationship in order to increase the student's cognitive activation of mathematics, which in return increases the mathematical literacy of the students.

References used:

http://www.oecd.org/pisa/pisaproducts/CBA12_stu_codebook.pdf
http://www.oecd.org/pisa/pisaproducts/PISA-2012-technical-report-final.pdf
https://seaborn.pydata.org/tutorial/color_palettes.html
https://github.com/mwaskom/seaborn/issues/867
https://stackoverflow.com/questions/30009948/how-to-reorder-indexed-rows-based-on-a-list-in-pandas-data-frame
https://matplotlib.org/gallery/text_labels_and_annotations/text_fontdict.html
