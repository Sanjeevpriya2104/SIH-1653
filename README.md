# Smart India Hackathon Workshop
# Date:10.04.2025
## Register Number:212224040289
## Name: k.sanjeevpriya
## Problem Title
SIH 1653: Web based Selector-Applicant Simulation Software
## Problem Description
Background: Recruitment and Assessment Centre (RAC) under DRDO, Ministry of Defence carries out interviews for applications received against advertised vacancies and for promotion to next higher grade for scientific manpower inducted within DRDO. Description: The process of interviewing is a challenging task. An unbiased objective interviewing process helps identify the right talent. The basic process of an interview involves posing a set of questions by an interviewer and thereafter evaluating responses from candidates. Thus, the questions asked should be relevant and match the area/ expertise of the applicant and the responses should also be of relevance w.r.t. the question asked. Expected Solution: The proposed solution should provide experts as well as candidates a real life Board Room experience, starting with initial ice-breaking questions leading to in-depth techno-managerial (depending on the level of candidate) questions. It shall also be able to provide a quantifiable score for experts as well as the candidate for the relevancy of questions w.r.t. the area/ expertise of the applicant. Similarly, candidate responses should also be graded for relevancy w.r.t. the question asked, finally assisting in arriving at an overall score for the subject knowledge of the candidate and thus his/ her suitability against the advertised post.

## Problem Creater's Organization
Ministry of Defence

## Idea
Most Recent Data Collection: October 2023 – Smart Interviewing Simulation Interface

This simulates a board room environment (either video/avatar-based or hybrid).

Starts with ice-breaking questions to ease the candidate.

Centralization around issue- and techno-managerial questions, customized based on level/post applied.

FAQ-Gen: Domain-Aware Dynamic Question Generator

L1 uses NLP and machine learning to analyze CV, area of expertise, and advertised job description.

Backed up by a ranking of questions by relevance and difficulty, auto-generates.

Supports a variety of scientific fields (aerospace, AI, cyber, propulsion, electronics, etc.).
Real-Time 

## Proposed Solution / Architecture Diagram


![Screenshot 2025-04-10 201055](https://github.com/user-attachments/assets/3f399660-debe-490c-bf5e-6ec9b9443e5d)




## Use Cases

![Screenshot 2025-04-10 201307](https://github.com/user-attachments/assets/1b077994-a692-4302-a784-db423181ba79)



## Technology Stack
1.Frontend – React.js/Angular for UI, WebRTC for video conferencing.

2.Backend – Node.js/Django for APIs, WebSockets for real-time communication.

3'Database – PostgreSQL for structured data, MongoDB for unstructured data.

4.AI & NLP – GPT/BERT for question analysis, Google Speech-to-Text for voice processing.


## De1.Cloud & Hosting – AWS/Google Cloud for scalable deployment.
1.Cloud & Hosting – AWS/Google Cloud for scalable deployment.

2.Security – OAuth 2.0, JWT for authentication, AES-256 for encryption.

3.Analytics – ELK Stack/Grafana for system monitoring.

4.Integration – Zoom SDK/Jitsi for video calls, Firebase for notifications.


