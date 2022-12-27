# PISA 2012 Dataset
## by Abdessalam Dai


## Overview

> This is the third project in Udacity's Nanodegree Program for Data Analysis. In this project, I used Python (Matplotlib and Seaborn) to perform an exploratory data analysis and then produced a presentation with explanatory plots to convey my findings. (Finalized on 27 December 2022).

## Dataset

> Download the compressed dataset (~300 MiB) from [here](https://s3.amazonaws.com/udacity-hosted-downloads/ud507/pisa2012.csv.zip).

> PISA is a survey of students' skills and knowledge as they approach the end of compulsory education. It is not a conventional school test. Rather than examining how well students have learned the school curriculum, it looks at how well prepared they are for life beyond school.

> Around 510,000 students in 65 economies took part in the PISA 2012 assessment of reading, mathematics and science representing about 28 million 15-year-olds globally. Of those economies, 44 took part in an assessment of creative problem solving and 18 in an assessment of financial literacy.

> These are the columns that helped me to determi how environmental factors affect learning success:

>- **PV1MATH**: Plausible value 1 in mathematics
- **PV2MATH**: Plausible value 2 in mathematics
- **PV3MATH**: Plausible value 3 in mathematics
- **PV4MATH**: Plausible value 4 in mathematics
- **PV5MATH**: Plausible value 5 in mathematics
- **PV1READ**: Plausible value 1 in reading
- **PV2READ**: Plausible value 2 in reading
- **PV3READ**: Plausible value 3 in reading
- **PV4READ**: Plausible value 4 in reading
- **PV5READ**: Plausible value 5 in reading
- **PV1SCIE**: Plausible value 1 in science
- **PV2SCIE**: Plausible value 2 in science
- **PV3SCIE**: Plausible value 3 in science
- **PV4SCIE**: Plausible value 4 in science
- **PV5SCIE**: Plausible value 5 in science
- **WEALTH**: Wealth
- **CNT**: Country
- **ST04Q01**: Gender of student
- **HISCED**: Highest education level parents
- **TIMEINT**: Time of computer use (mins)
- **ST11Q01**: At Home - Mother
- **ST11Q02**: At Home - Father


## Summary of Findings

> Male students typically perform better on math tests than female students do, and the opposite is true for reading test scores. The science scores of male and female students, however, are not significantly different. Students who have at least one parent at home perform better in math, science, and reading than those who do not. Asian countries appear to have slightly higher scores. Furthermore, there is a strong correlation between math and science (r=0.92), reading and science (r=0.89), and math and reading (r=0.87).
