# College-Scorecard-Data-Analysis

This project aims to conduct a high level survey of the US Postsecondary Education System as of the academic year 2017 - 2018.<br>
We will try to answer questions such as:
- What makes for a good or a bad SAT/ACT Score?
- Does the admission rate of an institution affect the salary of its faculty?
- Which degrees are most commonly conferred by schools?
- Is there a balance between Private and Public Schools?
- How much revenue do schools generate per student on average? <br>

We will also aim to discover certain patterns that emerge from the data.

## Data
The Data used here was gathered under the [College Scorecard Project](https://collegescorecard.ed.gov/) by the U. S. Department of 
Education. <br>
The College Scorecard Project was inititated in a bid to increase transparency, putting the power in the hands of students and families 
to compare how well individual postsecondary institutions were preparing their students to be successful. <br>
The data is downloaded programatically in Python from [Data.gov](https://www.data.gov/) which can be downloaded from this 
[link](https://catalog.data.gov/dataset/college-scorecard). <br>
The most recent data - for the Academic Year from Fall '17 - '18 is chosen for the analysis. Further, a subset of the entire data is 
focussed on.

## Dependencies
Following are the Python (v3.6) Libraries used for the analysis:
- Numpy v1.16.2
- Pandas v0.24.2
- Requests v2.22.0
- Matplotlib v3.0.3
- Seaborn v0.9.0 

## Analysis
The analysis is structured. In that, a question and answer format is followed throughout.<br> First a question is posed; 
then using Python and its Data Processing libraries informative Visualizations and relevant Summary Statistics are generated
that try to answer the question. Initially we will stick to answering questions about a single variable at a time, followed by two at a 
time and finally broaden our perspective to  consider interaction between three or more variables.<br>
The __IPython Notebook__ `index.ipynb` can be downloaded from the repo 
[here](https://github.com/dhavalpotdar/College-Scorecard-Data-Analysis/blob/master/index.ipynb)
or previewed in a rendered format 
[here](https://nbviewer.jupyter.org/github/dhavalpotdar/College-Scorecard-Data-Analysis/blob/master/index.ipynb). <br>
A __Presentation__ on some of the major findings of the analysis can be viewed 
[here](https://dhavalpotdar.github.io/College-Scorecard-Data-Analysis/).

## Conclusions
Here are some of the interesting observations and trends uncovered, as well as answers to the questions posed. <br>
#### General 
1. The State of California has by far the largest number of institutes (714). Of the Commonwealth/Territories only the District of 
Columbia and Puerto Rico have a significant number of institutes. The rest have a single institution each. <br>The distribution of 
institutes is irregular in the US with about 50% of the country's schools being concentrated in 10 States. 
2. Most schools in the US don't have branches, the median number being 1. Strayer University is at the opposite end of the spectrum 
having in total 73 branches spread across 16 States.
3. The median faculty salary on average is 6,400 dollars per month.

#### Academic Trends
1. From the limited data available we can say that a good SAT score falls in the range 500 - 600 for both Reading and Math while a good 
ACT Composite score can be anywhere between 20 and 26.
2. Required Test Scores and Average Faculty Salary across schools have a weakly negative correlation with Admission Rate. Meaning, 
schools that have a high admission rate have lower requirements on test scores and tend to pay less to their faculty on average as 
compared to schools with lower rates of admission.
3. Although the above trend is largely ubiquitous, there are some outlier institutes that have a low admission rate even though their 
requirements on test scores are relatively low. These institutes give less weightage to test scores while admitting students.
4. Certificate Programs are the most common in the US followed by Bachelor's Degrees.

#### Rise of Privatization of Education
1. About 11.5 million undergrads enrolled in Public Schools in Fall '17 as compared to 2.8 million in Private Nonprofits and 1.1 million
in Private For-Profits.
2. Even though the greatest number of enrollments happened in Public Institutions, Private For-Profit Schools are the most common in 
the US. There are about 30% more Private For-Profits than there are Public or Private Nonprofit Schools.
3. The median revenue generated per student per year by institutes is about 9,000 dollars. 90% of schools that generate more than this 
are Private.
4. On average about 90% more students from Private Schools receive federal loans than from Public Schools. Although this could be 
explained by the large number of students in Public Schools, it is an unjust discrepancy nonetheless.


## Contribute
The data as downloaded from Data.gov is quite large in size - about 2.5 GB. This analysis focuses singularly on the Academic 
Year 2017 - 18.
Further, only the variables I found interesting have been included. This project is in no way the complete picture of the U. S. 
Postsecondary
Education System. <br>
There is lot of potential room to analyze the data more deeply and broadly. Any contributions are welcome!

First, fork this repository.

![Fork Icon](images/fork-icon.png)

Next, clone this repository to your desktop to make changes.

```sh
$ git clone https://github.com/dhavalpotdar/College-Scorecard-Data-Analysis.git
$ cd College-Scorecard-Data-Analysis
```

Once you've pushed changes to your local repository, you can issue a pull request by clicking on the green pull request icon.

![Pull Request Icon](images/pull-request-icon.png)

Instead of cloning the repository to your desktop, you can also go to `README.md` in your fork on GitHub.com, hit the Edit 
button (the button with the pencil) to edit the file in your browser, then hit the `Propose file change` button, and finally make 
a pull request. 

## License
The contents of this repository are covered under the [MIT License](https://github.com/dhavalpotdar/College-Scorecard-Data-Analysis/blob/master/LICENSE).
