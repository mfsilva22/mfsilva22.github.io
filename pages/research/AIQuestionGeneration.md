---
permalink: research/ai_question_generation/

header: Developing an AI tool to support the creation of question generators
---

Grant: “SBIR Phase I: An online learning and assessment platform for sophisticated and secure exams”, National Science Foundation, Small Business Innovation Research. Research team: Mariana Silva, Nathan Walters and Matthew West. 2023-2025.

##### *Graduate Student Assigned to This Project: Jacob Levine*

Existing online assessment tools often balance trade-offs between ease of authoring questions and the sophistication of auto-grading. Most commercial platforms simplify the creation of specific question types, such as multiple-choice and fill-in-the-blank, which contributes to their widespread adoption in U.S. universities. However, interviews with instructors from various institutions revealed a strong demand for auto-grading more complex questions, including long-form calculations, mathematical proofs, graphical diagrams, and other advanced formats. Instructors also seek online tools that are user-friendly, enable high-quality assessments, reduce grading effort, and maintain academic integrity.

PrairieLearn addresses these needs by enabling the creation of richer question types with advanced auto-grading algorithms. Its flexibility stems from a core feature where instructors develop "questions as code," or "question generators." However, the lack of a user-friendly interface for content creation and the requirement to write code are significant barriers to PrairieLearn's wider adoption.

This project aims to develop an authoring environment that allows instructors without programming experience to create PrairieLearn question generators using Generative Artificial Intelligence (AI). Our initial prototype translates traditional paper-based question prompts into PrairieLearn questions, consisting of Python and HTML code.

Instructors still need to verify that the generated questions function as intended and refine the prompts if needed. Preliminary user studies with six instructors show that the AI question generator successfully creates working questions over 60% of the time. We are currently refining the implementation to improve accuracy and ease of use. 


<figure class="figure  m-3 rounded mx-auto d-block">
   <img 
      src="{{ site.baseurl }}/pages/images/QGAI-1.pdf" 
      alt="AI question generator interface" 
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
   <figcaption class="figure-caption text-center"> Example prompt on the left and the question generator created by the Gen-AI algorithm on the right. Instructors can refine the question by providing additional prompts or review the source code of the question generator. </figcaption>
</figure>