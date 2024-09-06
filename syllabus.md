# Programming Language Structures

## Course Information

Lewis & Clark College, Fall 2024  
CS 373, Section 01  
Monday/Wednesday/Friday 9:10-10:10 AM  
Olin 305

**Google Classroom:**  I will use Google Classroom throughout the semester to
share assignment due dates and details about exams, and track your grade.

**GitHub:**  I will use GitHub to share reading material, assignments, and the
toolset used to complete the latter.

**Gitpod:**  We will use Gitpod to edit code and to run the toolset (see the
[cheat sheet](cheatsheet.md)).

## Teacher Information

Professor: Alain Kägi  
Email: alaink@lclark.edu  
Office hours:
* In person, Tuesdays 11:00 AM - 1 PM, Olin 305
* Zoom, Thursdays 11-noon, meeting id 615 861 9716

## Course Description

In this course, you will learn fundamental concepts related to the design and
implementation of programming languages.  We will dive into lexical, syntactic,
and semantic analysis.  We will study different programming paradigms, including
functional, procedural, and object-oriented.  We will pay special attention
various call semantics, the difference between dynamic vs static scoping; and
type systems.

## Course Goals

My primary goal is to help you master some important concepts of programming
languages such as syntax analysis, scoping rules, function call semantics, and
type systems.

Through the assignments, you will also gain some experience reading and
extending object-oriented programs, learn how to use a cloud-based integrated
development environment, and use a distributed version control system.

Programming assignments will be done in Java.  Do not be alarmed if you have no
experience with this language.  First, Java is similar to Python.  Then, we will
first spend time reading existing Java programs before you will be asked to
extend them.  And, remember, it is good practice to be able to program in a
less-familiar language.  Success in your first job may hinge on developing that
skill.

## Learning Outcomes

The learning objectives for this class include:

1. Formal methods to describe lexical tokens and program syntax
2. Syntax and semantic analysis
3. Consequences and implementation of scoping rules
4. Key differences between functional and object-oriented programming languages
5. Type systems

## Office Hours

I hope you will visit me throughout the term, so I can learn more about your
interests and answer your questions.  No appointment is necessary to see me
during office hours; simply stop by Olin 305 for in-person office hours
(Tuesdays 11:00 AM - 1 PM) or enter my Zoom waiting room (Thursdays 11-noon,
meeting id 615 861 9716) and I will let you in as soon as I'm available.  If you
would like to make an appointment outside of my office hours, please email me at
alaink@lclark.edu.

## Requirements

All assignments will be posted on GitHub and will be submitted through Google
Classroom.  They are designed to help you master and apply what we are learning
in class.  **Assignments are due on Friday at 11:59 PM of the week they are
due.**  Points will be taken off if submitted late; in some cases late
assignments will not receive any credit.

## Grade Scale

I will use the following scale to compute your final grade:

Grade            | Point Range
-|-
**A− or A**      | 90-100
**B−, B, or B+** | 80-89
**C or C+**      | 72-79
**C−**           | 70-71
**D+**           | 68-69
**D**            | 62-67
**F**            |  0-61

Note that I may adjust your final grade in the class up or down in light of your
participation, attendance, and overall commitment to the class.  The grade of
“B”  reflects work that is normally done thoughtfully and thoroughly by
students.  The grade of “A” is earned by students who consistently do
outstanding work and who show an unusually strong commitment to being active
participants in the learning experience.

## Grading

* Assignments: 30%
* Midterms: 30%
* Final exam: 40%

## Helpful Tips

**Attend all class meetings.**  The classroom is a place to learn new concepts,
to work through activities to reinforce learning, and to engage in discussions
with your professors and your peers.  If you have to miss class for illness or
an emergency, please let me know and try to ask a peer to take notes for you.
Being on time for class is also important.

**Collaborate with your peers.**  Form a study group and get together to talk
about the class.  The sooner you get together with your peers to talk about the
class, the better.  That way you can look over your notes right away, when they
are still fresh.  You are likely to learn a lot from one another and find
places where you need clarification from me before exam-time.  You may
collaborate on assignments, but you need to develop your own answers.

**Divide and conquer — split up some of the exam review.**  When it comes time
to review and to prepare for exams, you will have another great opportunity for
collaboration.  Split up readings and lectures among a group of people and have
each person prepare parts of the study guides and potential answers to exam
questions.  Then trade study guides and get together for your own review
sessions.

**Get to know your professor.**  Please feel free to stop by my office hours
early in the semester, and stop by often.  I am here not only to answer
questions about the lectures and the assignments, but also to engage in
conversation about computer science (and life!) as a whole.  I love hearing from
students because you are the keepers of many interesting ideas and perspectives.

## High-level Schedule

* W1-2: Language Construction
  * Tokens, Scanner, Regex, Parser, BNF, AST, PLCC toolset
  * **Variable binding and lookup** (essence of semantics)
* W3-7: Functional Paradigm
  * Static vs dynamic scoping
  * `let`, `proc`, `+`, `-`, `*`, `add1`, `sub1`, `zero?`, `if`
* W8-10: Call Semantics
  * Side-effects
  * Pass-by-value, pass-by-reference, pass-by-name, pass-by-need,
    pass-by-copy-in-copy-out
* W10-11: Static Type System
* W12-16: Object-oriented Paradigm
  * Classes, objects, static fields, static methods, fields, methods,
    instantiation, object construction, inheritance, shadowing

## Detailed Schedule

**W** | **Monday**         | **Wednesday** | **Friday**        | **Due**
-|-|-|-|-
 1    | *No Class*         | Syllabus      | Lexical Analysis  |
 2    | Syntactic Analysis | *No Class*    | Semantic Analysis |
 3    | Semantic Analysis  | Environments  | Lab               |
 4    | V0                 | V1            | Lab               | **A1**
 5    | V2                 | V3            | Lab               |
 6    | V4                 | Lab           | *No Class*        | **A2**
 7    | V5                 | V6            | Lab               |
 8    | Exam 1 Review      | **Exam 1**    | SET               |
 9    | REF                | NAME          | Lab               | **A3**
10    | NEED               | TYPE0         | Lab               |
11    | TYPE1              | TYPE1         | Lab               |
12    | OBJ                | Lab           | Exam 2 Review     | **A4**
13    | **Exam 2**         | OBJ           | Lab               |
14    | Lab                | Lab           | *No Class*        |
15    | OBJ                | OBJ           | Lab               | **A5**
16    | Final Exam Review  | Inference     | *No Class*        |

## Course Policies

**Attendance.**  Attendance is key to master the topics covered in this course.
Participation in discussion and activities will help gain that proficiency.
If you must miss a class for any reason, please obtain information about the
the missed class from your classmates.  Missing the midterm or final exam
disadvantages not only you, but also your classmates and me.  Therefore, make-up
exams will only be given for very serious circumstances.

**Accommodations.**  Please see me if there are accommodations that could help
you learn more effectively in this class or if you are experiencing barriers to
accessibility in our class.  Some kinds of accommodations may require
documentation through the
[Office of Student Accessibility](https://www.lclark.edu/offices/student-accessibility/).
If you plan to take exams in the Office of Student Accessibility, please
schedule with them and let me know well in advance of the exam.

**Course Withdrawals.**  You may drop this course on WebAdvisor by Friday of the
second week of class and no W grade will appear on your transcript.  After the
second week and before 4 PM on Friday of the 10th week, you can withdraw from
the course by submitting a Course Withdrawal form to the Registrar’s Office.  In
this case, a W grade will appear on your transcript.  **The last day to withdraw
from this class is Friday, November 8th.**  It is not possible for me to
authorize your withdrawal from the course after that date.  At that point, you
will need to complete the course and take whatever grade you have earned.  If
you have questions or concerns about your performance in the course, please talk
with me before **November 8th**.

**Academic Integrity.**  Academic integrity is an essential part of learning.
Plagiarism, cheating, or the deliberate misrepresentation of information will
result in failure of this course.  Please avoid any behavior that may be
reasonably viewed as suspicious.  Remember that helping a classmate to cheat
counts as cheating.  If you have any questions about the use of generative AI
technology (e.g., ChatGPT) or plagiarism boundaries or about what type of
material you can access while working on an assignment, please see me before you
turn in your work.  If you have any questions or concerns about academic
honesty, please come see me or refer to Lewis & Clark’s
[Academic Integrity Policy](https://docs.lclark.edu/undergraduate/policiesprocedures/academicintegrity/).

**Other.**  All college policies govern this course.  Please see the
[Undergraduate Catalog](https://college.lclark.edu/catalog/) for any issues not
covered in this syllabus.
