**Version:** Fall 2026

## Overview

This course introduces students to fundamental concepts, representations, methods, and algorithms used in computational linguistics and natural language processing. The course emphasizes computational approaches to analyzing English language data, with applications to applied linguistics, language learning, assessment, and linguistic research.

This course is fundamentally about **computational representations of language**. Computers do not process human language in the same way that humans do; they require language to be _represented_ in forms that can be stored, manipulated, and analyzed computationally. Designing these representations is not simply a technical task; it involves principled theoretical decisions about what aspects of language to preserve, what to abstract away, and how different linguistic phenomena should be modeled.

Throughout the semester, we will follow a progression of increasingly rich representations of language. We begin by treating language as **strings of characters** and explore ways that we can calculate differences between pairs of strings. We then move to **bags of words**, where we represent language in terms of the words it contains and their frequencies, followed by **sequences of words**, which allow us to model word order. Next, we consider **annotated sequences**, in which linguistic information such as part-of-speech categories is incorporated into the representation as an additional, hidden layer. We then move to **graphs**, which allow us to represent more complex relationships among linguistic units, including syntactic structure and semantic relationships. Finally, we examine **embeddings**, which represent linguistic units as points in a multi-dimensional computational space that captures patterns of similarity and association. At each stage, we will consider not only how language can be represented, but also what kinds of linguistic questions each representation enables us to ask and what information it necessarily leaves out, and what kinds of algorithms can be used to process these types of representations.


## Course Materials

### Required Textbook

Daniel Jurafsky and James H. Martin, *Speech and Language Processing*, Third Edition.

The textbook is freely available from the authors:

[Speech and Language Processing, Third Edition](https://web.stanford.edu/~jurafsky/slp3/ed3book_jan26.pdf)

---

## Learning Outcomes

After completing this course, you will attain the following learning outcomes, which are aligned with the program-level learning outcomes of the Applied Linguistics and Technology program:

* Explain fundamental concepts, methods, and applications of computational analysis of English, including corpus linguistics, natural language processing, and computational approaches to learner language analysis.
* Apply computational tools and techniques to collect, process, and analyze English language data for research, language learning, and assessment purposes.
* Design, implement, and evaluate algorithms for automating linguistic analysis tasks.
* Design and evaluate computationally informed research procedures to investigate applied linguistics questions.
* Communicate computational linguistics findings effectively and demonstrate professional collaboration and independent inquiry in developing and evaluating applications for applied linguistics research and practice.

---

## Course Requirements and Grading

| Component              |   Weight |
| ---------------------- | -------: |
| Module Assessments     |      50% |
| Final Project and Exam |      30% |
| In-class Participation |      20% |
| **Total**              | **100%** |

---

## 1. Class Participation

Class participation is worth 20% of your final grade. Regular attendance, preparation, and active participation in class are expected and strongly encouraged. **Attendance itself is not graded, and there is no limit on the number of classes you may miss.** However, you are responsible for learning all material covered in class, whether or not you attend. If you miss class, you should obtain the relevant materials and prepare independently. The oral exam may include questions on material covered during classes you missed. Demonstrating full proficiency with that material on the oral exam can fully compensate for your absence and earn full participation credit.

---

## 2. Six Module Assessments

At the end of each of the six instructional modules, you will complete an in-class module assessment. Each assessment will evaluate your understanding of the concepts, computational representations, and algorithms introduced in that module.

There will be six module assessments, each worth 10% of the final grade. At the end of the semester, your **lowest-scoring module assessment will be dropped**, and your five highest scores will contribute to the 50% module-assessment portion of your final grade.

Each module assessment will also include an **optional take-home coding component**. This component will provide an opportunity to implement the computational representation, algorithm, or  method covered in the module and apply it to a linguistic dataset or problem. Completion of the coding component is not required and will not negatively affect your grade if you choose not to complete it.

Successful completion of the coding component may earn **bonus points** that can be used to improve your overall course grade. Additional instructions and the number of available bonus points will be provided with each assessment.

---

## 3. Final Project Presentation and Exam

### Final Project

For the final project, you will develop a computational linguistics project that addresses a linguistic or applied linguistics question using **at least one of the six computational modules** covered in the course.

Your project should include:

* A clearly defined linguistic or applied linguistics question
* An appropriate linguistic dataset
* Computational methods drawn from the course
* An analysis of the results
* A discussion of the implications and limitations of the approach

The project is intended to demonstrate your ability to select, implement, apply, and evaluate computational methods for a meaningful linguistic problem.

Projects may be completed individually or in an approved collaborative format. Additional project guidelines and evaluation criteria will be provided during the semester.

### Oral Exam

Toward the end of the semester, each student will participate in an individual oral examination with the instructor. The oral examination will assess your understanding of the computational methods covered in the course and your ability to explain, interpret, and critically evaluate the methods used in your final project.

The oral examination may include questions about:

* Methods for representing language computationally
* Algorithms used in the course
* Your implementation and analysis in the final project
* Methodological decisions
* Interpretation of results
* Limitations of computational approaches

The **Oral Exam will be scheduled individually with the instructor**.

---

## Note on the Use of GenAI

While GenAI can solve many of the programming challenges presented in this course, it is important to use it as a supplementary tool rather than a crutch. Relying solely on AI-generated solutions without understanding the underlying principles will hinder your ability to code independently and to debug AI-generated code effectively.

Remember, the goal of this course is to equip you with the skills necessary to develop, analyze, and troubleshoot linguistic analysis tasks on your own. By practicing coding assignments manually, you will build a strong foundation that will allow you to critically evaluate and refine the output generated by AI tools.

In essence, learning to code by hand is crucial for becoming proficient in programming, and GenAI should be viewed as an enhancer of this learning process, not a replacement for it.

---

## Syllabus Statements

Iowa State University provides required and recommended syllabus statements, which are incorporated into this syllabus by reference as if fully stated here. You can review these statements through the Iowa State University [syllabus statements webpage](https://celt.iastate.edu/prepare-and-teach/design-your-course/syllabus-statements/).

---

## Tentative Schedule

*Schedule is subject to change.*

| Weeks           | Topic                                      | Readings       | 
| --------------- | ------------------------------------------ | -------------- | 
| **Week 1**      | Introduction                               | —              |
| **Weeks 2–3**   | Language as a strings of characters                                    | Section 2.9    |
| **Weeks 4–5**   | Language as a bag of words                               | Section 11.1.1 |
| **Weeks 6–7**   | Language as a sequence of words (n-grams, Markov Models)                  | Section 3.1    |
| **Weeks 8–9**   | Language as an annotated sequence (parts of speech, Hidden Markov Models)        | Section 17.4   |
| **Weeks 10–11** | Language as a graph (syntax and semantics)                         | [universaldependencies.org](https://universaldependencies.org/) [WordNet](https://en-word.net/)|
| **Weeks 12–13** | Language as an embedding | Chapter 5      |
| **Week 14**     | Final Project Presentations                | —              |
| **Week 15**     | Oral Exam (based on final projects)        | —              |


