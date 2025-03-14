# Smart India Hackathon Workshop
# Date: 14.03.2025
## Register Number: 212224040220
## Name: Nikshitha S
## Problem Title
SIH 1653: Web based Selector-Applicant Simulation Software
## Problem Description
Background: Recruitment and Assessment Centre (RAC) under DRDO, Ministry of Defence carries out interviews for applications received against advertised vacancies and for promotion to next higher grade for scientific manpower inducted within DRDO. Description: The process of interviewing is a challenging task. An unbiased objective interviewing process helps identify the right talent. The basic process of an interview involves posing a set of questions by an interviewer and thereafter evaluating responses from candidates. Thus, the questions asked should be relevant and match the area/ expertise of the applicant and the responses should also be of relevance w.r.t. the question asked. Expected Solution: The proposed solution should provide experts as well as candidates a real life Board Room experience, starting with initial ice-breaking questions leading to in-depth techno-managerial (depending on the level of candidate) questions. It shall also be able to provide a quantifiable score for experts as well as the candidate for the relevancy of questions w.r.t. the area/ expertise of the applicant. Similarly, candidate responses should also be graded for relevancy w.r.t. the question asked, finally assisting in arriving at an overall score for the subject knowledge of the candidate and thus his/ her suitability against the advertised post.

## Problem Creater's Organization
Ministry of Defence

## Idea

1. **Challenge of Objective Evaluation** – Ensuring an unbiased and standardized interview process to fairly assess candidates' suitability for scientific roles in DRDO.  

2. **Relevance of Questions** – Questions should align with the candidate's expertise and job requirements, avoiding irrelevant or generic queries.  

3. **Assessment of Responses** – Candidate responses must be evaluated based on accuracy, depth, and relevance to the question asked.  

4. **Board Room Simulation** – The interview process should replicate a real-life boardroom experience, progressing from general to in-depth technical and managerial questions.  

5. **Quantifiable Scoring System** – A structured mechanism is required to assign scores to both interviewers (for question relevance) and candidates (for response quality).  

6. **Overall Suitability Analysis** – The final system should provide an overall assessment of the candidate’s subject knowledge and suitability for the advertised position.


## Proposed Solution / Architecture Diagram

![sih](https://github.com/user-attachments/assets/01e56152-d242-4666-a19f-1fcdb42e7af7)



## Use Cases

![Screenshot 2025-03-14 082959](https://github.com/user-attachments/assets/de5d900c-8dc5-4ea9-855c-5dade3838bea)



## Technology Stack

#### Frontend (Web Application):

React.js / Vue.js (UI)

WebRTC (for live video interviews)

#### Backend (AI & Processing):

Python (Django/FastAPI) or Node.js (Express.js)

PostgreSQL / MongoDB (for candidate profiles & scores)

#### AI & NLP Modules:

GPT-4 / BERT (for AI-driven questioning & scoring)

Speech-to-Text APIs (Google Speech API, Whisper)

Sentiment Analysis (TensorFlow/NLP models)

#### Deployment:

AWS / Azure / GCP (Cloud hosting)

Docker & Kubernetes (Scalability)

## Dependencies

AI Model Training & Optimization

Continuous improvement required for accuracy.
Fine-tuning models (GPT-4/BERT) with domain-specific datasets.
Ongoing monitoring and bias reduction in AI-driven questioning.
Data Mapping & Collection

Estimated Time: 20-25 days.
Collecting real interview data, historical hiring success metrics, and job-role-specific competency frameworks.
Preprocessing and structuring data for AI-based question generation & evaluation.
Speech & Sentiment Analysis Integration

Estimated Time: 15-20 days.
Integrating and fine-tuning Speech-to-Text APIs (Google Speech API, Whisper).
Developing NLP-based sentiment & confidence analysis models.
Video & Communication Module Development

Estimated Time: 30 days.
Implementing WebRTC/Twilio for real-time video interviews.
Ensuring smooth recording, playback, and assessment of interview sessions.
Frontend & Backend Development

Estimated Time: 40-45 days.
Frontend: UI/UX development using React.js/Vue.js with interactive dashboards.
Backend: Setting up APIs, database structures, and AI integration.
Cloud Deployment & Scalability Planning

Estimated Time: 15-20 days.
Deploying on AWS/Azure/GCP with Docker & Kubernetes for scalability.
Load balancing & security configuration.
Budget Allocation

Revised Budget: INR 15-20 Lakhs.
Major Costs:
Advanced AI model training & fine-tuning.
Speech & sentiment analysis tools.
Cloud storage & processing costs.
Security & compliance measures.
