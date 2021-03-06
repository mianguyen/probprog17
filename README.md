# CS492 Probabilistic Programming, Fall 2017, KAIST 

This is a webpage of the course "CS492 Probabilistic Programming", which is offered at the KAIST CS department in the fall of 2017. The webpage will contain links to lecture slides and other course-related materials.

Probabilistic programming refers to the idea of developing a programming language for writing and reasoning about probabilistic models from machine learning and statistics. Such a language comes with the implementation of several generic inference algorithms that answer various queries about the models written in the language, such as posterior inference and marginalisation. By providing these algorithms, a probabilistic programming language enables data scientists to focus on designing good models based on their domain knowledge, instead of building effective inference engines for their models, a task that typically requires expertise in machine learning, statistics and systems. Even experts in machine learning and statistics may get benefitted from such a probabilistic programming system because using the system they can easily explore highly advanced models.

This course has two goals. The first is to help students to be a good user of an expressive probabilistic programming language.  Throughout the course, we will use a particular language, called [Anglican](http://www.robots.ox.ac.uk/~fwood/anglican/), but we will emphasise general principles that apply to a wide range of existing probabilistic programming systems. The second goal is to expose the students to recent exciting results in probabilistic programming, which come from machine learning, statistics, programming languages, and probability theory.  Through a group project, students will be given a chance to study such a result
and to play with it.

## 1. Important Announcements

#### [December 19 2017] Final exam scoring is completed.

The TA uploaded Final exam scores on the KLMS. If you have any questions about your homework and final exam scores, please visit E3-1 building room 3420 at 2:00~3:00 pm on Tuesday and Wednesday.

#### [December 7 2017] Final exam schedule.

We follow the schedule arranged by the university. Our exam will happen at 
2443 in the E3 building, from 9:00 - 11:45 on Monday (11 December).

#### [December 2 2017] Homework 2 scoring is completed.

The TA uploaded Homework2 scores on the KLMS. If you have any questions about your score, contact TA (bskim90@kaist.ac.kr)

#### [November 30 2017] Homework 1 scoring is completed.

The TA uploaded Homework1 scores on the KLMS. If you have any questions about your score, contact TA (bskim90@kaist.ac.kr)

#### [November 27 2017] 1. No need to submit Homework 3.

You don't have to submit your answers to homework 3. But make sure that you know how to solve the second question in that homework.

#### [November 27 2017] 2. Presentation of group project on 4 December (Monday).

We will start five minute earlier on 4 December. On that day, each group will have to give a 15 minute presentation on their project, and answer questions from other students for 5 minutes. Here is a schedule of presentation.

1. 8:55am - 9:15am on 4 December (Mon) : Jungmin, Juhee
2. 9:15am - 9:35am on 4 December (Mon) : Ly Le, Minkee, Junoh
3. 9:35am - 9:55am on 4 December (Mon) : Donghyun, Hyunsoo, Hyunsoo
4. 9:55am - 10:15am on 4 December (Mon) : Junoh, Sujin, Changwha

#### [November 27 2017] 3. Project report by the midnight on 6 December (Wednesday).

Each project group should submit a report on what they learnt during the project. Short 2-page reports are recommended, but if students in a group think necessary, they can use more pages in their report. Please submit a report to the homework submission box in the third floor of the E3-1 building.

#### [November 22 2017] [Homework 3](https://github.com/hongseok-yang/probprog17/blob/master/Homework/Homework3/homework3.pdf) is out. Submit your solutions to the TA (Byungsoo) by 2:00pm on 6 December (Wednesday).

#### [November 19 2017] 1. Project meeting this week.

There will be a final meeting between me and each project group this week. The schedule is similar to the one before.

1. 7:40pm - 8:20pm on November 23 (Thu) : Junoh, Sujin, Changwha
2. 8:20pm - 9:00pm on November 23 (Thu) : Junghun, Wonyeol
3. 7:00pm - 7:40pm on November 24 (Fri) : Ly Le, Minkee, Junoh
4. 7:40pm - 8:20pm on November 24 (Fri) : Donghyun, Hyunsoo, Hyunsoo
5. 8:20pm - 9:00pm on November 23 (Fri) : Junmin, Juhee

#### [November 19 2017] 2. Change in the schedule due to the change in the KAIST undergraduate interview.

The KAIST undergraduate interview is postponed for a week because of earthquake. So, there is an adjustment of the schedule of the course. The new schedule is now in the course web page. Here are two important points:

1. We will have a lecture on 29 November, but will not have one on 6 December, on which there will be undergraduate interviews in KAIST.
2. Each project group will have to give a 15-min presentation on 4 December instead of 6 December.

#### [November 8 2017] There will be no lectures on 13 and 15 November. The evening group meetings were postponed to 23 and 24 November.

#### [November 7 2017] [Homework 2](https://github.com/hongseok-yang/probprog17/blob/master/Homework/Homework2/homework2.pdf) is out. Submit your solutions to the TA (Byungsoo) by 2:00pm on 22 November (Wednesday).

#### [November 2 2017] The last evening meetings with project groups
were moved from 9-10 November to 23-24 November.

#### [October 28 2017] The lecture on 29 November (Wed) is cancelled due to the university-wide undergraduate interview. 

#### [October 25 2017] Schedule of group interview this week.

As we announced, there will be individual group meetings with Hongseok
on Thursday and Friday this week. Here is a tentative schedule.

1. 6:00pm - 6:40pm on October 26 (Thu) : Junmin, Juhee
2. 7:40pm - 8:20pm on October 26 (Thu) : Junoh, Sujin, Changwha
3. 8:20pm - 9:00pm on October 26 (Thu) : Junghun, Wonyeol
4. 7:00pm - 7:40pm on October 27 (Fri) : Ly Le, Minkee, Junoh
5. 7:40pm - 8:20pm on October 27 (Fri) : Donghyun, Hyunsoo, Hyunsoo

#### [October 22 2017] [Homework 1](https://github.com/hongseok-yang/probprog17/blob/master/Homework/Homework1/homework1.pdf) is out. Submit your solutions to the TA (Byungsoo) by 2:00pm on 6 November (Monday).

#### [September 25 2017] 2D physics and program induction examples.

These examples (lecture4a.clj and lecture4b.clj) and two helper files (project.clj and bounce.clj) are available [here](https://github.com/hongseok-yang/probprog17/tree/master/Lectures/Lecture4). lecture4a.clj is a Gorilla worksheet for the 2D physics example, and lecture4b.clj is a worksheet for the program-induction example. To run the 2D physics example, you need to replace your project.clj file in the root directory of your anglican-user clone by the project.clj file from this webpage. Also, you need to store the bounce.clj file under the src directory of your anglican-user clone.

#### [September 16 2017] 1. No lecture on October 2.

Since the government decided to make October 2 a holiday, there will be no lecture on that day. So, there will be no lectures on the following dates:

1. October 2 (Mon) and October 4 (Wed) - Chuseok
2. October 9 (Mon) - Hangul Proclamation Day
3. October 16 (Mon) and October 18 (Wed) - Midterm Exam Period
4. November 13 (Mon) and November 15 (Wed) - Business Trip
5. December 11 (Mon) and December 13 (Wed) - Final Exam Period

#### [September 16 2017] 2. Schedule of group interviews this week.

As we announced, there will be individual group meetings with Hongseok
on Thursday and Friday this week. Here is a tentative schedule.

1. 6:00pm - 6:40pm on September 21 (Thu) : Junmin, Juhee
2. 7:40pm - 8:20pm on September 21 (Thu) : Junoh, Sujin, Changwha
3. 8:20pm - 9:00pm on September 21 (Thu) : Junghun, Wonyeol
4. 7:00pm - 7:40pm on September 22 (Fri) : Ly Le, Minkee, Junoh
5. 7:40pm - 8:20pm on September 22 (Fri) : Donghyun, Hyunsoo, Hyunsoo

* place: E3-1, 3403 (Hongseok's office)

If this schedule does not work, let us know it as soon as possible. Before each meeting, consider one or two possible topics of your project, or a few directions that you would like to pursue in your project. The goal of this meeting is to help you to pick a topic and to figure out what to do.

#### [August 29 2017] [Homework 0](https://github.com/hongseok-yang/probprog17/blob/master/Homework/Homework0/homework0.pdf) is out.

You don't have to submit your answer. But we strongly recommend you to try it. This homework will teach you how to run Anglican.

#### [August 27 2017] 1. Form a project group.

#### [August 27 2017] 2. Missing lectures and meetings with each project group.

There will be no lectures on the following dates:
1. September 4 (Mon) and September 6 (Wed) - Business Trip
2. October 4 (Wed) - Chuseok
3. October 9 (Mon) - Hangul Proclamation Day
4. October 16 (Mon) and October 18 (Wed) - Midterm Exam Period
5. November 13 (Mon) and November 15 (Wed) - Business Trip
6. December 11 (Mon) and December 13 (Wed) - Final Exam Period

Instead of the four missing lectures, Hongseok plans to have three meetings
with each project group for about 30 minutes. These meetings will take place as follows:
1. 7:00pm - 9:00pm on September 21 and 22 (Thu and Fri).
2. 7:00pm - 9:00pm on October 26 and 27 (Thu and Fri).
3. 7:00pm - 9:00pm on November 09 and 10 (Thu and Fri).

## 2. Logistics

#### Evaluation

Final exam (40%). Project (40%). Homework (20%).

#### Teaching Staffs

* Lecturer: [Hongseok Yang](https://cs.kaist.ac.kr/people/view?idx=552&kind=faculty&menu=160) (email: hongseok.yang@kaist.ac.kr)
* TA: Byungsoo Kim (email: bskim90@kaist.ac.kr, office hour: 2:30pm - 5:30pm on Wednesday, at Room 403 in N1 Building)

#### Place and Time

* Place: Room 2443 in the E3 Building
* Time: 9:00 - 10:15 on Monday and Wednesday from August 28 2017 until December 15 2017. 

Look at the announcements for the cancelled lectures and the additional meetings.

#### Online Discussion

The course has a [board](https://noah.kaist.ac.kr/course/CS492) in the noab bbs. Byungsoo's id is bskim90, and Hongseok's id in noah is hongseokyang.

## 3. Tentative Plan

* 08/28 (Mon) - Introduction. [Slides.](https://github.com/hongseok-yang/probprog17/blob/master/Lectures/Lecture1/Lecture1.pdf) [Homework0.](https://github.com/hongseok-yang/probprog17/blob/master/Homework/Homework0/homework0.pdf)
* 08/30 (Wed) - Basics of Clojure and Tiny Bit of Anglican. [Slides.](https://github.com/hongseok-yang/probprog17/blob/master/Lectures/Lecture2/Lecture2.pdf)
* __**09/04 (Mon), 09/06 (Wed) - NO LECTURES.**__ 
* 09/11 (Mon) - Posterior Inference, Basics of Anglican, and Importance Sampling. [Slides.](https://github.com/hongseok-yang/probprog17/blob/master/Lectures/Lecture3/Lecture3.pdf)
* 09/13 (Wed) - Posterior Inference, Basics of Anglican, and Importance Sampling. [Slides.](https://github.com/hongseok-yang/probprog17/blob/master/Lectures/Lecture3/Lecture3.pdf)
* 09/18 (Mon) - Generative Modelling with Anglican. [Slides.](https://github.com/hongseok-yang/probprog17/blob/master/Lectures/Lecture4/Lecture4.pdf)
* 09/20 (Wed) - Generative Modelling with Anglican. [Slides.](https://github.com/hongseok-yang/probprog17/blob/master/Lectures/Lecture4/Lecture4.pdf)
* __**09/21-22 (Thu,Fri) - EVENING MEETINGS with project groups.**__ 
* 09/25 (Mon) - Generative Modelling with Anglican. [Slides.](https://github.com/hongseok-yang/probprog17/blob/master/Lectures/Lecture4/Lecture4.pdf)
* 09/27 (Wed) - Markov Chain Monte Carlo. [Slides.](https://github.com/hongseok-yang/probprog17/blob/master/Lectures/Lecture5/Lecture5.pdf)
* __**10/02 (Mon), 10/04 (Wed), 10/09 (Mon) - NO LECTURES.**__
* 10/11 (Wed) - Markov Chain Monte Carlo. [Slides.](https://github.com/hongseok-yang/probprog17/blob/master/Lectures/Lecture5/Lecture5.pdf)
* __**10/16 (Mon), 10/18 (Wed) - NO LECTURES.**__
* 10/23 (Mon) - Markov Chain Monte Carlo. [Slides.](https://github.com/hongseok-yang/probprog17/blob/master/Lectures/Lecture5/Lecture5.pdf)
* 10/25 (Wed) - Implementing Inference Algorithms for Probabilistic Programs. [Slides.](https://github.com/hongseok-yang/probprog17/blob/master/Lectures/Lecture6/Lecture6.pdf) [Lecture Note.](https://github.com/hongseok-yang/probprog17/blob/master/Lectures/Lecture6/Note6.pdf)
* __**10/26-27 (Thu,Fri) - EVENING MEETINGS with project groups.**__
* 10/30 (Mon) - Implementing Inference Algorithms for Probabilistic Programs. [Slides.](https://github.com/hongseok-yang/probprog17/blob/master/Lectures/Lecture6/Lecture6.pdf) [Lecture Note.](https://github.com/hongseok-yang/probprog17/blob/master/Lectures/Lecture6/Note6.pdf)
* 11/01 (Wed) - Implementing Inference Algorithms for Probabilistic Programs. [Slides.](https://github.com/hongseok-yang/probprog17/blob/master/Lectures/Lecture6/Lecture6.pdf) [Lecture Note.](https://github.com/hongseok-yang/probprog17/blob/master/Lectures/Lecture6/Note6.pdf)
* 11/06 (Mon) - Denotational Semantics of Probabilistic Programs. [Slides.](https://github.com/hongseok-yang/probprog17/blob/master/Lectures/Lecture7/Lecture7.pdf) [Lecture Note.](https://github.com/hongseok-yang/probprog17/blob/master/Lectures/Lecture7/Note7.pdf)
* 11/08 (Wed) - Denotational Semantics of Probabilistic Programs. [Slides.](https://github.com/hongseok-yang/probprog17/blob/master/Lectures/Lecture7/Lecture7.pdf) [Lecture Note.](https://github.com/hongseok-yang/probprog17/blob/master/Lectures/Lecture7/Note7.pdf)
* __**11/13 (Mon), 11/15 (Wed) - NO LECTURES.**__
* 11/20 (Mon) - Denotational Semantics of Probabilistic Programs. [Slides.](https://github.com/hongseok-yang/probprog17/blob/master/Lectures/Lecture7/Lecture7.pdf) [Lecture Note.](https://github.com/hongseok-yang/probprog17/blob/master/Lectures/Lecture7/Note7.pdf)
* 11/22 (Wed) - Denotational Semantics of Probabilistic Programs. [Slides.](https://github.com/hongseok-yang/probprog17/blob/master/Lectures/Lecture7/Lecture7.pdf) [Lecture Note.](https://github.com/hongseok-yang/probprog17/blob/master/Lectures/Lecture7/Note7.pdf)
* __**11/23-24 (Thu,Fri) - EVENING MEETINGS with project groups.**__
* 11/27 (Mon) - Amortised Inference. [Slides.](https://github.com/hongseok-yang/probprog17/blob/master/Lectures/Lecture8/Lecture8.pdf) 
* 11/29 (Wed) - Amortised Inference. [Slides.](https://github.com/hongseok-yang/probprog17/blob/master/Lectures/Lecture8/Lecture8.pdf) 
* 12/04 (Mon) - Project Presentation and Discussion.
* __**12/06 (Wed) - NO LECTURE.**__
* __**12/11 (Mon), 12/13 (Wed) - NO LECTURES.**__

## 4. Studying Materials

Unfortunately we do not know of a good textbook that matches the topics of this course exactly.Studying the lecture slides and the homework exercises of the course is likely to be the most time-efficient way to catch up with this course. Also, at each lecture, we will give students pointers to the related papers. If a student wants to study more or finds the slides and the papers too terse or difficult, we recommend to have a look at the following online materials.

1. [Anglican website](http://www.robots.ox.ac.uk/~fwood/anglican/). In particular, students will learn a lot by trying examples in the site.
2. Goodman and Stuhlmuller's book "[The Design and Implementation of Probabilistic Programming Languages](http://dippl.org/)" This web-based book describes the implementation of WebPPL, a probabilistic programming language on top of JavaScript. Many techniques in the book are general and apply to other probabilistic programming languages.
3. [Forestdb.org](http://forestdb.org/) is a great source of interesting probabilistic programs. 
4. The online book "[Probabilistic Programming and Bayesian Methods for Hackers](https://github.com/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers)" describes Bayesian Machine Learning using a probabilistic programming system called PyMC.  Hongseok found this book easy to follow and good at explaining basics and intuitions. A more standard reference on machine learning is Bishop's book "Pattern Recognition and Machine Learning".

## 5. Group Project

A group project is a crucial part of this course. 2-3 students will form a 
project group, and they will carry out a project in Track A or in Track B:

1. **Track A**: A group develops an interesting application of Anglican or other probabilistic programming languages. The members of the group may attempt to find an efficient encoding of a highly complex probabilistic model (such as sequence memoizer) in Anglican,  or they may develop a new probabilistic model for a complex data set and analyse the data set, or they may try to find a novel use of probabilistic programming for solving well-known existing problems (such as figuring out secret key in some security protocol).
2. **Track B**: A group does small-scale research on probabilistic programming. The members of the group may choose to study a recent result on probabilistic programming or a related area and attempt to extend the result. Or they may consider a research question on probabilistic programming and try to come up with an answer. We are aware that failure is a norm in research. Thus, failed attempts to answer open questions and novel yet slower algorithms than existing ones are completely fine as long as they are analyzed carefully. We will suggest a few results and questions, although members of each group are free to choose one for themselves.

#### Concrete Tasks 

1. **[Deadline: midnight on Sep 11]** Form a group. Email it to both Byungsoo and Hongseok. 
2. **[Sep 21-22, Oct 26-27, Nov 9-10]** Participate in three evening meetings with Hongseok actively.
   1. First meeting: Choose candidate topics and plans before the meeting. 
   2. Second and third meetings: Have to explain the progress of a project and the challenges encountered so far.
3. **[Nov 27,29, Dec 4,6]** Present the result of your project. The presentation should include enough background materials so that it can be understood by fellow students.
4. **[Deadline: midnight on Dec 8]** Submit a report on the project. The report should not have more than 4 pages. 

#### Suggeted Topics in Track B

1. **Automatic Model Criticism and Automatic Model Revision.** People often arrive at a right model for a given data set after multiple revisions. Model criticism refers to techniques for evaluating the qualities of a model, and it plays a crucial role in this model-revision process. These model-revision techniques are partly automated in the probabilistic programming language Edward and the R language. The goal here is to study the state of the art in automatic model criticism, and to develop similar or better model-criticism functionalities for Anglican, a far more expressive probabilistic programming language than Edward and R. A more ambitious goal can be to develop a technique for automatically improving a model expressed as a probabilistic program by using these model-criticism functionalities. A good starting point is the [model-criticism web page](http://edwardlib.org/tutorials/criticism) of the Edward language. The book "Rethinking Statistics" also describes this process of model criticism and revision using several examples and information-theoretic estimates such as WAIC. This latter goal is similar to the objective of [the automated statistican project](https://www.automaticstatistician.com/index/), although this project uses a very different technique based on kernels.

2. **Variational Optimisation for Probabilistic Programs.** Suppose that we are given an Anglican function f that takes a real number and returns a real number randomly. We would like to find an input to this function that maximises the expectation of f(x). The goal here is to use the variational optimisation technique to solve this problem. The variational optimisation is explained in [this paper](https://arxiv.org/abs/1707.07113). [This paper](http://www.robots.ox.ac.uk/~twgr/assets/pdf/rainforth2016BOPP.pdf) on Bayesian optimisation for probabilistic programs is also related.

3. **Renyi-Divergence-Based Black-box Variational Inference for Probabilistic Programs.** A black-box variational inference (BBVI) is a powerful technique for computing an approximate posterior distribution of a probabilistic model. The standard BBVI has been implemented in Anglican, and it has played a crucial role for using Anglican for solving challenging stochastic planning problems. Our goal is to implement a recent variant of BBVI based on Renyi divergence for Anglican, and to analyse its cons and pros experimentally. The related papers are [the original BBVI paper](http://www.cs.columbia.edu/~blei/papers/RanganathGerrishBlei2014.pdf), [the Reni-divergence variational inference paper](https://arxiv.org/pdf/1602.02311.pdf), and [this paper on BBVI in Anglican](http://www.robots.ox.ac.uk/~fwood/assets/pdf/vandemeent16.pdf).

4. **Comparing the Cartesian Product of Quasi-Borel Spaces with That of Measurable Spaces.** This is a math problem. In the course, we will present quasi-Borel spaces and use them to set a new foundation of probability theory. Then, we will explain why this new foundation is more suitable for describing Anglican programs than the standard foundation based on measurable spaces. This topic is related to one such reason, which is that the cartesian product of quasi-Borel spaces is different from that of measurable spaces; intuitively, it is more permissive.  This difference is known, but we lack concrete examples that show this difference clearly. The goal here is to find such examples and to try to say something general about those examples. [Hongseok's LICS'17 paper](https://arxiv.org/pdf/1701.02547.pdf) is a good entry for this topic. 

5. **Automatic Synthesis of Probabilistic Programs.** The goal of this topic is to develop an efficient technique for finding a good probabilistic program for a given data set. Nori and his colleagues worked on this problem using the idea of sketch from the programming-language community. Understanding [their paper](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/paper-5.pdf) and modifying their techniques in the context of Anglican can become a good starting point. [This paper](http://www.robots.ox.ac.uk/~fwood/assets/pdf/perov-agi-2016.pdf) by Perov and Wood and [this paper](https://arxiv.org/pdf/1110.5667.pdf) seem to be related.
