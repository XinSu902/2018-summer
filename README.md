**This syllabus is effective as of Tuesday, June 05, 2018 at 11:02 AM**

DNSC 6290 Section 12<br/> Big Data <br/> the George Washington University <br/> Summer 2018
===========================================================================================

Course Information
------------------

-   **Instructors:** Marck Vaisman (marck at gwu.edu)
-   **Classroom:** Duques 254
-   **Time:** Wednesday 6:00-9:00pm
-   **TA's:** Madison Turano (madly9 at gwmail.gwu.edu)
-   **TA Office Hours:** Monday evenings

Course Description
------------------

Data is everywhere! Many times, it's just too big to work with traditional tools. This is a hands-on, practical workshop style course about using cloud computing resources to do analysis and manipulation of datasets that are too large to fit on a single machine and/or analyzed with traditional tools. The course will focus on Spark, MapReduce, the Hadoop Ecosystem and other tools.

You will understand how to acquire and/or ingest the data, and then massage, clean, transform, analyze, and model it within the context of big data analytics. You will be able to think more programmatically and logically about your big data needs, tools and issues.

Credit Hours
------------

This is a 3 credit graduate level course. You will spend approximately 3 hours per week in class. It is expected that you will spend approximately 2-3 hours of outside classroom activities (required readings, homework problems, completion of labs, quizzes, etc.) for each hour of class time. You will spend approximately 30 hours in instructional time, and approximately 100 hours in out-of-classroom time.

Course Objectives
-----------------

-   Operate big data tools and cloud infrastructure, including Spark, MapReduce, Hadoop and other tools in the big data ecosystem
-   Recognize and use ancillary tools that support big data processing, including git and the Linux command line
-   Setup and manage big data infrastructure and tools in the cloud on Amazon Web Services and Microsoft Azure
-   Identify broad spectrum resources and documentation to remain current with big data tools and developments
-   Execute a big data analytics exercise from start to finish: ingest, wrangle, clean, analyze and store
-   Be aware of the responsibilities that are associated with performing analysis of large datasets

Prerequisites
-------------

### Essential

-   Experience with R, Python, and SQL for reading files, manipulating and analyzing data. **Note:** We will use Python as the primary interface to Apache Spark, through [PySpark](https://spark.apache.org/docs/latest/api/python/index.html)
-   Understand programming concepts (flow control, input/output, variable assignment.) - Experience with git and GitHub

### Optional and Useful

-   Experience with the command line and terminal shell to navigate the file system, manipulate files (create, move, delete, etc.). Understand file permissions
-   Experience with remote computing via ssh
-   Understand shell executables

### Refresher Tutorials

It is highly recommended that you go through the following tutorials if you need a refresher or are new to the topics of git, the command line, and SQL. If these topics are new to you, you must take these online courses before the course begins.

-   [git - the simple guide](http://rogerdudler.github.io/git-guide/)
-   [DataCamp: Introduction to Git for Data Science](https://www.datacamp.com/courses/introduction-to-git-for-data-science)
-   [DataCamp: Introduction to Shell for Data Science](https://www.datacamp.com/courses/introduction-to-shell-for-data-science)
-   [DataCamp: Introduction to SQL for Data Science](https://www.datacamp.com/courses/intro-to-sql-for-data-science)

Books, Software and Cloud Resources
===================================

We have chosen several reference books for this course that cover different parts of the material. We will assign readings for each class from these books. These books are all available on [Safari Books Online](https://www.safaribooksonline.com/), and you should be able to access these resources. Our understanding is that as a GWU student, you have access to these resources.

We may also provide supplemental materials (articles, links, videos, etc.) to complement the books. \#\# Required Books (for assigned readings)

-   Benjamin Bengfort, Jenny Kim (2016). *Data Analytics with Hadoop: An Introduction for Data Scientists*. O'Reilly Media. ISBN: 9781491913703.
-   Bill Chambers, Matei Zaharia (2018). *Spark: The Definitive Guide*. O'Reilly Media. ISBN: 9781491912218.

Additional Recommended Books
----------------------------

-   Tomasz Drabas, Denny Lee (2017). *Learning Pyspark*. Packt Publishing. ISBN: 9781786463708.
-   Ofer Mendelevitch, Casey Stella, Douglas Eadline (2016). *Practical Data Science with Hadoop and Spark: Designing and Building Effective Analytics at Scale*. Addison-Wesley Professional. ISBN: 9780134024141.
-   Krishna Sankar (2016). *Fast Data Processing with Spark 2 - Third Edition*. Packt Publishing. ISBN: 9781784392574.

Cloud Resources
---------------

You will be using cloud resources on [Microsoft Azure](https://azure.microsoft.com/en-us/) and [Amazon Web Services](http://aws.amazon.com). We will discuss how to setup your account and environment in the first class session.

**Required For Windows Users Only**
-----------------------------------

If you have a Windows laptop, please download the [Babun Shell](http://babun.github.io/) before first class. Do not install, we will do it in class. Direct download link is here: [download link](http://projects.reficio.org/babun/download).

Mac Users (Optional)
--------------------

I recommend using [iTerm](https://www.iterm2.com/) as another Terminal application for your Mac. I've been using it for years and I love it. This is not required, but truly recommended.

Credit Cards
------------

You will need a credit card (not a debit card) to create an account on Amazon Web Services. If you do not have a credit card, you may consider getting a pre-paid VISA card which you can use as the credit card when you create the account.

Learning Activities and Evaluation
==================================

This is a hands-on, practical, workshop style course that provides opportunities to use the tools and techniques discussed in class. Although this is not a programming course per se, there is programming involved.

Lectures and In-Class Labs
--------------------------

Every class session will have a lecture portion and many sessions will have an in-class lab portion. Lab exercises are designed to get you familiar with the tools discussed in class. In these labs, we will work through simple examples. The completion of the in-class lab exercises is part of your attendance/participation portion of the grade.

Quizzes
-------

You will take online quizzes about the topics/ideas discussed in class and from the readings. The purpose of the quizzes is to reinforce your knowledge about the tools and platform and also to help you remember the nomenclature and terms used in class. The quizzes will be online through [Blackboard](https://blackboard.gwu.edu) and you can take them at your convenience within the established time window.

Assignments
-----------

You will be given problem sets as homework assignments. The goal of these problem sets is to use the big data tools to answer some questions about large datasets. The problem sets will build on the labs and will be much more elaborate. Deliverables from the problem sets will usually include code written for your programs and the output produced.

We will be using [GitHub Classroom](https://classroom.github.com/) for problem sets and assignment submissions. When an assignment is created, we will email you a link that will clone the assignment and create a private repository for you. You will perform your work within the repository and then push back to GitHub for submission. If you do not have a [GitHub](http://www.github.com) account, please create one.

Grading Rubric for Homework Assignments
---------------------------------------

-   We will look at the results files and the scripts. If the result files are exactly what is expected, in the proper format, etc., we may run your scripts to make sure they produce the output. If everything works, you will get full credit for the problem.
-   If the results files are not what is expected, or the scripts produce something different from what is expected, we will look at code and provide partial credit where possible and applicable.
-   Points will be deducted for each the following reasons:
    -   Instructions are not followed
    -   Output is not in expected format (not sorted, missing fields, wrong delimiter, unusual characters in the files, etc.)
    -   There are more files in your repository than need to be
    -   There are additional lines in the results files (whether empty or not)
    -   Files in repository are not the requested filename

Grading
-------

-   Problem Sets: 60% (4 problem sets at 15)
-   Quizzes: 30% (5 quizzes at 6%)
-   Attendance/Participation: 10% (attendance, in-class discussion, completion of in-class labs, active participation in online forums)

Course Calendar
===============

This calendar is subject to change. We will make make any changes known in advance.

<table style="width:100%;">
<colgroup>
<col width="1%" />
<col width="1%" />
<col width="33%" />
<col width="36%" />
<col width="17%" />
<col width="6%" />
<col width="1%" />
</colgroup>
<thead>
<tr class="header">
<th align="right">Session</th>
<th align="left">Date</th>
<th align="left">Topics</th>
<th align="left">Lab</th>
<th align="left">Reading</th>
<th align="left">Assignment</th>
<th align="left">Quiz</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="right">1</td>
<td align="left">May 23</td>
<td align="left">Welcome to Big Data: Course Overview, What is Big Data, Distributed Computing, Cloud Computing, High Performance Computing, the Infrastructure of the Cloud</td>
<td align="left">Create your cloud &amp; GitHub accounts. Setup your environment. Install software. Create and configure SSH keys.</td>
<td align="left"></td>
<td align="left"></td>
<td align="left"></td>
</tr>
<tr class="even">
<td align="right">2</td>
<td align="left">May 30</td>
<td align="left">AWS/Azure overview. Introduction to Hadoop &amp; MapReduce: Hadoop, Distributed filesystems, MapReduce programming model</td>
<td align="left">Start and connect to your first virtual machine on the cloud. Start and connect to a Hadoop cluster, run built-in Hadoop examples, examine the different user interfaces</td>
<td align="left">Required: (Bengfort, Kim) Chapter 2</td>
<td align="left"></td>
<td align="left"></td>
</tr>
<tr class="odd">
<td align="right">3</td>
<td align="left">Jun 06</td>
<td align="left">Hadoop Streaming</td>
<td align="left">Run the &quot;Hello World&quot; of Hadoop, the word count using Hadoop Streaming</td>
<td align="left">Required: (Bengfort, Kim) Ch. 3</td>
<td align="left">A01 released - due Sun 6/17</td>
<td align="left">Q01</td>
</tr>
<tr class="even">
<td align="right">4</td>
<td align="left">Jun 13</td>
<td align="left">Higher Level APIs: Pig and Hive</td>
<td align="left">Store a dataset in a Hive table, Run and example Pig job</td>
<td align="left">Required: (Bengfort, Kim) Ch. 6,8</td>
<td align="left">L02 released - due Sun 6/24</td>
<td align="left">Q02</td>
</tr>
<tr class="odd">
<td align="right">5</td>
<td align="left">Jun 20</td>
<td align="left">Introduction to Spark: What is Spark, Resilient Distributed Datasets, PySpark</td>
<td align="left">Start a PySpark session, Create RDDs, Operate on RDDs</td>
<td align="left">Required: (Chambers, Zaharia) Ch. 1-3, 12, 32; Recommended: (Sankar) p.122-126</td>
<td align="left"></td>
<td align="left">Q03</td>
</tr>
<tr class="even">
<td align="right">6</td>
<td align="left">Jun 27</td>
<td align="left">SparkSQL: SQL Review, Intro to SparkSQL</td>
<td align="left">Perform operations on Spark dataframes using SparkSQL</td>
<td align="left">Required: (Chambers, Zaharia) Ch. 10; Recommended: (Sankar) Ch. 8</td>
<td align="left">A03 released - due Sunday 7/15</td>
<td align="left"></td>
</tr>
<tr class="odd">
<td align="right">7</td>
<td align="left">Jul 11</td>
<td align="left">Working with Streaming Datasets: Spark Streaming</td>
<td align="left">Run real-time analytics on a data stream using Spark Streaming</td>
<td align="left">Required: (Chambers, Zaharia) Ch. 20, 21</td>
<td align="left"></td>
<td align="left">Q04</td>
</tr>
<tr class="even">
<td align="right">8</td>
<td align="left">Jul 18</td>
<td align="left">Machine Learning with Big Data: SparkML, Issues with ML algorithms on large datasets</td>
<td align="left">Build a predictive model with SparkML</td>
<td align="left">Required: (Chambers, Zaharia) Ch. 24, 25; Recommended: (Sankar) Ch. 11</td>
<td align="left">A04 released - due Sun 7/29</td>
<td align="left"></td>
</tr>
<tr class="odd">
<td align="right">9</td>
<td align="left">Jul 25</td>
<td align="left">Working with Graph Datasets: GraphX API for Spark</td>
<td align="left">Analyze a large graph using GraphX</td>
<td align="left">Required: (Chambers, Zaharia) Chapter 30; Recommended: (Sankar) Ch. 12</td>
<td align="left"></td>
<td align="left">Q05</td>
</tr>
<tr class="even">
<td align="right">10</td>
<td align="left">Aug 01</td>
<td align="left">TBD</td>
<td align="left">TBD</td>
<td align="left">TBD</td>
<td align="left"></td>
<td align="left"></td>
</tr>
</tbody>
</table>

**Class will not meet on Wednesday, July 4 (Independence Day Holiday).**

It is very likely we will cover all the topics in the syllabus. However, we have some room for flexibility depending on other topics of interest to the class. We may also have a guest lecturer from time to time.

Course Policies, Expectations, and Tools
========================================

General Policies
----------------

-   **Attendance:** Given the technical nature of this course, and the breadth of topics discussed, you must attend every class session. **Attendance will be tracked and is part of your grade.** Please contact us in advance if you are not able to attend class. Excused absences in advance will not affect your attendance grade.
-   **Participation:** We love participation. Raise your hand. Ask questions. Make comments. Challenge us. Acknowledge us. If we speak for three hours to a silent classroom, it is a lot more boring and tiring.
-   **Computer Usage:** You must bring your laptop to class to work on labs. Please refrain from other activities.
-   **E-mail:** We will try to respond to email within 24 hours. Please use email for personal discussions and not for homework, material or techincal questions. See next bullet:
-   **Online Discussion Boards:** Please use the discussion board on Blackboard for questions about the course, homework assignments, technical issues, etc. Answering individual questions submitted by email does not scale, and the likelihood of many students having the same question is high. Using the forums is a great resource for everyone.
-   **Name Tents:** You will be given a name tent. Please use it every class session and place it in front of you so we can get to know your name quicker.
-   **Cloud Resources:** You will create cloud accounts on Amazon Web Services and Microsoft Azure. You will get credits on both platforms that will be enough to support your coursework throughout the semester. **It is your responsibility to manage the credits and resources yourself. If you run out of credits because you do not shut down your resources, we cannot help you.**
-   **Homework Submission:** Homeworks take time, so please do not wait until the last minute to start them. Give yourself a several days to work on problem sets. While the tools have matured a lot over the years, there are cases where you will run into unforseen technical difficulties. All homework assignments have been thoroughly tested using the technical configuration provided in the assignment and they work. *"It didn't work for me"* is not an excuse. *"I lost my code because I didn't push to github"* is not an excuse. *"It took me too long because it was the first time I'm doing it"* is not an excuse. Homework due dates will not be extended, and late homeworks will incur a late penalty.

Open Door Policy
----------------

Please approach or get in touch with us if something is not working for you regarding the class, methods, etc. Our pledge to you is to provide the best learning experience possible.

Academic Integrity
------------------

The code of academic integrity applies to all courses in the George Washington School of Business. Please become familiar with the code. All students are expected to maintain the highest level of academic integrity throughout the course of the semester. Please note that acts of academic dishonesty during the course will be prosecuted and harsh penalties may be sought for such acts. Students are responsible for knowing what acts constitute academic dishonesty. The code may be found at <http://www.gwu.edu/~ntegrity/code.html>

You may collaborate with other students during in-class labs to facilitate collective learning. Regarding assignments, though, only limited collaboration is allowed.

-   You may discuss ideas on how to solve the problem with other students
-   You may work alongside other students
-   You may get help from other students if you are stuck and/or are having technical difficulties on steps to take, **BUT**:
-   You may not share code
-   All submitted code and scripts written must be your own - this will be checked
-   You must do all your work on your own cloud resources - this will be checked

University Policies and Support Services
========================================

Religious Accommodation
-----------------------

Students should notify faculty during the first week of the semester of their intention to be absent from class on their day(s) of religious observance. Faculty should extend to these students the courtesy of absence without penalty on such occasions, including permission to make up examinations. Faculty who intend to observe a religious holiday should arrange at the beginning of the semester to reschedule missed classes or to make other provisions for their course-related activities.

Disability Support Services (DSS)
---------------------------------

Any student who may need an accommodation based on the potential impact of a disability should contact the Disability Support Services office at 202-994-8250 in the Rome Hall, Suite 102, to establish eligibility and to coordinate reasonable accommodations. For additional information please refer to <http://gwired.gwu.edu/dss/>

Mental Health Services 202-994-5300
-----------------------------------

The University's Mental Health Services offers 24/7 assistance and referral to address students' personal, social, career, and study skills problems. Services for students include: crisis and emergency mental health consultations confidential assessment, counseling services (individual and small group), and referrals. <http://counselingcenter.gwu.edu>
