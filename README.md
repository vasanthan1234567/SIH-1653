# Smart India Hackathon Workshop
# Date:
## Register Number:
## Name:
## Problem Title
SIH 1653: Web based Selector-Applicant Simulation Software
## Problem Description
Background: Recruitment and Assessment Centre (RAC) under DRDO, Ministry of Defence carries out interviews for applications received against advertised vacancies and for promotion to next higher grade for scientific manpower inducted within DRDO. Description: The process of interviewing is a challenging task. An unbiased objective interviewing process helps identify the right talent. The basic process of an interview involves posing a set of questions by an interviewer and thereafter evaluating responses from candidates. Thus, the questions asked should be relevant and match the area/ expertise of the applicant and the responses should also be of relevance w.r.t. the question asked. Expected Solution: The proposed solution should provide experts as well as candidates a real life Board Room experience, starting with initial ice-breaking questions leading to in-depth techno-managerial (depending on the level of candidate) questions. It shall also be able to provide a quantifiable score for experts as well as the candidate for the relevancy of questions w.r.t. the area/ expertise of the applicant. Similarly, candidate responses should also be graded for relevancy w.r.t. the question asked, finally assisting in arriving at an overall score for the subject knowledge of the candidate and thus his/ her suitability against the advertised post.

## Problem Creater's Organization
Ministry of Defence

## Idea
Simulated Interview Environment:

The platform will simulate a real-life interview experience where interviewers can ask customized questions based on the candidate’s profile (education, skills, previous roles).

The candidate will respond to these questions in a structured format that mirrors real-life conditions, either through text, video, or audio.

![WhatsApp Image 2025-04-19 at 14 39 28_2b5de707](https://github.com/user-attachments/assets/c505398b-b1a8-471b-ab80-fb2adb588c09)

## Proposed Solution / Architecture Diagram
Architecture Overview:
Frontend (Web Interface):

Interview Dashboard: Provides interviewers and candidates with a platform to conduct and take the interview.

Real-time Question and Answering Interface: The interviewers can pose questions, and candidates can respond in real time.

Scoring System: Interviewers can score responses, and the system will calculate an overall score for the candidate.

## Use Cases
nterview Setup: Create a new interview session, select candidate profiles, and initiate a list of relevant questions.

Pose Questions: Ask questions from the system or manually input custom questions.

Score Responses: Score the candidate’s answers based on relevance and quality using a rating scale or automatic system.

Provide Feedback: Leave qualitative feedback for ca

## Technology Stack
eactJS / Vue.js: For building an interactive, responsive UI.

HTML5 / CSS3: For designing the interface.

WebRTC or WebSockets: For real-time audio/video communication between interviewers and candidates.

JavaScript: For interactive elements on the page.

Backend:

Node.js / Django: For creating the server-side logic, APIs, and managing user requests.

ExpressJS (if using Node.js): For managing API routes and server-side routing.


## Dependencies
Natural Language Processing (NLP) Libraries:

spaCy (for text analysis)

NLTK (for traditional NLP tasks)

transformers (for state-of-the-art language models)

Machine Learning Frameworks:

TensorFlow / PyTorch (for developing and deploying ML models)

Scikit-learn (for simpler ML models or feature extraction)
