--- 
layout: index
title: Syllabus

index:
    title: Foundations of Program Evaluation III
    image: distribution.svg
    subtitle: Econometrics techniques for program evaluation. 
    
info: 
 program_title: Program Evaluation and Data Analytics
 program_website: 
 course_title: Foundations of Program Evaluation Part III
 course_number: CPP 525 
 course_level: Graduate 
 course_website: 'https://canvas.asu.edu/courses/41574'
 course_start_end_dates: March 16 to May 01, 2020 
 course_prerequisites: CPP 523
 class_meets_when:  Asynchronous  
 class_meets_where:  ''
 review_sessions_when: TBD 
 review_sessions_where: 
 discussion_board_url: 'https://ds4ps.org/cpp-525-spr-2020/help/'

instructor:
-  name: Irene Tsapara, PhD
   title: Professor
   email: irene.tsapara@asu.edu
   office_location: virtual
   website_url: 
   github_url: 'https://github.com/itsapara' 
   twitter_url: 
   scholar_url: 
   linked_in_url: 'https://www.linkedin.com/in/irene-tsapara-8a1a04b5/'
   office_hours_time: By appointment
   office_hours_location:  Zoom
   office_hours_app_url:  'https://calendly.com/irene-tsapara/15min'
   

textbooks:
- title: 'Applied Regression: An Introduction'
  authors: 'Lewis-Beck, C., & Lewis-Beck, M.'
  edition: 2015
  link: https://github.com/DS4PS/cpp-523-spr-2020/raw/master/pubs/Applied%20Regression%20Lewis-Beck.pdf
  required: Required (follow link)
- title: 'Impact Evaluation in Practice'
  authors: 'Gertler, P. J., Martinez, S., Premand, P., Rawlings, L. B., & Vermeersch, C. M. J.'
  edition: 2011
  link: https://siteresources.worldbank.org/EXTHDOFFICE/Resources/5485726-1295455628620/Impact_Evaluation_in_Practice.pdf
  required: Free online
- title: 'Real Stats: Using Econometrics for Political Science and Public Policy'
  authors: 'Bailey, M. A.'
  edition: 2016
  link: 'https://www.amazon.com/Real-Stats-Econometrics-Political-Science/dp/0199981949'
  required: Recommended Reference
--- 




# I.  Course Description, Course Goal and Course Learning Objectives:

Regression serves as the foundation for modern quantitative program evaluation techniques. It is a powerful set of tools used to examine relationships in data and test hypotheses concerning the significance of these relationships. Regression can be used to analyze observational data, in which case it can be used to identify correlational relationships to predict when events will occur together. In the program evaluation context we are specifically interested in causal analysis, which allows us to determine whether a management practice, a nonprofit or government program, or a specific public policy has a positive impact. When certain conditions are met we can use regression analysis to produce an imperfect but reasonable estimate the causal impact of a policy or program. 

This course helps you expand your program evaluation toolkit by demonstrating how to estimate several common regression models that leverage unique data and counterfactual specifications. The previous course on research design (CPP 524) covered a collection of experimentatal and quasi-experimental approaches to estimating program impact. This course extends the previous material by translating each specific form of the counterfactual – pre-post with comparisons, reflexive design, and the post-test only design – into specific regression models that leverage each counterfactual. This course teaches you how to estimate program effects using a given research design. We will cover the following models organized by counterfactuals: 

**Pre-post with comparison group:**
(1) difference-in-difference regression
(2) panel models using fixed effects
**Reflexive design:** 
(3) time series analysis
**Post-test only design:**
(4) propensity score matching
(5) regression discontinuity design

We also cover (6) instrumental variables and (7) logistic regression. 

The main learning objectives for the course are:

* Gaining comfort with hypothesis-testing using regression models 
* Developing the ability to select the best model to evaluate a specific program 
* Be able to identify the implicit counterfactual used in each model 
* Gain knowledge of assumptions of each model 




## Course Prerequisites:

This course will build upon material presented in Foundations of Program Evaluation II.

To be successful in this program you need foundational knowledge about regression models covered in CPP 523 or a similar class. Basic R knowledge is assumed, including the ability to use R Markdown documents for labs.  



### Math

This course utilizes algebra and some geometry, specifically the slope-intercept equation of a line:

```
y = mx + b
```


We will use basic probability, logarithms, and exponents, all at a high school level. We will NOT be using calculus, matrix algebra, or proofs for this course. 

We will rely heavily on visual reasoning with the data, an intuitive understanding of regression mechanics, and a strong understanding of the interpretation of results, but for the most part we will rely on software for advanced mathematical calculations.




# II. Assessment of Student Learning Performance & Proficiency: Keys to Student Success

Assessment of student performance in this course is based on indications that the course learning objectives stated above have been achieved.  Several areas of measurement will be used to produce a final student performance rating.  These areas of performance assessment include the following:

- Knowledge of key concepts associated with regression models, the interpretation of program impact in quantitative studies, the mechanics of control variables, and the differentiation between correlational and causal analysis.
- Ability to run and interpret program evaluation models by correctly specifying a multiple regression equation, diagnosing problems, and presenting findings to stakeholders.
- Completed assignments are measured and assessed based on a demonstrated understanding of core regression concepts and the ability to clearly and accurately interpret model results.

Students will demonstrate competency in understanding, producing and communicating results of their analyses through weekly labs. 

The course grade is a direct reflection of performance on labs. Students should take stated expectations seriously regarding preparation, conduct, and academic honesty in order to receive a grade reflective of outstanding performance.  

Students should be aware that merely completing assigned work in no way guarantees an outstanding grade in the course. To receive an outstanding course grade all assigned work should completed on time with careful attention to assignment details.

# III. Course Structure and Operations; Performance Expectations

## A. Format and Pedagogical Theory

Mastering advanced analytical techniques is like learning a language. You start by mastering basic vocabulary that is specific to statistics. Through your coursework you will become conversant in the domains of regression analysis, research design, and data analysis. 

Progress might be slow at first as you work to master core concepts, integrate the building blocks into a coherent mental model of real-world problems, learn to translate technical results into clear narratives for non-technical audiences, and become comfortable with data programming skills. Over time you will find that your thought processes change as you approach problem-solving in a more structured and evidence-based manner, you apply counter-factual reasoning to performance problems, and you start reading the news and viewing scientific evidence differently. You begin to think and speak like a program evaluator.

By the end of this degree you will be conversant in statistics, research design, and data programming. Fluency takes time and will be developed through professional experience. It requires you to practice these skills to develop muscle memory. You can do this through participating in evaluations on the job and gaining experience building and cleaning data sets from scratch. Understand, though, that this degree focuses on building foundations for your career. Don&#39;t be nervous if it feels like it&#39;s impossible to master all of the material in this program – it is impossible to learn everything in this field in a year.

Similar to immersion in a language, the best way to learn the material is to be consistent in doing course work each day. The more frequently you revisit concepts and practice data programming the more you will absorb. The curriculum has been designed around this approach. Lectures are split into small units, and each unit includes questions to test your understanding of the material. Weekly labs allow you to spend some time applying the material to a specific problem. The final exam at the end of the semester is designed to help you make connections between concepts and consolidate knowledge. You will be much better off spending a small amount of time each day on the material instead of trying to cram everything into a couple of days a week.

Online discussion boards, when used, are design to accomplish three things: (1) allow students to interact with their peers and share ideas and interpretations of the assigned material, (2) such peer-to-peer discussion online helps build professional relationships with potential future colleagues in the field, and (3) the discussions permit the instructor to assess student engagement with the assigned material.

The online discussions are explicitly intended to meet the objectives stated above.  They are not intended as another form of &quot;lecture&quot; where the instructor provides commentary and students simply react to that.  Rather, the discussions are a chance for peer-to-peer interaction and proactive engagement by each individual student.

The purpose of all exams and assigned written work is also threefold: (1) the assignments and written exam afford students the opportunity to demonstrate substantive understanding of materials covered in course readings, lectures and online discussion, (2) the assignments and exam permit students to develop and demonstrate research, analytic and written communication skills, and (3) the written work permits the instructor to assess student knowledge, skills and ability within this subject domain.



## B. Assigned Reading Materials

There is one required texts for this course, and it is available online for free:

- Gertler, P. J., Martinez, S., Premand, P., Rawlings, L. B., &amp; Vermeersch, C. M. J. (2011). _Impact Evaluation in Practice._ The World Bank. Washington. Available free online.

### Reference Texts

Each author approaches material in a slightly different way, so different textbooks work for different people. The following texts are recommended as good resources if you would like additional references:

- Field, A., Miles, J., & Field, Z. (2012). Discovering statistics using R. Sage publications. 
- Bailey, M. A. (2016). _Real Stats: Using Econometrics for Political Science and Public Policy_. Oxford University Press.
- Bingham, R., &amp; Felbinger, C. (2002). _Evaluation in Practice: A Methodological Approach._ CQ Press.
- Fox, J. (1991). _Regression diagnostics: An introduction_ (Vol. 79). Sage.
- Berry, W. D., &amp; Feldman, S. (1985). _Multiple regression in practice_ (No. 50). Sage.
- Cohen, J., Cohen, P., West, S. G., &amp; Aiken, L. S. (2013). _Applied Multiple Regression/Correlation Analysis for the Behavioral Sciences_. Routledge.
- William R.. Shadish, Cook, T. D., &amp; Campbell, D. T. (2002). _Experimental and quasi-experimental designs for generalized causal inference._ Wadsworth Cengage learning.
- Cumming, G. (2013). _Understanding the New Statistics: Effect Sizes, Confidence Intervals, and Meta-Analysis_. Routledge.
- Stock, J. H., &amp; Watson, M. W. (2007). _Introduction to Econometrics._
- Wooldridge, J. M. (2015). _Introductory Econometrics: A Modern Approach_. Nelson Education.

In addition to the required textbooks, the instructor will supplement the assigned unit readings with various journal articles, policy reports, or other related material.  These will be made available in the course shell.

## C.  Course Grading System for Assigned Work, including Final Exam:

Your grade will be based on your performance in the following areas:
 
- Weekly labs

Letter grades comport with a traditional set of intervals:

* 100 – 99% = A+ 
*  98 – 94% = A 
*  93 – 90% = A- 
*  89 – 87% = B+ 
*  86 – 84% = B 
*  83 – 80% = B-  

The assigned work for the term comes in the form of four elements, described below:

- **Weekly Labs (100%):**  Each week you will be given a lab based upon a new regression model. 

- **Final Quiz (10%):**  The course will conclude with a quiz


## D. General Grading Rubric for Written Work

In general, any submitted work written work (assignments and/or exams) is assessed on these evaluative criteria:

- Assignment completeness – all elements of the assignment are addressed
- Quality of analysis – substantively rigorous in addressing the assignment
- Demonstrated synthesis of core concepts from lecture notes and ability to apply to new problems

Most assignments in this course are labs that are graded pass-fail based upon completeness and correctness of responses (every attempt must be made to complete labs, and they must be more than 50% correct to receive credit). Discussion boards that accumulate points through each activity on the board. 

The final project will be accompanied by a rubric describing the allocation of points and criteria for evaluation. 

## E. Late and Missing Assignments

Grades for the course are largely based on weekly labs. Assigned work is accompanied by detailed instructions, adequate time for completion and opportunities to consult the instructor with questions. As a result, each assignment element in the course is expected to be completed in a timely fashion by the due date. Once solutions are posted it is no longer possible to receive points for assignments. 

## F.  Course Communications and Instructor Feedback:

**Course content** is hosted on this website. Lecture files, assignments and other course communications will be transmitted via this site and/or through the class email list. **All assignment submissions** will be made through the [Canvas shell](https://canvas.asu.edu). 

Please post lab questions on the [Get Help](/help/) page on this site, schedule individual office hours using the Calendly link provided above, and email the instructor directly instead of using the Canvas system. 

Students should be aware that the course instructor will attempt to respond to any course-related email as quickly as possible. Students are asked to allow between 24 and 48 hours for replies to direct instructor emails, generally, as a reasonable time to reply to questions or other issues posed in an email. Additionally, the general timeline for instructor grading or other feedback on assignments, either writer work or online discussion work, is between 5 and 10 work days.


# I. Student Learning Environment: Accommodations

**Disability Accommodations:**  Students should be fully aware that the Arizona State University, the MA in EMHS program, and all program course instructors are committed to providing reasonable accommodation and access to programs and services to persons with disabilities. Students with disabilities who wish to seek academic accommodations must contact the ASU Disability Resources Center directly.  Information on the Center&#39;s procedures, resources and how to contact its staff can be found here: [https://eoss.asu.edu/drc/](https://eoss.asu.edu/drc/).  The Disability Resources Center is responsible for reviewing any student&#39;s requests; once that review has taken place, the Center will provide the student with appropriate information on academic accommodations which in turn will be provided to the course instructor.

**Religious accommodations:** Students will not be penalized for missing an assignment due solely to a religious holiday/observance, but as this class operates with a fairly flexible schedule, all efforts should be made to complete work within the required timeframe. If this is not possible, students must notify the instructor as far in advance as possible in order to make an alternative arrangement.

**Military Accommodations:** A student who is a member of the National Guard, Reserve, or other branch of the armed forces and is unable to complete classes because of military activation may request complete or partial unrestricted administrative withdrawals or incompletes depending on the timing of the activation. For more information see ASU policy [USI 201-18](http://www.asu.edu/aad/manuals/usi).



# IV. Course Schedule and Unit-specific Learning Objectives

## A. Schedule: Overview of Readings and Assignments

As students are all aware, ASU Online courses are typically offered on a seven and a half week schedule. A schedule for each week of the term is outlined here; the course is divided into seven units with specific learning objectives for each unit.

Please note: the course instructor may from time to time adjust assigned readings or adjust the due dates for assignment. The basic course content approach and learning objectives will not change, but slight modifications are possible if circumstances warrant an adjustment.

## Couse Schedule

### Unit 1 - Regression Review

**Regression Mechanics: Variance, Slopes and Residuals**
- Using Regression Models to Estimate Program Effects&quot; Read 417-431, Skim 431-455
- Lewis-Beck pp 9-25
- Lab #1 – Regression Review

### Unit 2 - Effects: Size and Confidence 

**Hypothesis Testing: Standard Errors, Confidence Intervals, and p-values**
- Skim The New Statistics, CH3: Confidence Intervals; CH4: Error Bars and p-values.
- Lewis-Beck pp 30-54
- Lab #2 - Confidence Intervals

### Unit 3 - Control Variables 

**Control Variables &amp; Partitioned Regressions**
- Baily CH5: Section 5.1-Multivariate OLS
- Lab #3 - Partitioned Regression

### Unit 4 - Omitted Variable Bias

**Omitted Variable Bias**
- Baily Section 5.2-Omitted Variable Bias
- Lab #4 – Omitted Variable Bias

### Unit 5 - Dummy Variables 

**Model Specification**
- Baily CH6: Dummy Variables; CH7: Transforming Variables
- Lab #5 – Omitted Variable Bias

### Unit 6 - Specification

**Model Specification**
- Baily CH7: Transforming Variables
- Lab #6 – More Model Specification

**Seven Sins of Regression Analysis** 
- Readings posted on Course Shell

### Unit 7

**Review for Final**
- Practice final exam 

### Final Exam

<br>
<br>









<style> 
body {
   font-family: "Roboto", sans-serif;
}
 
p.italic {
  font-style: italic;
  color: black !important;
}

em {
  color: black !important;
  }

#fa-icon {
  font-style: normal;
}
</style>
