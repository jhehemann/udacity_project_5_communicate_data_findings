# (Dataset Exploration Title)
## by (your name here)


## Dataset

Provide basic information about your dataset in this section. If you selected your own dataset, make sure you note the source of your data and summarize any data wrangling steps that you performed before you started your exploration.

> The dataset I will explore and analyze in this project is the PISA dataset. The following Note from the udacity website describes the dataset best: "PISA is a survey of students' skills and knowledge as they approach the end of compulsory education. It is not a conventional school test. Rather than examining how well students have learned the school curriculum, it looks at how well prepared they are for life beyond school.
Around 510,000 students in 65 economies took part in the PISA 2012 assessment of reading, mathematics and science representing about 28 million 15-year-olds globally. Of those economies, 44 took part in an assessment of creative problem solving and 18 in an assessment of financial literacy."


## Summary of Findings

Summarize all of your findings from your exploration here, whether you plan on bringing them into your explanatory presentation or not.

### Univariate exploration
> All the numeric variables are normally distributed. The only categorical data type is the immigration status. The data shows that roughly 90% of the students are native, 5% have an immigration status of 'First-Generation' and 5% of 'Second-Generation'.
> There were no unusual distributions in the features I investigated. 

### Bivariate exploration
> Students that have a immigration status of 'First-Generation' have the lowest sense of belonging to their school (`BELONG`) amongst all three immigration stati (`IMMIG`). This might be explained by the fact that the students themselves immigrated and switched school from the home country to the new country. On the other side most of the students in the second-generation immigration group have been attending school from class one as the native students. This might lead to the higher sense of belonging to the school for those groups, which is shown in the chart.

> The barplot shows that better grades (`GRADE`) correlate with a higher sense of belonging to the school (`BELONG`). The uncertainty whiskers at the grade values of 2.0 indicate that there might be students that have a less sense of belonging to the school even less than students with less than -1.0 in the grade values. This seems to be counterintuitive. It could be explained in the following way: Some students that are extrordinary good in school and way better than their classmates, might feel they do not belong to the school, because it does not fit their capabilities.

> The violine plots and the boxplots for the comparism between `IMMIG`(Immigration status) and `ESCS` indicate that the students with first generation immigration status have most of the index scores distributed between 0.5 and 1 whereas the native students and second generation immigration students have their maximum of indices distributed at an index between -0.5 and -1. This leads to the conclusion that first generation immigrants have a higher chance to have a higher economic, social and cultural status than native students or second generation immigrants. 

> Students with second-generation immigration status (`IMMIG`) have on average better grades compared to modal grades in the country (`GRADE`) than the native and the first-generation immigration students, whereas the difference to the native students is very little. 

> The mean international grade (`ST01Q01`) of the native immigration group (`IMMIG`) is higher than the other two. But all of them are very close. 

> The charts show that the native students (`IMMIG`) are on average less wealthy (`WEALTH`). In the boxplot the median wealth of the native students is lower than of those with immigration background. 

> There is a quite strong positive correlation between a students wealth (`WEALTH`) and the economic, social and cultural status (`ESCS`).

> The plots between `GRADE` (grade compared to modal grade in country) and `ESCS` (Index of economic, social and cultural status) indicates a slightly positive correlation. 

### Multivariate exploration

> The bivariate exploration showed that students with the immigration status of 'First-Generation' have on average the lowest sense of belonging to their school amongst all three `IMMIG` groups. By looking at the sense of belonging to school separated by grade, the data reveals that for the grade values of -1.0 and less the sense of belonging to school is on average much lower for the second-generation immigration students than for both the first-generation immigration and the native students. For the grades of 1.0 and more the sense of belonging to school is on average even higher for second-generation immigration students. It seems that beeing an immigrant in the second generation in a country the sense of belonging to school is strengthened in either direction, for worse grades to a lower sense of belonging to school and for better grades to a higher sense of belonging to school. 

> The bivariate exploration showed that the native students are on average less wealthy. In the boxplot the median wealth of the native students was lower than of those with immigration background. The multivariate analysis of all three features showed that the students with immigration status either First-Generation or Second-Generation are located slightly more to the top right of the plot. This leads to the assumption that students with immigration background are indeed on average wealthier and have a higher economic, social and cultural status. This is a finding that is rather counter intuitive. The effects are quite little. 

> It is surprising that not the first-generation immigration students have a lower sense of belonging to school, but the second-generation students. 
> Moreover it is surprising that students with immigration background are on average wealthier and have a higher economic, social and cultural status. 




## Key Insights for Presentation

Select one or two main threads from your exploration to polish up for your presentation. Note any changes in design from your exploration step here.

> In my presentation I want to emphazise the fact that students with immigration background in the second-generation have a much less sense of belonging to school than the native students or students with first-generation immigration status when they perform less than the grades most appearing in the country. 

1. I will introduce the study and present the research question "Does the immigration status have an influence on the sense of belonging to school?"
2. I will present the distribution of immigration groups within the study in a pie chart.
3. I will show the mean sense of belonging to school for the different immigration groups which indicates that the first-generation immigration students have a less mean sense of belonging to school.
4. In the end I will show the multivariate plot of all three features (immigration status, sense of belonging to school and grade compared to modal grade in country), where it is revealed that for the grade values of -1.0 and less the sense of belonging to school is on average much lower for the second-generation immigration students than for both the first-generation immigration and the native students
5. Conclusion and suggestions


## Sources
- https://video.udacity-data.com/topher/2019/April/5ca78b26_dataset-project-communicate-data-findings/dataset-project-communicate-data-findings.pdf