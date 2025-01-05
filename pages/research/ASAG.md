---
permalink: research/asag/

header: Developing AI tools for Automatic Grading of Short Answers
---

Grant: "Automatic Short Answer Grading at scale using Large Language Models", *Strategic Instructional Innovations Program (SIIP) at UIUC*. Research team: Mariana Silva, Matthew West, Jeff Erickson, Yael Gertner, Firas Moosvi, Seth Poulsen, 2024-2025.

##### *Graduate Student Assigned to This Project: Victor Zhao*

The rapid growth of online education has significantly increased the volume of student assignments, creating a pressing need for efficient grading systems. This project aims to integrate an Automatic Short Answer Grading (ASAG) system into PrairieLearn, utilizing Large Language Models (LLMs) such as OpenAI's GPT and specialized local models. Our primary goal is to develop an ASAG system that enables instructors to grade free-form textual answers accurately and efficiently, regardless of their familiarity with LLMs. By reducing the grading burden on educators and delivering immediate, constructive feedback to students, this approach enhances both learning outcomes and engagement.

### An ASAG system to grade mathematical proofs

In our initial study, we explored various training methods and models to autograde free-form mathematical proofs by leveraging existing LLMs and other machine learning techniques. The models were trained using data from four different proof-by-induction problems. We evaluated the performance of MathBERT, Llemma7b, Llemma34b, and GPT-3, all of which demonstrated satisfactory results to varying degrees.

To benchmark the models, we also recruited human graders to assess the same proofs used in the training data. The best-performing grading models (Llemma7b and Llemma 34b) proved to be more accurate than most human graders, highlighting the potential of ASAG systems to surpass human capabilities in grading consistency and precision.

<figure class="figure border m-3 rounded mx-auto d-block">
   <img 
      src="{{ site.baseurl }}/pages/images/per_grader.pdf" 
      alt="" 
      style="
         display: block; 
         margin-left: auto; 
         margin-right: auto; 
         margin-top: 10px; 
         margin-bottom: 10px; 
         width: 90%; 
         max-width: 1200px; 
         height: auto; 
         clear: both;">
   <figcaption class="figure-caption text-center"> Average accuracy for each grading model and human grader. Human graders familiar with the grading rubrics are indicated by the letter A, and the ones with less experience are indicated by the letter B. Graders with more experience with the grading rubrics achieve higher accuracy than unexperienced graders and all grading models. </figcaption>
 </figure>

In Spring 2024, we conducted a user study in a Discrete Math class, utilizing the trained GPT-3 grader integrated into PrairieLearn to autograde three proof-by-induction problems. The study found that students who could use the autograder to revise their submissions scored on average 10% higher on the proof problems compared to those who did not have access to the autograder.  Despite these improvements, students reported trusting human graders more than AI-based autograders.

Zhao C., Silva M., Poulsen S., ["Autograding mathematical induction proofs with Natural Language Processing"](https://arxiv.org/abs/2406.10268), arXiv 2024.
