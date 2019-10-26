# CMPSC 100-03: Group Project

* Assigned: 28 October 2019
* Due: Various parts on various dates; see below
* Point value: 100 pts

## Project description

This semester, in the course of learning fundamental computational concepts using Java, you've been using structured, semi-guided exercises to explore topics. This group project invites you to explore and expand your knowledge in greater detail by applying your knowledge to a discipline-specific problem chosen from a wide variety of subject areas, listed below. Because this is a group project, you will also explore using GitHub and the git version control system (VCS) as a collaborative tool.

This project has three required steps:

* Submission of a proposal
* Submission of a technical report
* A buildable, runnable set of (at minimum) three (3) files

Projects will be graded using the following rubric:

|:----Area----:|:-----Percentage weight-----:|:-----Points possible-----:|
| Code Quality | 50%                         | 50 pts.                   |
| Documentation| 35%                         | 35 pts.                   |
| Teamwork     | 15%                         | 15 pts.                   |

## Helpful reading

To ensure complete preparation for completing this assignment, review all of the chapters covered to this point in the course (up to and including the date of assignment for this project). As we cover new material, you will likely choose to incorporate it into your thinking and development. In some cases, new topics may replace or revise your problem-solving methods. If your group would like additional tutorials or guidance for developing your project using any topic, please schedule office time (as a group) for us to review and discuss application of concepts.

In addition, there may exist concepts, modules, or third-party classes not covered in this course. You are welcome to use these provided that you document how they are used and ensure that you are not merely taking something "off the shelf" (i.e. substituting someone else's solution for your chosen project). Often, development requires going well beyond your current knowledge to produce a high-quality product.

## Required deliverables

### Part 1: Proposal

* Due: 4 November 2019

This document, to be completed using the `proposal.md` file in the `writing` directory, should:

* Be composed of 4 paragraphs
* Contain at least four headings:
    * Title
    * Abstract
    * Description
    * Task list and plan
* Contain at least 500 words
* Contain at least 1 image
* Contain at least 1 list

> Note: Before submitting this proposal, your project needs to be approved by the instructor. I highly suggest getting approval _early_ -- as this will give your group the most time to complete your work, and not create a situation in which you're pressed for time.

#### Title

The title should be an informative, concise, and professionally appropriate name for your project.

#### Abstract

An abstract is, essentially, a high-level summary of your project. While the abstract does not go too far into details, a brief description of the kind of program your group is making and your motivations for choosing this topic/issue are relevant here.

#### Description

This section should be a detailed and thorough explanation of how you plan your program to work and the roles of its various parts. Diagrams and clear, concise writing are helpful here. The section could potentially also include code samples or _pseudocode_-based discussion.

### Part 2: Project Update and Demo

* Due: 18 November 2019

On the date listed above, your group will demonstrate progress during the laboratory session scheduled for that day. In addition, your group should provide a brief, 1 paragaph update with a list of remaining tasks and a plan for completing them in the `update.md` file located in the `writing` directory. This update should be _no fewer_ than 350 words.

### Part 3: Project Submission

* Due: 6 December 2019

Your project should be submitted to your group's GitHub repository by the end of the day (11:59 PM) on this date. This should include all of the writing above in addition to responses to questions in the `reflection.md` file, located in the `writing` directory. This writing should:

* Have at least 5 headings
* 750 words
* At least 1 code block (though you _will_ use more)

#### Code requirements

To ensure that you and your partner have mastered the concepts discussed in this course, your project's source code should adhere to the following requirements. These requirements may be modified, at the discretion of the course instructor, only if a student receives prior permission and documents this approval in the final report and the source code. Without prior approval, all submitted programs should contain at least three Java classes that consist in total of at least five methods in addition to the main method. The final project's source code should include examples
of the declaration and use of at least three different data types (e.g., `int`, `String`, and `boolean`). The program should also include conditional logic, in the form of if or switch statements, and one or more iteration constructs, expressed as `while`, `do-while`, or `for` loops. Finally, the programs must also use either an array, an `ArrayList`, or both.

#### A note on testing

Due to the variety of topics and projects groups may choose, I can only write concrete, comprehensive grading criteria for the reports and other writing submissions. Without your help, I can only test that:

* The project runs
* The project builds without legibility/style issues

As part of the final submission, I require that you write a series of test cases for which at least some part of the project's output is known. You will do this in consultation with me (as a group).

## Types

Groups are free to choose any of the following types. However, keep in mind that _each group's project must be approved by the instructor_. This means that before you submit your proposal, you need to meet with me.

### Tips for choosing a project

When establishing a goal to achieve or problem to solve, keep in mind that the limited time remaining in this course may also limit the scope (i.e. size, complexity) of the project you take on. Groups are responsible for assessing the feasibility of their projects, though I am glad to help if the practicality or possibility of an idea is in doubt.

### Cryptography and Cryptanalysis

Explore a topic in the felds that make up the "art and science of sending and decoding secret messages." This project invites you and your partner to
implement and test several cryptography and/or cryptanalysis systems. To start, you should investigate, implement, and test ciphers such as the Caesar and Vigenere ciphers. Then, you should use your ciphers to demonstrate that you can successfully send secret messages through, for instance, an email server. In addition to creating and testing these Java programs, your report should include a detailed explanation of how your chosen algorithms work.

### Interactive Storytelling

Leveraging your knowledge of file and console input and output, create a computer program that allows a person to engage with a "choose your own adventure"-style story or game. After reading in commands from the user, your program will display information about the world subject to exploration and act on the user's request. Along with creating and testing your program, your report should fully describe your interactive story and how you used, for instance, conditional logic and iteration to create it.

### Computational Literature

Your knowledge of Java also allows you to tell stories in a less interactive way, via the creation of a program which makes a literary object in the spirit of [https://nanogenmo.github.io/](NaNoGenMo). After reading various entries from the several years catalogued on the site and other examples of computational literature, create an outline of the kind of narrative your group is interested in creating. This project may also take on the form of making tools to address gaps in available frameworks or toolkits or providing solutions in areas where others have struggled. As it stands, there have not been many Java-based entries in prior years, so your work may be of academic interest to members of the community.

Coincidentally, November is the month that computational authors participate in the year's edition. Should your group choose this option and want to publish your entry, we can group 

### Computer Simulation

There are many physical or biological phenomena that are challenging to study in either a laboratory or a natural setting. As such, natural and social scientists may implement computer simulations that model these phenomena, often leading to additional insights into how the real systems operate. This project invites you and your partners to pick a phenomenon that you would like to simulate and then implement a full-featured simulation in the Java programming language. Your chosen phenomenon for simulation might involve the throwing of a ball, the vibration of a string, chemical reactions, or the interaction between predator and prey animals. In addition to implementing and running your simulation, your report should completely describe the phenomenon that your program models and explain how your implementation uses, for example, methods for random number generation.

### Performance Evaluation

Since it is often important to implement computer software that exhibits acceptable time and space overheads, this project invites students to use and/or extend performance evaluation software like System.nanoTime(). After finding, reading, and understanding textbooks and research papers on this topic, students who pick this project should identify a focus area and create a benchmarking tool. The final version of the framework should allow students to measure the performance of computations in Java, report those measurements to the user of the benchmarks, and support informed decision making about design and implementation trade-offs. Along with including the source code of the benchmarking framework, this project invites students to write a performance evaluation report.

### Software Testing

In response to the fact that real-world software often contains serious defects, this project encourages students to learn more about techniques that can find program errors before they are delivered to end-users. Students who choose this topic will investigate software testing tools, such as JUnit, and then create a software system that includes a test suite. In addition to implementing Java classes and methods that provide the main
functionality, you will, as part of this project, also write tests that assess the correctness of the aforementioned methods. If your team picks this project, you should submit programs and test suites in addition to a report that explains your approach to software testing.

### Student-designed projects

Your group will develop an idea for their own project that focuses on one or more real-world topics in the field of computer science. After receiving the course instructor's approval for your idea, you will complete the project and report on your results.

## Evaluating projects

Group projects will be graded on the basis of:

* Quality of final code
* Quality of technical writing up to, and including, final `reflection.md`
* Team member participation
   * I will survey your `git` commit record on GitHub to see who/how/how often a team member contributes

### Quality of code

"Quality" here represents code's legibility, workability, and documentation (including comments within code). Projects which demonstrate success in all three areas will recieve the highest marks here. Code which does not meet the following criteria will not achieve high scores in quality:

* Frequent and descriptive single and multi-line comments
* Absence of checkStyle errors (i.e. passes `gradle build` or `gradle check`)
* Code has no (or very few) cases where critical failures occur

### Quality of technical writing

The files contained within the `writing` folder should display clear understanding of progress and product. This means that these files are complete, descriptive, insightful, and accurate. All writing sould give me a window into the challenges and successes that teams experienced as part of the process of conceptualizing and developing projects.

In high-quality technical documentation, I expect to see:

* Clear instructions for running and building projects
* Frequent use of headings and other Markdown structures to create clarity and structure
* Objective, focused writing which gives insight into the design and use of the software created

### Participation

In addition to maintaining a watchful eye over GitHub `commit` logs, you will complete end-of-project surveys in which you rate not only yourself, but your teammates, describing the outcome of your project in response to both quantitative and qualitative prompts.