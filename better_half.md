# Talking to your better half: An educational, reproducible, parallel randomized controlled trial comparing a positive psychology toolkit vs. control and its effect on work engagement, meaning, purpose in life and job satisfaction among professionals

<!-- out of my shoes methodology -->


Francesco de Paola   
Annamaria Meneghini   
Bruno Melo  
Joao Ricardo Vissoci  
Ricardo Pietrobon  


## Abstract
<!-- write at the end -->

## Introduction

Work engagement is arguably one of the most desirable characteristics of an employee from an organizational perspective <!-- ref --> , often times being closely associated with employee characteristics including meaning, purpose in life and job satisfaction. <!-- ref --> And yet, multiple studies have demonstrated that these are also some of the most difficult characteristics to sustain at a high level over time. <!-- ref -->

While previous research has demonstrated that work engagement can be increased through in person or mixed in-person and online interventions <!-- ref --> , this instruction mode is fairly expensive and time consuming since it takes a substantial amount of time away from work, requires a significant payment for specialized instructors and, above all, is not very scalable beyond small groups. <!-- ref --> While an entirely online format would be desirable, to our knowledge no previous studies have been published evaluating alternative forms of professional training.  

* lit review on work engagement and its association with meaning, purpose in life and job satisfaction
* lit review on Online learning for work engagement

The objective of this educational, reproducible, parallel randomized trial is therefore to compare a positive psychology training toolkit intervention involving versus a control group in relation to work engagement, meaning, purpose in life and job satisfaction. We hypothesize that the positive toolkit (named the "better half arm") would result in increased work engagement, meaning, purpose in life and job satisfaction after a four-week intervention period.


## Methods

This trial was designed and reported in accordance with the recommendations provided by the [CONSORT statement](http://www.consort-statement.org/)

### Ethics
This study was approved by the Ethics Committe at the University of Verona ([Università degli Studi di Verona](http://www.univr.it)), informed consent having been waived since this was considered a research with minimal risk within an educational context. All participants were ensured that their participation was absolutely unrelated to their performance in their current disciplines and that they could drop out at any point if they so wanted.

### Trial Design

This is a parallel controlled randomized trial comparing a control group versus a positive psychology toolkit comprehending four main components: (1) focus on the positive rather than the negative side of the work, (2) understand meaning/purpose of the work and establish a connection to its mission, (3) underscore the value that youthe person individually brings to the organization, (4) try to see challenges as opportunities for personal growth, enabled through a problem solving attitude. The trial involved 106 participants who completed the trial <!-- replace by the actual number and describe dropout rate -->, randomized on a 1:1 ratio to the intervention and control arms, with the intervention and respective follow-up lasting a total of four weeks. No changes to the initially methods design were implemented while the trial was in course. <!-- need to check at the end whether this is true -->

### Participants
Our study involved 106 participants. Participants were employees at <!-- add -->, located in the Northeast part of Italy. For each participant we have collected information on gender, age, profession and previous educational background.

### Interventions


The "better half" arm was constituted by a short course with weekly video lectures and exercises focused on a positive psychology toolkit. Specifically, the toolkit involved a series of videos where participants had to answer questions that attempted to create a more positive attitude toward their jobs. These questions focused on four main components of the toolkit, each series of questions delivered one per week:

1. Focus on the positive rather than the negative aspect of the job. This was accomplished by asking questions such as: "is really all the time spent on your job really that bad?" This question was then followed by a request for the participants to create lists about what they currently perceive as a negative aspect of their jobs, how that same characteristic was initially perceived as a positive or interesting thing at the beginning of their job, and how that perception had changed over time. The insight to be gained through this exercise was that negative perceptions can be a belief rather than an experience, making participants go back to the beginning of their job experience when certain aspects of the job seemed to be positive
2. Understand the meaning or purpose of their job and connect those aspects to the overall mission. In this exercise, we emphasized that many characteristics of the jog that might over time seem meaningless or boring actually connected to a larger mission of the company, and that this connection might have been lost over time. By regaining the connection between tasks and a larger purpose, we attempted to recreate the perception that their activities actually had a larger purpose and therefore provided meaning to their day-to-day activities.
3. Underscore the value that the person might individually bring to the organization. The main point in this exercise was to regain the perception that the individual work one performs in the organization is actually essential for its ability to achieve a major goal, even if the task might not seem important when perceived from a day-to-day perspective.
4. Attempt to see challenges as opportunities for personal growth, enabled through a problem solving attitude. This exercise attempted to create the perception that what might seem as simple barriers impeding growth are actually the means to growth themselves. In other words, it is only through challenges and overcoming those challenges that one is capable of growing in their careers and as persons.

The control arm was not provided with an intervention, but simply by the outcome questionnaires discussed in a subsequent section.

All educational material for this course is made available within our Reproducible Research repositories, and delivered through the original [Open edX platform](http://code.edx.org/). Videos were provided in in Italian. All remaining material was made available in Italian, although both Italian and English versions are provided within our Reproducible Research repositories (see subsequent section on Reproducible Research).


<!-- add CONSORT for Non-Pharmacological Treatment Interventions -->

<!-- soft skills, tacit knowledge, rationality, competition, empathy, choice, aesthetics, memory, emotion, happiness - ask mauro for opinion on what could work -->

### Outcome variables
<!-- : toolkit send email to yourself as 4 ferramentas vão ser, a principio:  outcome variables:  -->

Our study had four main categories of outcome variables: work engagement, meaning, purpose in life and job satisfaction, all described under the subsequent sections. Per CONSORT Statement guidelines, any eventual changes to outcome measures deviating from the initial plan and occurring throughout the trial were recorded in our versioning system ([Github](https://github.com/)), thus ensuring full reproducibility. However, changes were avoided unless strictly necessary.

<!-- Francesco to talk with Semeghini -->

#### Work engagement

#### Meaning

#### Purpose in life 


The Life Engagement Test: Assessing Purpose in Life

#### Job satisfaction


#### Sense of coherence
http://www.benthamscience.com/open/togerimj/articles/V004/6TOGERIMJ.pdf

<!-- francesco to translate scale -->



####  Sample size

Given the absence of preliminary efficacy data, we calculated our sample size based on an assumption of a two-sample t-test for an index representing the worst case scenario for each of the four outcomes, with an effect size of 55%, a significance level and statistical power set at the traditional levels of 0.05 and 80%, respectively. Under these assumptions the estimated required sample size is of 52.9 per group, which we have rounded to 53, ultimately leading to a total sample size of 106 participantsin total. Taking into account a worst case scenario dropout rate of approximately 20%, we therefore plan to enroll 140 participants.


####  Interim analyses and stopping guidelines

Given the relatively short duration of our trial, we did not perform an interim analyses. In addition, given the low risk associated with the intervention, our guidelines did recommend that the trial be stopped in case of an unlikely loss of confidentiality that might compromise participants privacy, which has not occurred.

####  Randomization: sequence generation

All randomization schedules were delivered through [Planout](http://facebook.github.io/planout/) within the [edx Code](http://code.edx.org/) platform. Briefly, Planout makes use of a pseudorandom number generator from the [Python language](https://www.python.org/), which has been extensively tested. <!-- need ref --> Randomization was blocked at 10 participants, thus decreasing the likelihood of a possible imbalance.  

All randomization was delivered through the Open edX platform, thus ensuring that participants and investigators are blind to the allocation. Data analysts (RP and JRV) received a dataset from the computer scientist (BM) where the two randomization arms were designated by unspecific letters, thus ensuring that the analysis is also conducted in a blind fashion.


#### Statistical methods 

All analyses were conducted by the members in our team(RP, JRV). The data analysis started with an overall evaluation of individual variables to assess distributions for continuous variables (e.g., participant's age) in terms of their distributions, as well as the frequency/percentage for categorical variables (e.g., gender). 

Missing values were handled differently if they happened to individual variables or full encounters, e.g., an entire evaluation for a week. Individual variables were imputed starting by an exploratory visual analysis to better understand the potential underlying pattern behind missing values for each variable. This analysis was conducted using the [VIM package](http://cran.r-project.org/web/packages/VIMGUI/vignettes/VIM-Imputation.pdf) within the [R language](http://www.r-project.org/). Depending on the pattern of missing data, we might then choose one of several alternatives, ranging from not imputing when the percent missing might be negligible, imputing using predictive models from variables that are hypothesized to be associated with the missing values (e.g., age predicting residency year), or multiple imputation in cases where missing patterns might be happening at random (MAR or missing at random) (@rubin1976inference). <!-- see 3d grant -->

We evaluated for potential confounding of the intervention effect by assessing balance across baseline variables between the 3D and control arms. This evaluation occurred for the overall study. While imbalances were unlikely given that we are using a series of preventive measures (blinding, concealed allocation, blocking and stratification), eventual imbalances were evaluated on an individual basis and required adjusting in our modeling strategy (see below for details).

The psychometric analysis for parallel validation of our scales started with an Exploratory Factor Analysis to evaluate the underlying dimensional structure of our item pool. We then conducted a Confirmatory Factor Analysis using the hypothesized domains (see Outcome Variable section for extensive details). Once domains are established we used Cronbach's alpha to measure internal reliability within each construct. Validity was measured by triangulation across different domains. 

Given that all of our outcomes have multiple endpoints over time, we used a combination of mixed models and survival analysis to measure the efficacy associated with the "better half toolkit" in comparison with the control arm. To formally test trends in each of our outcome variables over time we developed mixed models that account for multiple measures as random a effect. For each time period we also assessed differences in scores. These bivariate analyses incorporated robust standard errors to account for the clustering effect.


### Reproducible research
In order to follow a reproducible research protocol, we have written our final manuscript using Rmarkdown, which combines the R language with the [Markdown markup](http://daringfireball.net/projects/markdown/), ultimately allowing us to leave all calculations and data manipulation within the article text. All data sets and respective analytical scripts were provided in CSV (comma separated value) formats in open public repositories including [Figshare](http://figshare.com/) and [Github](https://github.com/). In addition, we have also stored the version of the software used in this analysis and deposited it within our Github and Figshare repositories, ultimately decreasing the probability of reproducibility issues during subsequent attempts to reproduce our analyses. <!-- add paper that recommends this procedure -->

## Results

<!-- add this section in alignment with CENT -->

## Discussion


<!-- http://www.plosone.org/article/info%3Adoi%2F10.1371%2Fjournal.pone.0084118

http://kenexa.com/Portals/0/Downloads/KHPI%20Papers/Developing%20and%20Validating%20a%20Global%20Model%20of%20Employee%20Engagement.pdf

http://www.wilmarschaufeli.nl/publications/Schaufeli/290.pdf
 -->

<!-- 
http://www.psychologytoday.com/blog/career-transitions/201207/job-crafting
http://justinmberg.com/berg-dutton--wrzesniewski_j.pdf
http://www.compasspoint.org/sites/default/files/docs/Positive%20Organizational%20Scholarship%20Concepts%20and%20Resources.pdf
http://positiveorgs.bus.umich.edu/cpo-tools/job-crafting-exercise/
 -->
