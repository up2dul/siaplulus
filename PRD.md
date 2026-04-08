# Product Requirements Document (PRD)

# Siaplulus

Version: 1.0  
Product Type: AI-powered Career Assistant SaaS  
Platform: Web-based SaaS (Mobile Responsive)  
Target Timeline: MVP in 1–2 Months

---

# 1. Product Vision

Siaplulus aims to become a **personal AI career assistant** that helps job seekers understand their competitiveness in the job market and prepare effectively for job applications.

The platform reduces uncertainty in the job search process by providing **data-driven career insights, CV feedback, and interview preparation tools** powered by artificial intelligence.

Long-term vision:

> Enable every job seeker to make informed career decisions using AI-powered insights.

Siaplulus will eventually evolve into a **full career intelligence platform**, helping users navigate:

- Career planning
- Skill gap identification
- Salary negotiation
- Interview preparation
- Career growth strategies

---

# 2. Problem Statement

Job seekers often face several uncertainties during the job application process:

### 1. Lack of CV Feedback

Many candidates do not know:

- Whether their CV is strong enough
- If their CV structure is ATS-friendly
- Which skills they are missing

Most applicants submit resumes **without objective feedback**.

### 2. Unclear Market Value

Job seekers frequently do not know:

- What salary they should expect
- How competitive their profile is
- What skills increase their value

This leads to **underpricing or unrealistic salary expectations**.

### 3. Poor Interview Preparation

Candidates often prepare interviews inefficiently because they:

- Do not know what questions will be asked
- Lack practice with role-specific questions
- Do not tailor preparation to their own CV

### 4. Fragmented Career Tools

Currently users rely on multiple tools:

- Resume review tools
- Salary websites
- Interview prep content

There is **no single platform providing personalized career intelligence**.

---

# 3. Goals and Success Metrics

## Primary Goal

Help job seekers **improve their chances of getting hired** by providing actionable insights based on their CV.

## Secondary Goals

- Increase user confidence in job applications
- Improve interview preparation quality
- Provide transparent salary insights

---

## Success Metrics

### Product Metrics

| Metric                         | Target                             |
| ------------------------------ | ---------------------------------- |
| CV uploads                     | 1,000+ in first 3 months           |
| Feature usage rate             | >60% users use at least 2 features |
| Conversion to paid credits     | >5%                                |
| Average credits spent per user | >20 credits                        |

### Engagement Metrics

| Metric                  | Target     |
| ----------------------- | ---------- |
| Return rate             | 25%+       |
| Session duration        | 5+ minutes |
| Feature completion rate | 70%+       |

---

# 4. Target Users and Personas

## Primary Users

### 1. Final-Year University Students

Characteristics:

- Preparing first CV
- Limited work experience
- Seeking internships or entry-level roles

Needs:

- CV feedback
- Skill improvement guidance
- Interview practice

---

### 2. Fresh Graduates

Characteristics:

- 0–2 years experience
- Actively applying to jobs
- Often unsure about competitiveness

Needs:

- CV optimization
- Salary expectations
- Interview preparation

---

### 3. Early-Career Professionals

Characteristics:

- 1–5 years experience
- Considering job switch
- Curious about market value

Needs:

- Salary benchmarking
- Skill gap analysis
- Interview preparation

---

## Example Persona

### Persona: Ardi – Fresh Graduate Developer

Age: 23  
Background: Computer Science Graduate  
Goal: Land first frontend developer job

Pain Points:

- Unsure if CV is strong
- Doesn't know expected salary
- Nervous about interviews

How Siaplulus helps:

- AI CV feedback
- Salary estimation for frontend roles
- Tailored interview questions

---

# 5. Key Features

## 5.1 AI CV Analysis

### Overview

Users upload their CV and receive automated AI analysis.

### Inputs

- PDF / DOCX CV
- Optional: target role

### AI Analysis Areas

1. CV Structure
2. Skills identification
3. Experience relevance
4. Keyword analysis
5. Overall quality

### Outputs

Users receive:

#### CV Score (0–100)

Evaluation based on:

- Clarity
- Skills relevance
- Experience
- formatting
- keyword match

#### Strengths

Example:

- Strong technical skills
- Good project experience
- Clear education background

#### Improvement Suggestions

Example:

- Add quantifiable achievements
- Improve bullet point clarity
- Include more role-specific keywords

#### Skill Gap Detection

Example:

Target Role: Frontend Developer

Missing Skills:

- TypeScript
- Testing frameworks
- CI/CD exposure

---

## 5.2 Market Salary Insight

### Overview

Provides estimated salary ranges based on profile.

### Inputs

- Extracted CV data
- Experience level
- Job role
- Skills

### Output

Users see:

Estimated Salary Range:

Example:

Frontend Developer (Indonesia)

- Low: IDR 7,000,000
- Median: IDR 10,500,000
- High: IDR 15,000,000

Additional Insights:

- Skills increasing salary
- Experience impact
- Market demand

---

## 5.3 AI Interview Question Generator

### Overview

Generates interview questions tailored to user's CV.

### Question Categories

1. Behavioral Questions
2. Technical Questions
3. Situational Questions
4. Resume-specific Questions

Example:

Behavioral:

> Tell me about a challenging project listed in your CV.

Technical:

> How would you optimize React rendering performance?

Situational:

> How would you handle a tight deadline with changing requirements?

---

# 6. User Journey / User Flow

## First-Time User Flow

1. User lands on homepage
2. User signs up
3. User purchases credits (optional early step)
4. User uploads CV
5. System processes CV
6. User receives analysis results
7. User spends credits to unlock features

---

## Core Flow

User → Upload CV  
→ CV parsed  
→ Credits deducted  
→ AI analysis performed  
→ Results dashboard displayed

---

## Feature Access Flow

Example:

User clicks "Generate Interview Questions"

System checks:

- Does user have enough credits?

If yes:

- Deduct credits
- Generate results

If no:

- Redirect to credit purchase page

---

# 7. Functional Requirements

## Authentication

Users must be able to:

- Sign up
- Log in
- Log out
- Reset password

---

## CV Upload

System must support:

- PDF upload
- DOCX upload
- File size limit (e.g. 5MB)

---

## CV Parsing

System extracts:

- Name
- Skills
- Work experience
- Education
- Projects

---

## AI Analysis

System must:

- Analyze CV content
- Generate score
- Produce feedback

---

## Credit System

Users must be able to:

- Purchase credits
- View remaining credits
- Spend credits per feature

---

## Feature Access Control

System must restrict access if credits insufficient.

---

# 8. Non-Functional Requirements

## Performance

CV analysis response time:

Target: **<15 seconds**

---

## Scalability

System should support:

- 1,000+ concurrent users

---

## Security

- Secure file storage
- Encrypted user data
- Secure authentication

---

## Availability

Target uptime:

99%

---

## Privacy

User CV data must:

- Not be publicly accessible
- Only used for analysis

---

# 9. Pricing and Monetization Model

## Credit-Based System

Users purchase credits.

Credits are spent per feature usage.

---

## Example Pricing

| Credits     | Price |
| ----------- | ----- |
| 20 credits  | IDR 36,000    |
| 50 credits  | IDR 72,000    |
| 120 credits | IDR 150,000   |

---

## Feature Cost

| Feature             | Credit Cost |
| ------------------- | ----------- |
| CV Analysis         | 10          |
| Salary Insight      | 6           |
| Interview Questions | 8           |

---

## Monetization Strategy

Primary:

- Credit purchases

Future:

- Subscription plans
- Career coaching services
- Premium analytics

---

# 10. MVP Scope

Given 1–2 month development timeline.

Focus only on **core value features**.

### Included in MVP

- User authentication
- CV upload
- CV parsing
- AI CV analysis
- Interview question generator
- Credit system
- Basic dashboard

---

### Excluded from MVP

- Advanced analytics
- Skill learning recommendations
- Resume builder
- LinkedIn integration
- AI mock interview

---

# 11. Risks and Challenges

## 1. AI Accuracy Risk

AI insights may sometimes be generic.

Mitigation:

- Improve prompts
- Add structured scoring rules

---

## 2. Data Quality

Salary insights depend on reliable market data.

Mitigation:

- Use aggregated salary datasets
- Partner with job platforms

---

## 3. User Trust

Users must trust the insights.

Mitigation:

- Provide transparent explanations
- Show reasoning behind suggestions

---

## 4. Cost of AI Inference

AI API costs may become high.

Mitigation:

- Optimize prompt usage
- Cache results
- Use smaller models where possible

---

# Conclusion

Siaplulus aims to simplify the job application process through **AI-powered career insights**.

By focusing on **CV intelligence, salary insights, and interview preparation**, the platform provides practical tools that help users become more competitive in the job market.

The MVP prioritizes **high-value features with fast execution**, enabling rapid validation and iteration within an early-stage startup environment.
