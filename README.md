# Smart India Hackathon Workshop
# Date:
## Register Number:24900595
## Name:Jeevan Vishal GD
## Problem Title
SIH 1653: Web based Selector-Applicant Simulation Software
## Problem Description
Background: Recruitment and Assessment Centre (RAC) under DRDO, Ministry of Defence carries out interviews for applications received against advertised vacancies and for promotion to next higher grade for scientific manpower inducted within DRDO. Description: The process of interviewing is a challenging task. An unbiased objective interviewing process helps identify the right talent. The basic process of an interview involves posing a set of questions by an interviewer and thereafter evaluating responses from candidates. Thus, the questions asked should be relevant and match the area/ expertise of the applicant and the responses should also be of relevance w.r.t. the question asked. Expected Solution: The proposed solution should provide experts as well as candidates a real life Board Room experience, starting with initial ice-breaking questions leading to in-depth techno-managerial (depending on the level of candidate) questions. It shall also be able to provide a quantifiable score for experts as well as the candidate for the relevancy of questions w.r.t. the area/ expertise of the applicant. Similarly, candidate responses should also be graded for relevancy w.r.t. the question asked, finally assisting in arriving at an overall score for the subject knowledge of the candidate and thus his/ her suitability against the advertised post.

## Problem Creater's Organization
Ministry of Defence

## Idea

AI-Driven Evaluation System: Develop an AI-based platform that integrates:

Customized Question Bank: Dynamically generate and customize interview questions tailored to the candidate's expertise and job role.

Response Analysis: Use Natural Language Processing (NLP) to analyze candidate responses in real-time for relevance, technical accuracy, and communication skills.

Expert Score Accountability: Grade experts' questions for relevance to ensure unbiased evaluation.

Boardroom Simulation: Create an interactive virtual interview environment, simulating a real-life boardroom scenario to give candidates and experts an authentic experience.

Integrated Scoring Metrics: Use machine learning to provide quantifiable scores for:

Relevance of questions asked by the interviewers.

Candidate responses in relation to the questions.

Overall subject knowledge and suitability for the role.

Final Output: Generate a comprehensive report that gives a cumulative score for the candidate, assists in objective decision-making, and ensures transparency.


## Proposed Solution / Architecture Diagram

User Interface (UI):

A web-based or desktop application providing:

A boardroom simulation with interactive visuals.

Dashboards for candidates and experts to access the interview process.

AI-Powered Components:

Question Generator:

Uses Natural Language Processing (NLP) to generate relevant ice-breaking and technical questions.

Ensures the questions align with the candidate's profile and expertise.

Response Evaluator:

Grades responses in real-time for relevance, depth, and communication clarity.

Evaluates the subject matter using a predefined scoring rubric.

Scoring Engine:

Consolidates scores for:

Expert questions (evaluates relevance and professionalism).

Candidate responses (analyzes technical accuracy and depth).

Data Management:

Stores and retrieves candidate profiles, resumes, and interview records.

Dynamically matches candidates with job-specific question banks.

Back-End Processes:

Machine Learning Algorithms:

Optimizes evaluation criteria by learning from past interview data.

Database Management:

Securely stores candidates' input, grading history, and system-generated reports.


![Screenshot 2025-03-09 200122](https://github.com/user-attachments/assets/c3086b4e-9e6b-4221-858e-a3cf491b2ac1)



## Use Cases

1. Recruitment Process
Scenario: Shortlisting candidates for advertised positions in DRDO.

Use Case:

Experts use the platform to simulate real-life boardroom interviews for candidates.

The system evaluates candidates' subject expertise and communication skills, generating quantifiable scores.

The final scores assist in selecting the most suitable candidates.

2. Internal Promotions
Scenario: Assessing scientific manpower within DRDO for promotion to higher grades.

Use Case:

Tailored interview questions are generated based on the candidates' current roles and expertise.

The system evaluates both technical knowledge and managerial skills for higher-grade positions.

Recommendations are provided to the decision-making panel for unbiased promotion assessments.

3. Expert Training and Evaluation
Scenario: Enhancing the interviewing skills of experts.

Use Case:

The system evaluates the relevance of questions posed by experts.

Offers feedback to improve questioning techniques, ensuring alignment with candidate profiles.

Scores help gauge and improve interviewer performance over time.

4. Bias-Free Evaluation
Scenario: Minimizing unconscious bias during interviews.

Use Case:

The system provides impartial feedback on both questions and responses, ensuring consistency in evaluations.

Reduces variability in scoring caused by individual biases among interviewers.

5. Continuous Improvement
Scenario: Optimizing the interview process based on historical data.

Use Case:

Machine learning models analyze past interviews to refine scoring metrics.

Dynamic updates to the question bank based on trends in successful candidate profiles.


## Technology Stack

Front-End (User Interface):
Frameworks/Technologies:

React.js or Angular for a responsive, interactive interface.

WebRTC for real-time video and audio to create a virtual boardroom simulation.

Bootstrap or Tailwind CSS for styling and ensuring a professional look.

Purpose:

Provides an intuitive and engaging experience for experts and candidates.

Simulates a boardroom environment with realistic visuals.

2. Back-End (Server and API):
Frameworks/Technologies:

Node.js (with Express.js) or Django (Python) for building the back-end server.

Flask (Python) for lightweight API management.

Purpose:

Processes requests from the front end.

Manages communication between the user interface and the AI models or database.

3. Natural Language Processing (NLP):
Libraries/Models:

Hugging Face Transformers for question generation and response analysis.

spaCy or NLTK for text preprocessing and linguistic analysis.

Pre-trained models like OpenAI GPT series or T5 for advanced question generation and response evaluation.

Purpose:

Dynamically generates questions based on candidate profiles.

Grades and evaluates responses for relevance, technical depth, and clarity.

4. Machine Learning (Scoring Engine):
Frameworks/Technologies:

TensorFlow or PyTorch for training custom ML models.

Scikit-learn for implementing simpler classification or scoring algorithms.

Purpose:

Provides quantifiable scoring for candidates and experts.

Learns from historical data to refine the evaluation process.

5. Database Management:
Databases:

PostgreSQL or MySQL for structured data like candidate profiles and scores.

MongoDB for handling semi-structured data such as interview transcripts.

Purpose:

Securely stores user data, questions, and interview records.

Supports efficient querying for candidate-specific questions or evaluation history.



## Dependencies

Front-End Dependencies
React.js/Angular (or other frameworks): For building the user interface.

WebRTC: To enable real-time video and audio streaming.

Bootstrap/Tailwind CSS: For styling and ensuring responsive design.

2. Back-End Dependencies
Node.js/Django:

Required back-end framework and runtime environment.

Includes libraries like express (for Node.js) or Django middleware.

RESTful APIs:

Dependency on frameworks/libraries for building APIs to connect the front-end to the AI models and database.

3. Natural Language Processing (NLP) Libraries
Hugging Face Transformers:

Pre-trained language models like GPT, T5, or BERT for generating and evaluating text.

spaCy/ NLTK:

For text processing tasks like tokenization, part-of-speech tagging, and dependency parsing.

OpenAI API:

For leveraging advanced large language models (if needed as an external service).


