# The Programme for International Student Assessment (PISA) Data Exploration
## by Shaheer Khan

## Dataset

> The dataset being analyzed is gathered from PISA, which is a survey depicting students' skills and knowledge as they approach the end of compulsory education. It is not a conventional school test. This test focuses on how well prepared are students for life beyond school. Unlike many conventional tests which evaluate how well students have learned the school curriculum. The PISA test evaluates the more practical and real life scenario of a student's journey through life after school.

> Around 510,000 students in 65 economies took part in the PISA 2012 assessment of reading, mathematics and science representing about 28 million 15-year-olds globally. Of those economies, 44 took part in an assessment of creative problem solving and 18 in an assessment of financial literacy.

Feature Engineering was done to produce:
> Overall Literacy - *Engineered Variable* (Quantitative)
> Average Learning Time in mins per Week - *Engineered Variable* (Quantitative)

Following Variables were used in the analysis:
* Grade - Grade compared to modal grade in country (Quantitative).
* Overall Literacy - *Engineered Variable* (Quantitative)
* Average Learning Time in mins per Week - *Engineered Variable* (Quantitative)
* Perseverance Give up easily - (Categorical)
* Internet Connection - (Categorical)
* Highest Educational Level of Parents - (Categorical)
* Highest Parental Occupational Status - (Quantitative)
* Grade Repeated (class repeated) - (Categorical)

## Summary of Findings

> Mexico has the most number of students who took the PISA survey while Liechtenstein has the least number of students. China has students who have the highest overall literacy compared to other nations, whereas Jordan has students who have the lowest overall literacy.

> Grade variable was analyzed which is from a scale of -3 to 2 and it was found that majority of students have a value of 0 which means that they are at the country's modal grade threshold. I will be using this variable in the explanatory presentation.

> Overall Literacy's distribution seems normally distributed with the peak at 500 mark. This variable will be the dependent variable for majority of the analysis. I will be using this variable in the explanatory presentation.

> Average Learning Time (mins/week) had alot of outliers. The data was cleaned after which the Average Learning Time's distribution seems normally distributed with the peak at around 200 mark. I will be using this variable in the explanatory presentation.

> Highest Parental Occupational Status' distribution shows that it is almost evenly spread out with one peak at 20-30 interval. I will be using this variable in the explanatory presentation.

> Highest Parental Education in years, this variable's distribution is left skewed with the peak at 15-17.5 years interval. I will be using this variable in the explanatory presentation.

> Computer Use in minutes per week, this variable's distribution is right skewed with the peak at 25-50 mins interval.

> There are more students in OECD nations than non-OECD ones.

> There are marginally more female students than male students who were surveyed for PISA.

> Analysing the Perseverance variable, majority of students do not give up easily. Though as the perseverance level decrease (giving up ability increase) resulting in students' overall literacy to decrease. I will be using this variable in the explanatory presentation.

> Majority of students surveyed have desktop and/or portable laptop at home and they use it. Those students who had a desktop and/or a portable laptop at home did far better in overall literacy compared to students who did not have them.

> Majority of students surveyed do not have a tablet computer at home. Those who have or do not have a tablet computer at home did fairly the same in terms of overall literacy.

> Majority of students surveyed have internet connection and they use it. Those students who have internet connection and use it did far better in overall literacy compared to students who did not have it or to those who did have it but don't use it. I will be using this variable in the explanatory presentation.

> Majority of students surveyed have video games console at home and they use it 

> Majority of students surveyed have cellphone at home without internet and they use it.

> Majority of students have cellphone at home with internet and they use it.

> Majority of parents have atleast passed ISCED 5A or 6 level. As the parent's highest educational levels increase, so does the students' overall literacy level. I will be using this variable in the explanatory presentation.

> Majority of students did not repeat a grade and students who did not repeat a grade did far better in overall literacy compared to students who did repeat a grade. I will be using this variable in the explanatory presentation.


## Key Insights for Presentation

> There are more number of students who repeated a grade given they have and use an internet connection compared to the students who either have internet connection but didn't use it or those who do not have internet connection altogether. Those students who had and used internet connection tend to have the least amount of average learning time regardless of having repeated or not repeated a grade in comparison to the students who either have internet connection but didn't use it or those who do not have internet connection altogether. Students who had no internet connection had spent on average more learning time compared to those students who had internet connection and do not use it or those who have internet connection and use it.

> Regardless of the students having repeated a class or not, they have higher overall literacy given they had internet connection and used it as compared to those who had internet connection but didn't use it or those who didn't have internet connection at all.

> Students with parents' who have high education level tend to have higher overall literacy given those students did not repeat a grade. As for those students who did repeat a grade similar pattern is visible.

> Students who didn't give up easily tend to have the highest overall literacy given they didn't repeat a grade/class. For the students who repeated a grade, similar downwards staircase pattern is found from the left most bar to the right most bar depicting that as students give up easily the lower the overall literacy. The count of students giving up easily given they repeated a grade is much less than those who give up easily given they didn't repeat a grade.

> As the Parents' occupational status increase so does the student's overall literacy, with that students' modal grades have stayed the same as the country's modal grade with few of the grades being above the modal grade. Whereas, as the parents' occupational status decrease so does the student's overall literacy, with that more and more students are below the modal grade.

> As the Parents' occupational status increase so does the student's overall literacy, with that less and less students have repeated a class. The right side of the plot has majority of students who did not repeat a grade whereas, as the parents' occupational status decrease so does the student's overall literacy, with that more and more students repeated a grade.

> As the Parents' occupational status increase so does the student's overall literacy, with that more and more students have access to internet. The right side of the plot has majority of students using internet whereas, as the parents' occupational status decrease so does the student's overall literacy, with that less and less students have access to internet.


## Resources Used

[1] http://www.oecd.org/pisa/pisaproducts/MS12_StQ_FORM_UH_ENG.pdf

[2] http://www.oecd.org/pisa/pisaproducts/CBA12_cogn_codebook.pdf

[3] http://www.oecd.org/pisa/pisaproducts/CBA12_cogs_codebook.pdf

[4] https://stackoverflow.com/questions/38085547/random-sample-of-a-subset-of-a-dataframe-in-pandas

[5] https://towardsdatascience.com/understanding-boxplots-5e2df7bcbd51

[6] https://stackoverflow.com/questions/34782063/how-to-use-pandas-filter-with-iqr

[7] https://gist.github.com/fomightez/bb5a9c727d93d1508187677b4d74d7c1

[8] https://stackoverflow.com/questions/3777861/setting-y-axis-limit-in-matplotlib

[9] https://seaborn.pydata.org/tutorial/color_palettes.html

[10] https://stackoverflow.com/questions/3899980/how-to-change-the-font-size-on-a-matplotlib-plot

[11] https://cduvallet.github.io/posts/2018/11/facetgrid-ylabel-access

[12] https://www.oecd.org/pisa/sitedocument/PISA-2015-Technical-Report-Chapter-9-Scaling-PISA-Data.pdf

[13] https://www.oecd.org/pisa/pisaproducts/PISA12_stu_codebook.pdf

[14] http://www.oecd.org/pisa/pisaproducts/PISA%202012%20framework%20e-book_final.pdf

[15] http://www.oecd.org/pisa/aboutpisa/

[16] http://www.oecd.org/pisa/pisaproducts/PISA-2012-technical-report-final.pdf

[17] https://en.wikipedia.org/wiki/International_Standard_Classification_of_Education

[18] https://stackoverflow.com/questions/5552555/unicodedecodeerror-invalid-continuation-byte

[19] https://largescaleassessmentsineducation.springeropen.com/articles/10.1186/s40536-020-00086-x#Sec38

[20] https://www.oecd.org/pisa/sitedocument/PISA-2015-Technical-Report-Chapter-16-Procedures-and-Construct-Validation-of-Context-Questionnaire-Data.pdf

[21] http://uis.unesco.org/sites/default/files/documents/international-standard-classification-of-education-isced-2011-en.pdf

[22] https://towardsdatascience.com/getting-more-value-from-the-pandas-value-counts-aa17230907a6#:~:text=value_counts()%20displaying%20the%20NaN,the%20dropna%20parameter%20to%20False%20.&text=We%20can%20easily%20see%20that,null%20values%20in%20the%20column.

[23] https://medium.com/@danberdov/dealing-with-missing-data-8b71cd819501#:~:text=As%20a%20rule%20of%20thumb,the%20variable%20should%20be%20considered.

[24] https://thispointer.com/pandas-drop-rows-from-a-dataframe-with-missing-values-or-nan-in-columns/

[26] https://dev.to/thalesbruno/subplotting-with-matplotlib-and-seaborn-5ei8

[27] https://stackoverflow.com/questions/25239933/how-to-add-title-to-subplots-in-matplotlib

[28] https://www.kaggle.com/residentmario/subplots