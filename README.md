# Internship Allocator
AI based internship recommendation engine 
Prototype Link - [Internship Allocator](https://www.figma.com/proto/FjyMgtf56ahrk7SgzcWuD3/AlgoNaut?node-id=4-13&p=f&t=WCmqsW9nqy5jbeee-1&scaling=contain&content-scaling=fixed&page-id=0%3A1)

## Problem Statement
Candidates struggle to identify suitable interships due to limited digital exposure. Hundreds of listings overwhelm applicants with no prior experience

## Solution
AI based recommendation enginge to suggest top 3-5 interhips to the candidates based on their details (Education, skills, interests, etc.). UI - Guided input collection via step-by-step Q&A.

## Tech Stack 
- Python
- FastAPI
- React + TailwindCSS 
- TensorFlow + scikit-learn
- JWT with 2FA
- Email, WhatsApp/SMS notifications
- MySQL
- WebSockets for real time updates
- Docker

## Workflow
Candidate -> Login -> Fill Profile (upload Resume) -> Request Recommendations -> Backend fetches internships -> Compute Match Score -> Return top 3-5 interships -> Candidate can apply

Background Services -> Fetch interships (API/scraper) -> Update DB -> Trigger re-recommendations -> Notify students

## Outcomes 
- Personalized internship recommendations instead of scrolling endlesslly
- Increased chances of applying to relevant opportunities
- Real-time alerts when new interships matching their profile appears
