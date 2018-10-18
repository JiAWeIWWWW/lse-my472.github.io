---
papersize: a4
documentclass: scrartcl
classoption: DIV=14
colorlinks: true
---

![LSE](images/lse-logo.jpg)
# MY472 Data for Data Scientists

### Michaelmas Term 2018

### Instructors

* [Pablo Barberá](mailto:P.Barbera@lse.ac.uk), Department of Methodology.  *Office hours*: Fridays 12.30-14.30, COL.7.10 (book via LSE for You)

* [Akitaka Matsuo](mailto:A.Matsuo@lse.ac.uk), Department of Methodology.  *Office hours*: Tuesdays 11.30-12.30, COL.8.02 (book via LSE for You. Only weeks 3, 4, 5, 9)

### Course Information

* Lectures on Tuesdays 09:00–11:00 in 32L.LG.03
* Classes on:
    - Thursdays 9:30-11:00 TW2.4.03
    - Fridays 15:00-16:30 STC.S018

No lectures or classes will take place during School Reading Week 6.

### Course Description

This course will cover the principles of digital methods for storing and structuring data,
including data types, relational and non­relational database design, and query languages.
Students will learn to build, populate, manipulate and query databases based on datasets
relevant to their fields of interest. The course will also cover workflow management
for typical data transformation and cleaning projects, frequently the starting point
and most time­-consuming part of any data science project.  This course uses a
project-based learning approach towards the study of performance computation and
group­-based collaboration, essential ingredients of modern data science projects.
The coverage of data sharing will include key skills in on-line publishing, including
the elements of web design, the technical elements of web technologies and web programming,
as well as the use of revision-control and group collaboration tools such as GitHub.

### Objectives

In this course, we introduce principles and applications of the electronic
storage, structuring, manipulation, transformation, extraction, and
dissemination of data. This includes data types, database design,
data base implementation, and data analysis through structured queries.
Through joining operations, we will also cover the challenges of data
linkage and how to combine datasets from different sources. We begin
by discussing concepts in fundamental data types, and how data is stored
and recorded electronically.

Cloud computing and online collaboration tools forms the second part of this
course, along with the tools and technologies that underlie them. Students will
firstly learn the basics of cloud computing that can serve various purposes such
as secure hosting of webpages and web services and on-demand computations for
data analysis and then learn how to set up a cloud-computing environment through
Amazon Web Services, a popular cloud platform.  Collaboration and the
dissemination and submission of course assignments will use GitHub, the popular
code repository and version control system. The course also provides in­depth
look at various common data-types on the Internet such as various mark­up languages
(e.g. HTML and XML) and JSON.  Students also study the fundamentals of
acquisition and management of the data from the Internet through both scraping of
websites and accessing APIs of online databases and social network services.

In the third part of the course, we will learn the data management and basic
methodology of data analysis. We will cover database design, especially
relational databases, using substantive examples across a variety of fields.
Students are introduced to SQL through MySQL, and programming assignments in
this unit of the course will be designed to insure that students learn to
create, populate and query an SQL database. We will introduce NoSQL using
MongoDB and the JSON data format for comparison. For both types of database,
students will be encouraged to work with data relevant to their own interests as
they learn to create, populate and query data. In the next section of the data
section of the course, we will step through a complete workflow including data
cleaning and transformation, illustrating many of the practical challenges faced
at the outset of any data analysis or data science project. The course will be
concluded with the discussion of performance issues in computation with the
particular focus on parallel computing.


### Assessment

#### Formative coursework

Students will be expected to produce five weekly, structured problem sets with a
beginning component to be started in the staff-led lab sessions, to be
completed by the student outside of class. Answers should be formatted and
submitted for assessment. One or more of these problem sets will be completed
in collaboration with other students.

#### Summative Assignments

Take home exam (50%) and in class assessment (50%).

Student problem sets will be marked and will provide 50% of the mark.

#### Assessment criteria

Assignments will be marked using the following criteria:

􏰀- 70–100: Very Good to Excellent (Distinction). 􏰀 Perceptive, focused use of a good depth of material with a critical edge. Original ideas or structure of argument. 􏰀
- 60–69: Good (Merit).  Perceptive understanding of the issues plus a coherent well-read and stylish treatment though lacking originality
􏰀- 50–59: Satisfactory (Pass).􏰀 A “correct” answer based largely on lecture material. Little detail or originality but presented in adequate framework. Small factual errors allowed.
- 30–49: Unsatisfactory (Fail) and 0–29: Unsatisfactory (Bad fail). 􏰀 Based entirely on lecture material but unstructured and with increasing error component. Concepts are disordered or flawed. Poor presentation. Errors of concept and scope or poor in knowledge, structure and expression.

Some of the assignemnts will involve shorter questions, to which the answers can be relatively unambiguously coded as (fully or partially) correct or incorrect. In the marking, these questions may be further broken down into smaller steps and marked step by step. The final mark is then a function of the proportion of parts of the questions which have been answered correctly. In such marking, the principle of partial credit is observed as far as feasible. This means that an answer to a part of a question will be treated as correct when it is correct conditional on answers to other parts of the question, even if those other parts have been answered incorrectly.

### Schedule

#### Week 1, October 2 (PB). [Introduction to data](https://github.com/lse-my472/lectures/blob/master/week01/)

In the first week, we will introduce the basic concepts of the course, including how data is recorded, stored, and shared. Because the course relies fundamentally on GitHub, a collaborative code and data sharing platform, we will introduce the use of git and GitHub, using the lab session to guide students through in setting up an account and subscribing to the course organisation and assignments.

This week will also introduce basic data types, in a language-agnostic manner, from the perspective of machine implementations through to high-level programming languages. We will then focus on how basic data types are implemented in R.

Lecture materials:

- SLIDES: [Overview of the course and introduction to data](https://github.com/lse-my472/lectures/raw/master/week01/MY472-week01.pdf)
- R example: [Introduction to RMarkdown](https://github.com/lse-my472/lectures/blob/master/week01/01-RMarkdown.rmd)
- R example: [vectors, lists, data frames](https://github.com/lse-my472/lectures/blob/master/week01/02-intro-to-R.rmd)

**Readings:**

*Required readings*:
* Wickham, Hadley.  Nd.  _Advanced R_, 2nd ed.  Ch 3, [Names and values](https://adv-r.hadley.nz/names-values.html), Chapter 4, [Vectors](https://adv-r.hadley.nz/vectors-chap.html), and Chapter 5, [Subsetting](https://adv-r.hadley.nz/subsetting.html). (Ch. 2-3 of the print edition),
* [GitHub Guides](https://guides.github.com), especially: "Understanding the GitHub Flow", "Hello World", and "Getting Started with GitHub Pages".
* GitHub.  "[Markdown Syntax](https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf)" (a cheatsheet).

*Further Readings*:
* Lake, P. and Crowther, P. 2013. _Concise guide to databases: A Practical Introduction_.  London: Springer-Verlag.  Chapter 1, [Data, an Organizational Asset](https://books.google.co.uk/books?id=SuK2BAAAQBAJ&pg=PA301&lpg=PA301&dq=Concise+Guide+to+Databases+pdf&source=bl&ots=pEJj8miMrf&sig=3nrRgpk3kF7fXzcWUWpJ_uzpfl0&hl=en&sa=X&ved=0ahUKEwiAkM3JrbHWAhXE7xQKHWseCZAQ6AEISzAH#v=onepage&q=Concise%20Guide%20to%20Databases%20pdf&f=false)
* Nelson, Meghan.  2015.  "[An Intro to Git and GitHub for Beginners (Tutorial).](http://product.hubspot.com/blog/git-and-github-tutorial-for-beginners)"
* Jim McGlone, "[Creating and Hosting a Personal Site on GitHub
A step-by-step beginner's guide to creating a personal website and blog using Jekyll and hosting it for free using GitHub Pages.](http://jmcglone.com/guides/github-pages/)".

*Lab*: [**Working with git and GitHub**](https://github.com/lse-my472/pset1)
* Installing git and setting up an account on GitHub
* How to complete and submit assignments using GitHub Classroom
* Forking and correcting a broken RMarkdown file
* Cloning a website repository, modifying it, and publishing a personal webpage


#### Week 2, October 9 (PB). [The shape of data](https://github.com/lse-my472/lectures/blob/master/week02/)

This week moves beyond the rectangular format common in statistical datasets, modeled on a spreadsheet, to cover relational structures and the concept of database normalization. We will also cover ways to restructure data from "wide" to "long' format, within strictly rectangular data structures. Additional topics concerning text encoding, date formats, and sparse matrix formats are also covered.

**Readings**:
* Wickham, Hadley and Garett Grolemund.  2017.  _R for Data Science: Import, Tidy, Transform, Visualize, and Model Data_.  Sebastopol, CA: O'Reilly.  [Part II Wrangle](http://r4ds.had.co.nz/wrangle-intro.html), [Tibbles](http://r4ds.had.co.nz/tibbles.html), [Data Import](http://r4ds.had.co.nz/data-import.html), [Tidy Data](http://r4ds.had.co.nz/tidy-data.html) (Ch. 7-9 of the print edition).
* The [**reshape2** package](http://had.co.nz/reshape/) for R.

Lecture notes:

- Lecture week 2: the shape of data
- R example: reshaping data in R

*Lab*: **Reshaping data in R**

*Assignment 1*: **Data cleaning in R**. Deadline: October 19.


#### Week 3, October 16 (AM). [Cloud computing](https://github.com/lse-my472/lectures/blob/master/week03/)

In this week, we focus on the setup of computation environments on the Internet. We will introduce the cloud computing concepts and learn why the big shift to the cloud computing is occurring in the industry and how it is relevant to us as data scientists. In the lab, we will have an introduction to the cloud environment setup using Amazon Web Services. We will sign up an account, launch a cloud computing environment, create a webpage, and set up a statistical computing environment.

Lecture notes:

- Lecture week 3: Cloud computing overview

**Readings**

*Required Readings*:

* Rajaraman, V. 2014. "[Cloud Computing.](https://www.ias.ac.in/article/fulltext/reso/019/03/0242-0258)" Resonance 19(3): 242–58.
* AWS: [What is cloud computing](https://aws.amazon.com/what-is-cloud-computing/).
* Azure: [Developer guide](https://docs.microsoft.com/en-us/azure/guides/developer/azure-developer-guide).

*Further Readings*:
* Puparelia, Nayan. 2016. "Cloud Computing." MIT Press. Ch. 1-3.
* Botta, Alessio, Walter De Donato, Valerio Persico, and Antonio Pescapé. 2016. "[Integration of Cloud Computing and Internet of Things: A Survey.](http://iranarze.ir/wp-content/uploads/2017/03/6229-English-IranArze.pdf)" Future Generation Computer Systems 56: 684–700.

*Lab*: **Working with AWS**
* Setup AWS account
* Secure the account
* Configure EC2 instance
* Work with EC2 instance
    - Login EC2-Linux Console
    - Set up a web server
    - Install R, some packages
    - Stop the instance
* [Link to the github classroom](https://classroom.github.com/a/kHWz58_a)


#### Week 4, October 23 (AM). [Basics of HTML and CSS](https://github.com/lse-my472/lectures/blob/master/week04/)

From week 4 to week 7, we will learn how to get the data from the Internet. This week introduces the basics, including markup languages (HTML, XML, and Markdown) and other common data formats such as JSON (Javascript Object Notation).  We also cover basic web scraping, to turn web data into text or numbers.  We will also cover the client-server model, and how machines and humans transmit data over networks and to and from databases.

**Readings**

*Required Readings*:

* Lazer, David, and Jason Radford. 2017. “[Data Ex Machina: Introduction to Big Data.](https://doi.org/10.1146/annurev-soc-060116-053457)” _Annual Review of Sociology_ 43(1): 19–39.
* Howe, Shay. 2015.  [_Learn to Code HTML and CSS: Develop and Style Websites_](http://learn.shayhowe.com/html-css/).  New Riders.  Chs 1-8.
* Kingl, Arvid. 2018. [_Web Scraping in R: rvest Tutorial_](https://www.datacamp.com/community/tutorials/r-web-scraping-rvest).

*Further Resources*:

* Munzert, Simon, Christian Rubba, Peter Meissner, and Dominic Nyhuis D. 2014. _Automated Data Collection with R: A Practical Guide to Web Scraping and Text Mining_. Hoboken, NJ/Chichester, UK:Wiley & Sons. Ch. 2-4, 9.
* Severance, Charles Russell. 2015. [_Introduction to Networking: How the Internet Works_](http://www.net-intro.com).  Charles Severance, 2015.
* Duckett, Jon. 2011. _HTML and CSS: Design and Build Websites_.  New York: Wiley.

*Assignment 2*: **Webscraping**. Deadline: November 2.


#### Week 5, October 30 (AM). [Using data from the internet](https://github.com/lse-my472/lectures/blob/master/week05/)

Continuing from the material covered in Week 4, we will learn the advanced topics in scraping the web. The topics include the scraping documents in XML (such as RSS), scraping websites beyond the authentication, and websites with non-static components.

**Readings**

*Required Readings*:
* Sai Swapna Gollapudi. 2018. [_Learn Web Scraping and Browser Automation Using RSelenium in R_](https://analyticsprofile.com/business-analytics/learn-web-scraping-and-browser-automation-using-rselenium-in-r/).
* Wickham, Hadley. 2015. [_Parse and process XML (and HTML) with xml2_](https://blog.rstudio.com/2015/04/21/xml2/)
* Mozilla Developer Web Docs. [_What is JavaScript_](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/What_is_JavaScript).
* TBA

*Further Readings*:
* Schouwenaars, Filip. 2015. [_Web Scraping with R and PhantomJS_](https://www.datacamp.com/community/tutorials/scraping-javascript-generated-data-with-r).
* Mozilla Developer Web Docs. [_A First Splash into JavaScript_](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/A_first_splash).


#### Week 6, November 6. Reading week. No class.


#### Week 7, November 13 (PB). [Working with APIs](https://github.com/lse-my472/lectures/blob/master/week07/)


*Assignment 3*: **APIs**. Deadline: November 23.

#### Week 8, November 20 (PB). [Creating and managing databases](https://github.com/lse-my472/lectures/blob/master/week08/)


#### Week 9, November 27 (AM). [Interacting with online databases](https://github.com/lse-my472/lectures/blob/master/week09/)

*Assignment 4*: **Databases**. Deadline: December 7.


#### Week 10, December 4 (PB; classes with AM). [Exploratory data analysis](https://github.com/lse-my472/lectures/blob/master/week10/)


#### Week 11, December 11 (PB). [Parallel computing](https://github.com/lse-my472/lectures/blob/master/week11/)

*Assignment 5*: **Data analysis**. Deadline: December 21.

*Take-home exam*. Deadline: January 18.