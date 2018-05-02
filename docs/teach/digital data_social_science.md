# Digital Data for Social Science
The design of this course is highly influenced by the course taught by John McLevey ("[Big Data and Social Science](http://www.johnmclevey.com/440/)" at the University of Waterloo) which I attended and also marked the beginning of my journey to computational social science. Some aspects of this course also resonate with the course by Laura Nelson ("[Digital Methods for Social Sciences and Humanities](http://www.lauraknelson.com/p/teaching.html)" at Northeastern University).

## Course Instructor Schedule
Instructor: Jude H. Kurniawan

Office: EV1-246

Office Hour: TBA

Class Schedule: TBA

## Calendar Description

## Course Overview


## Learning Objectives
The schedule section of the syllabus identifies the core learning objectives for every scheduled topic in the course.

## Materials
### Books:
Two books will be used extensively, Salganik and Foster et al. For students who are not familiar with Python, it is rudimentary to read Severance and practice along while watching his youtube tutorial videos.
* Matthew Salganik. 2018. [Bit by Bit: Social Research in the Digital Age](http://www.bitbybitbook.com/en/1st-ed/preface/). Princeton University Press. Currently free to read online.
* Ian Foster, Rayid Ghani, Ron S. Jarmin, Frauke Kreuter, Julia Lane (eds). 2016. Big Data and Social Science: A Practical Guide to Methods and Tools. CRC Press.
* Charles Severance. 2016. [Python for Everybody: Exploring Data In Python 3](https://www.py4e.com/book.php). Available for free online.
* Ryan Mitchell. 2015 / 2018. Web Scraping with Python: Collecting Data from the Modern Web. O’Reilly. This is optional.

If you have no previous knowledge of HTML or CSS, you might consider getting yourself a copy of Jon Duckett’s (2011) [HTML and CSS: Design and Build Websites.](http://www.htmlandcssbook.com/) It’s a nice (and beautiful) introduction that assumes no prior knowledge. Of course there are plenty of great resources online. You don’t need to buy the book. Your web scraping skills will advance rapidly as you become more familiar with HTML and CSS.

### Computing:
All students need to bring their laptops to every class. Let me know if this is an issue.
### Software:
Before coming to class, all students must install [Anaconda for Python 3.6](https://www.anaconda.com/download/) on your laptop. Anaconda will install most of Python pacakges for data science including Jupyter Notebook, which will be the "work space" for students in all lecture and tutorial sessions. As the lesson progresses, students will be asked to install other packages (e.g. metaknowledge, spaCy, gensim etc) as required.

**Important: All the computing we do in this course will be in Jupyter Notebooks**

## Assignments

|Assignment #|Description|%|
|---|---|---|
|Data Challenge #1|Web scaping, data parsing and cleaning|20|
|Data Challenge #2|Machine learning|20|
|Notebook Tutorial|Tutorial for any Python packages in Jupyter Notebook|20
|Hackathon| Bibliometric Project|30|
|Participation|Ongoing|10|

## Lecture Schedule
### Session 1: INTRODUCTION
This class meeting will introduce the core themes and learning objectives for the term. By the end of the class, you should (1) know what the key themes of the course are, (2) be able to clearly explain what I expect from you in the course, and (3) understand what you need to do to succeed. 
>Chapter 1 “Introduction” from Bit by Bit

>Supplementary / Optional: Chapter 1 “Introduction” from Big Data and Social Science

>Supplementary / Optional: David Lazer and Jason Radford. 2017. “Data ex Machina: Introduction to Big Data.” Annual Review of Sociology 43:19-39.

>Supplementary / Optional: Dalton Conley et al. “Big Data. Big Obstacles.” The Chronicle Review.

>Supplementary / Optional: Eszter Hargittai. 2015. “Is Bigger Always Better? Potential Biases of Big Data Derived from Social Network Sites.” The ANNALS of the American Academy of Political and Social Science 659(1).

### Session 2: SOCIAL SCIENCE WITH DIGITAL DATA
By the end of this class, you should be able to (1) explain how social scientists and data scientists use digital data in observational studies, and (2) describe the 10 common characteristics of “big data” discussed in Salganik: big, always on, nonreactive, incomplete, inaccessible, non-representative, drifting, algorithmically confounded, dirty, and sensitive.
>Chapter 2 “Observing Behavior” from Bit by Bit

### Session 3: GETTING STARTED WITH PYTHON
By the end of this class, you should be able to (1) assign things to variables, (2) execute code conditionally, and (3) explain what a function is, use built-in functions, and understand when, why, and how you might want to write your functions.
>Chapter 1 “Why should you learn to write programs?” from Python for Everyone

>Chapter 2 “Variables, expressions, and statements” from Python for Everyone

>Chapter 3 “Conditional execution” from Python for Everyone

>Chapter 4 “Functions” from Python for Everyone

>Supplementary / Optional: Watch and follow along with Jessica McKellar’s “[A Hands-On Introduction to Python for Beginning Programmers](https://www.youtube.com/watch?v=rkx5_MRAV3A).” If you have no previous Python background, I recommend watching and following along with McKellar’s tutorial before coming to class.

>Supplementary / Optional: Watch Brian Granger, Chris Colbert, and Ian Rose’s 2017 talk “[JupyterLab: The Evolution of the Jupyter Notebook](https://www.youtube.com/watch?v=w7jq4XgwLJQ)” to get a sense of what you can do with Jupyter Lab.

### Session 4: GETTING STARTED WITH PYTHON
By the end of this class, you should be able to (1) understand iteration in Python, (2) manipulate strings, and (3) understand basic data structures (lists, dictionaries, and tuples).
>Chapter 5 “Iteration” from Python for Everyone

>Chapter 6 “Strings” from Python for Everyone

>Chapter 8 “Lists” from Python for Everyone

>Chapter 9 “Dictionaries” from Python for Everyone

>Chapter 10 “Tuples” from Python for Everyone

### Session 5: GETTING STARTED WITH PYTHON
By the end of this class, you should be able to (1) read, create, open, modify, and save files; and (2) work with data in the form of Pandas dataframes.
>Chapter 7 “files” from Python for Everyone

>Watch Daniel Chen’s SciPy 2016 tutorial [Introduction to Pandas](https://www.youtube.com/watch?v=dye7rDktJ2E).

### Session 6: WEB SCRAPING AND CRAWLING
By the end of this class, you should be able to (1) understand more complex HTML markup, (2) explain how CSS works, (3) understand how to collect data from websites by scraping or using Application Programming Interfaces (API), and (4) put your new knowledge of HTML and CSS to work in developing your web scraper that also crawls.
>Chapter 2 “Working with Web Data and APIs” from Big Data and Social Sciences

>Chapter 1 “Your First Web Scraper” from Web Scraping with Python

>Chapter 2 “Advanced HTML Parsing” from Web Scraping with Python

>Chapter 3 “Starting to Crawl” from Web Scraping with Python

>Watch Corey Schafer’s [Beautiful Soup tutorial](https://www.youtube.com/watch?v=ng2o98k983k)

>Supplementary / Optional: Watch Ryan Mitchell’s DEF CON 23 talk “[Separating Bots from the Humans](https://www.youtube.com/watch?v=PADKIdSPOsc).” I suggest watching this video if you really want to get into scraping complex web pages. If the material we have covered so far is all new to you, this video may be a bit too advanced, but it’s still worth watching.

### Session 7: PARSING DOCUMENTS AND CLEANNG 'DIRTY' DATA
By the end of this class, you should be able to (1) parse data from documents rather than web pages, and (2) clean up messy unstructured data from web pages and documents.

>Chapter 6 “Reading Documents” from Web Scraping with Python

>Chapter 7 “Cleaning Your Dirty Data” from Web Scraping with Python

### Session 8: ASKING QUESTIONS
By the end of this class, you should be able to (1) describe the role that survey methods and the ‘total survey error framework’ play in the digital age; (2) accurately describe historical changes in sampling strategies, and explain why Salganik thinks new approaches to non-probability sampling differ from earlier approaches; (3) describe innovations in how we ask questions; and (4) differentiate between “enriched asking” and “amplified asking.”

>Chapter 3 “Asking Questions” from [Bit by Bit](http://www.bitbybitbook.com/en/preface/)

>Watch Matt Salganik’s 2017 talk [“Survey research in the digital age”](https://www.youtube.com/watch?v=LEbn3_pXvmw) from the Summer Institute in Computational Social Science

>Supplementary / Optional: Watch Chris Bail’s 2017 talk [“Apps for Social Science Research”](https://www.youtube.com/watch?v=8DBLnYABAMQ&t=258s) from the Summer Institute in Computational Social Science

>Supplementary / Optional: Christopher Bail. 2015. [“Taming Big Data Using App Technology to Study Organizational Behavior on Social Media.”](http://journals.sagepub.com/doi/abs/10.1177/0049124115587825) Sociological Methods & Research 46(2):1-29.

>Supplementary / Optional: Read Chapter 10 “Errors and Inference” from Big Data and Social Science

### Session 9: EXPERIMENTS AND MASS COLLABORATIONS
By the end of this class, you should be able to (1) explain the role of experiments in social science and data science and explain how they are changing in the digital age, and (3) explain the role of mass collaborations in social science and data science and explain how they are changing in the digital age.

>Chapter 4 “Running Experiments” from Bit by Bit

>Chapter 5 “Creating Mass Collaboration” from Bit by Bit

>Watch Devah Pager’s overview of her experimental audit study [“The Mark of a Criminal Record”](https://scholar.harvard.edu/files/pager/files/pager_ajs.pdf)

>Supplementary / Optional: Devah Pager 2003 “The Mark of a Criminal Record.” American Journal of Sociology. 108(5):937-975.

### Session 10: MACHINE LEARNING AND COMPUTATIONAL TEXT ANALYSIS (PART ONE)
By the end of this class, you should be able to (1) characterize the general types of problems that machine learning methods can address, (2) describe how machine learning fits into the larger analysis landscapes of data science and computational social science, (3) prepare unstructured text for a computational analysis.

>Gabe Ignatow and Rada Mchalcea. 2018. Pages 99 - 130 in Text Mining: Research Design, Data Collection, and Analysis. SAGE. Chapters cover basic text processing and supervised learning. It is fine to skim the chapter on supervised learning methods. I want you to have a high-level understanding of the general processes and goals. We will get into specific methods later, using concrete examples of applications.

>James Evans and Pedro Aceves. 2016. “Machine Translation: Mining Text for Social Theory.” Annual Review of Sociology. 42:21–50.

>Pages 176 - 187 from John McLevey and Reid McIlroy-Young (2017) [“Introducing metaknowledge: Software for computational research in information science, network analysis, and science of science.”](http://www.johnmclevey.com/pdfs/research/JOI2017.pdf) Journal of Informetrics 11:176-197.

>Supplementary / Optional: NetLab blog post by John McLevey [http://networkslab.org/2017/08/29/2017-08-29-mkrecords/](http://www.johnmclevey.com/440/%22Getting%20Started%20with%20Metaknowledge%22)

>Supplementary / Optional: Justin Grimmer and Brandon Stewart. 2013. “Text as Data: The Promise and Pitfalls of Automatic Content Analysis Methods for Political Texts.” Political Analysis. 1-31.

>Supplementary / Optional: David Zentgraf [“What every programmer absolutely, positively needs to know about encodings and character sets to work with text”](http://kunststube.net/encoding/)

>Supplementary / Optional: Chapter 6 “Machine Leaning” from Big Data and Social Science

>Supplementary / Optional: Alex Hanna. 2017. [“MPEDS: Automating the Generation of Protest Event Data”](https://osf.io/preprints/socarxiv/xuqmv). SocArXiv. osf.io/preprints/socarxiv/xuqmv.

>Supplementary / Optional: Aurélien Géron (2017) Chapter 1 “The Machine Learning Landscape” from Hands-On Machine Learning with Scikit-Learn and TensorFlow.

>Supplementary / Optional: Chapter 1 from Alex Smola and S.V.N. Vishwanathan (2008) [Introduction to Machine Learning](http://alex.smola.org/drafts/thebook.pdf). Cambridge University Press.

>Supplementary / Optional: Michael Smith (2017) [“How Canada has emerged as a leader in artificial intelligence.”](https://www.universityaffairs.ca/features/feature-article/canada-emerged-leader-artificial-intelligence/) University Affairs

>Supplementary / Optional: Chris Albon’s [“Machine Learning Flashcards”](https://machinelearningflashcards.com/)

>Supplementary / Optional: Watch Hilary Mason’s 2015 keynote address on [machine intelligence at the Grace Hopper Celebration of Women in Computing.](https://www.youtube.com/watch?v=Fo7pUJxqLQU)

### Session 11: MACHINE LEARNING AND COMPUTATIONAL TEXT ANALYSIS (PART TWO)

>Watch Jake VanderPlas: [Machine Learning with Scikit Learn](https://www.youtube.com/watch?v=HC0J_SPm9co&t=4760s)
>Watch Patrick Harrison tutorial on spaCy: [Modern NLP in Python](https://www.youtube.com/watch?v=6zm9NC9uRkk&t=4145s)


### Session 12: MACHINE LEARNING AND COMPUTATIONAL TEXT ANALYSIS (PART THREE)

### Session 13: UNDERSTANDING NETWORK ANALYSIS

### Session 13: NETWORK ANALYSIS USING NETWORKX


### Session (optional): AGENT-BASED MODELS IN PYTHON
These sessions will (1) review some of the fundamental theory and concepts information agent-based models and other simulation methods in the social sciences, (2) review the paradigm of object-oriented programming, and (3) explain how to develop simple agent-based models in Python.
>Macy and Willer (2002) “From Factors to Actors: Computational Sociology and Agent-Based Modeling.” Annual Review of Sociology. 28:143-166

>“What Is Agent-Based Modeling?” from Wilensky and Rand (2015) An Introduction to Agent-Based Modeling

>Nicky Case’s online game “[The Evolution of Trust](http://ncase.me/trust//).” Take about 30 minutes to play.

>“Creating Simple Agent-Based Models” from Wilensky and Rand (2015) An Introduction to Agent-Based Modeling.

