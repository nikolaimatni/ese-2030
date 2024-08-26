---
title: Welcome to ESE 2030
subject: Fall 2024 - ESE 2030
subtitle: Linear Algebra with Applications to Engineering and AI
short_title: ESE 2030
authors:
  - name: Nikolai Matni
    affiliations:
      - Dept. of Electrical and Systems Engineering
      - University of Pennsylvania
    email: nmatni@seas.upenn.edu
license: CC-BY-4.0
keywords: ese 2030, linear algebra
numbering:
    heading_1: false
    heading_2: false
    heading_3: false
---

## Welcome to the Fall 2024 semester of ESE 2030!

All of the information on this page and the next can be found in the [syllabus](./24F-ESE2030-Syllabus.pdf).

**Instructor**: Nikolai Matni, Assistant Professor, Dept. of ESE \
**TAs**: 	Owen Frausto, Eric Cao, Elliu Huang, Faraz Rahman, and more to come \
**Course website**: [https://nikolaimatni.github.io/ese-2030/ ](https://nikolaimatni.github.io/ese-2030/) \
**Lectures:** Tu/Th 5:15pm-6:45pm ET, LRSM Auditorium \
**Recitations:** Fr 1:45pm-3:15pm, LRSM Auditorium \
**Other resources:** We will use CANVAS to disseminate course materials, and Ed Discussion for class related discussions 

### Office Hours
All teaching staff (TAs, instructor) will hold 1 hour of office hours each week.  Times and locations will be posted on CANVAS.

### Course Description
This first course in linear algebra will introduce students to key concepts of the field, including but not limited to vectors, vector norms and inner products, matrices, matrix-vector and matrix-matrix multiplication, matrix inverses, solving systems of linear equations, vector spaces, orthogonality, least-squares, eigenvalues and eigenvectors, singular value decompositions, and principal component analysis.  These theoretical tools will be grounded in exciting problems from the sciences, engineering, machine learning, data science, logistics, and economics.  Through application-based case studies, you will be shown how to model problems using linear algebra and how to solve the resulting problem using standard Python scientific computing modules.  

### Prerequisites 
The official prerequisites for this class are 1. Programming: CIS 1100 or ENGR 1050 and 2. Math: MATH 1410.  If you have prior exposure to programming (in any language) at a level equivalent to CIS 1100, please fill out a permit request following these instructions, and we will approve your request.  We will be much less flexible about MATH 1410, as we assume you have had prior exposure to vectors, matrices, and solving systems of linear equations.

### Course Structure and Philosophy
Linear algebra is one of the most broadly applicable and useful branches of mathematics.  It underpins nearly every piece of modern engineering, economics, finance, data science, machine learning, and AI.  Even more exciting, given only a small amount of knowledge in linear algebra and a little bit of coding skills, you can start solving real-world problems!  Our goal in this class is to not just teach you linear algebra, but to also get you excited about what Linear Algebra can do for you as a scientist, engineer, data scientist, financial analyst, or AI researcher.  To meet this goal, we will take the following approach in terms of how material is presented to you across lecture notes, class time, recitations, and homework:
-	**The lecture notes**, which are available online (see below), are interactive Python Notebooks that present the core linear algebra concepts we will cover in class, as well as extra worked examples.  These online notes also provide you with:
    +	Small code snippets showing the basic Python syntax needed to implement the concepts you learn about in computer code.
    +	Real-world case studies showing you (a) how linear algebra can be used to model and solve important problems in engineering and AI, and (b) the accompanying Python code needed to implement these ideas for large-scale problems that are too big to work out by hand.  See the tentative schedule below for a list of the exciting case studies we’ll study this semester.
    + Every page of the online notes can be launched on to an online server with the click of a button to allow you to play with the code and explore how solutions change as parameters of the problem and solution are varied.  You will learn by doing!
- **In class**, we will focus on introducing the core concepts and definitions needed in linear algebra.  We will also work out simple examples that can be computed by hand to show you how to apply these new concepts, and help you understand what they mean.  We will also spend some time later in the class on how to formulate and analyze some of the most important applications of linear algebra.
-	**In recitation**, each week a TA will spend approximately half of the recitation going through simple worked examples that reinforce the concepts seen in class.  The other half of the recitation will be spent working through the case study from the online notes that illustrates how this week’s concepts can be applied to a real problem. Unfortunately, we don’t have time to go over these in class, so **it is very important for you to attend recitation!**
-	**In the homework**, which is assigned roughly weekly (see below for detailed schedule), you will get the chance to hone your new linear algebraic skills.  Part 1 of each homework will be a “Mechanics” section, in which you will practice applying the concepts learned that week to smaller problems for which solutions can be computed by hand.  Parts 2 and 3 of each homework will be your chance to apply linear algebra to solve a real problem. In Part 2, you will use the linear algebraic tools you’ve learned that week to model a problem from the sciences, engineering, finance, or AI, and propose and analyze solutions to it.  In Part 3, you will implement the solutions from Part 2 in code and see your hard work come to life.

#### The Role of Programming in this Course
You may have noticed that some form of programming permeates much of the class.  This is because computer code is how we bring math to life. In this class, we will use Python, which is an industry standard programming language for scientific computing.  We assume that you’ve taken _some form of programming course before_, so that you can read code and understand what it is doing, but that’s about it.  Our goal in this class is not to teach you how to program: doing that and teaching you linear algebra all within one semester would simply be too much!  Instead, we view programming as a means for showing you how the math you learn can be applied.  With that in mind, the only programming you will have to do will be in Part 3 of the homework assignments, which we have designed in highly structured way for you.  We will always give you code snippets showing you the syntax and functions you will need for the homework problem.  You will typically be asked to fill in some function implementations, and then use these functions to explore the properties of your solution.  Finally, we will be very generous in helping students in OHs with the coding aspects of the homework.

#### Which course should I take: ESE 2030 or Math 2400?
ESE 2030 and MATH 2400 both build on the linear algebra from MATH 1410 and cover roughly the same core topics typically seen during a first course in linear algebra.  The difference is mainly in how the material is presented. ESE 2030 teaches these concepts with an eye towards applications of linear algebra students in ESE, CIS, and other engineering/applied math disciplines are likely to encounter throughout their careers. While these applications are mentioned in MATH 2400, they are not emphasized as much, as MATH 2400 is designed to prepare students to use linear algebra as a tool to better understand ordinary differential equations (which we also cover in ESE), as well as partial differential equations in MATH 2410.  As to which course you should take: it depends! Both are excellent courses but are designed with very different audiences in mind.  We of course recommend that you take ESE 2030 if you are in completing a degree in SEAS, as we have designed this class with your needs in mind.

#### Our Promise
While we have made every effort possible to make this course as accessible and fun as possible, there is no getting around that doing well will require hard work.  You will learn a lot of new concepts quickly, and for many of you, the level of abstraction we will work will be a significant leap as compared to your previous classes.  But here is the payoff: if you attend class and recitations, work hard on your homework problems, and study well for your exams, you will get a good grade.  Even more importantly though, I promise you that doing well in this class **_will make the rest of your degree so much easier_**.  This is because ideas from this class will appear over and over and over across the 3000, 4000, and 5000 level courses you will take in the coming years.  If you spend the time to learn these ideas well now, you will have a solid foundation for the rest of your degree.  And as a bonus, the practical skills you’ll acquire in this class via the programming exercises will help you when you apply for internships!

### Course Materials
There is no official textbook or proprietary software needed for this class.  The course notes are available online at [https://nikolaimatni.github.io/ese-2030/](https://nikolaimatni.github.io/ese-2030/).  These are interactive Python Notebooks that present the mathematical content of the class supplemented with Python code snippets showing how to implement the concepts you’ll learn about.  The online notes also include extra worked examples, as well as real-world case studies allowing you to explore how linear algebra can be used to solve important problems in engineering and AI.

The online notes are entirely self-contained, but they are based on the following textbooks, which you may wish to refer to for optional supplemental reading:
-	_Applied Linear Algebra_, by Peter J. Olver and Chehrzad Shakiban, available [online](https://link.springer.com/book/10.1007/978-3-319-91041-3) (accessible via Penn institutional log in).
-	_Linear Algebra and its Applications_, by David C Lay, Judi McDonald, and Steven R Lay (available on course reserve at Van Pelt Library)
-	_Introduction to Linear Algebra_, by Gilbert Strang (available on course reserve at Van Pelt Library)
-	_Introduction to Applied Linear Algebra – Vectors, Matrices, and Least Squares_, by Boyd and Vandenberghe, available [online](https://web.stanford.edu/~boyd/vmls/).

We will share lecture notes, reading, assignments, and slides on CANVAS.  All programming exercises will be performed using Python Notebooks in the Google Colab environment.  We ask you to please not share course materials with those not registered in the class.

### Grading 
-	**Homework (25%)**: there will be 8 homework assignments.  They will be assigned weekly, handed out on Thursday at 5pm and due the following **Thursday at 11:59pm**.  There will be suitable breaks in assignments to accommodate the midterms and the Thanksgiving holiday weekend.  **No late assignments will be accepted whatsoever**.  Instead, we will only count 6 out of the 8 homework assignments towards your grade, meaning that if you so choose, you can skip up to 2 assignments without it negatively affecting your grade.  Each homework problem will be graded on a scale of 0-2: no points are awarded for a skipped problem, 1 point for a solid attempt, and 2 points for a mostly correct solution. 
-	**Midterm exam 1 (25%)**: the midterm will consist of an in-class written exam.  **Midterm 1 is scheduled for 10/01/2024**. The exam will be closed-book and closed-notes. However, you will be allowed a single sheet of standard-sized paper with you with anything you want written on it (double-sided). No electronic devices are allowed.  This midterm exam will cover the material covered in the first four weeks of class. 
-	**Midterm exam 2 (25%)**: the midterm will consist of an in-class written exam.  **Midterm 2 is scheduled for 11/07/2024**. The exam will be closed-book and closed-notes. However, you will be allowed a single sheet of standard-sized paper with you with anything you want written on it (double-sided). No electronic devices are allowed. This midterm exam will cover the material covered in weeks five to nine of class.
-	**Final exam (25%)**: there will be a synchronous final exam scheduled during the final exam period with time and date set by the Registrar.  It will be closed-book and closed-notes. However, you will be allowed a single sheet of standard-sized paper with you with anything you want written on it (double-sided). No electronic devices are allowed.  This is a cumulative exam covering the entire semester.

### Collaboration and AI Policy
-	**Homework**: You are allowed and in fact encouraged to **discuss homework problems with your peers**, but you must **conceptualize and write up** your own homework solutions and code to hand in.  If you discuss a problem with someone for more than five minutes, you are required to list their name on the first page of your assignment as a collaborator.  Full marks will still be awarded to all collaborators.
-	**Midterm and Final Exams**: no collaboration or discussion with classmates is allowed.
-	**AI Policy**: you are welcome to use generative AI assistance when completing the coding exercises to help with syntax.  Otherwise, all use of AI is forbidden: if you cheat and use AI to complete the homework, you will be at a severe disadvantage during the exams, which comprise the bulk of your overall grade.
-	**Code of Academic Integrity**: All students are expected to adhere to the University’s [Code of Academic Integrity](https://catalog.upenn.edu/pennbook/code-of-academic-integrity/). **Violators will be reported to the [The Center for Community Standards and Accountability](https://csa.upenn.edu/)**.
