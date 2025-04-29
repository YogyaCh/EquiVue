
# Project Charter: Equivue

## Project Goal

Recruiters are human too—and they deserve tools that help them make better, faster, and fairer hiring decisions. Job seekers are human too—and no one should be overlooked just because they were the 100th applicant.

**Equivue** is an intelligent assistant for recruiters, designed to deeply analyze resumes beyond keyword matching and highlight candidates who truly align with a job—based not just on tools and titles, but on experience depth, coding practices, learning agility, and cultural fit.

For example, a candidate may not know the exact tool listed in the job description but may have demonstrable skills applying similar technologies—Equivue detects that potential and surfaces it. The recruiter can calibrate how much flexibility to allow using a threshold setting that matches the company’s standards and role needs.

Our tool doesn't replace the human recruiter. It amplifies them—by reducing resume fatigue, increasing candidate fairness, and placing decision-making controls directly in HR's hands.

## Project Scope

### In-Scope (MVP)

- Upload 1 job description + bulk upload of 100s–1000s of resumes
- Parse resumes and extract: education, experience, skills, projects, public links (LinkedIn, GitHub, portfolios)
- Enrich candidate profiles via web scraping/APIs
- Smart JD parsing to extract implicit and explicit role requirements
- Resume–JD match scoring system based on skill similarity, transferable experience, coding depth/breadth (via GitHub)
- HR-configurable filters (e.g., prioritize clean code, newer tools, team roles)
- Candidate match report with justifications
- Shortlist view for recruiters with ranking and notes

### Future Scope (Planned Enhancements)

- Screening call automation (LLM-powered phone/chat screening)
- ATS integrations (Workday, Greenhouse)
- Internal team feedback loop integration
- Bias detection and mitigation
- Talent pool analytics across roles and regions

### Out-of-Scope (for MVP)

- Real-time interview scheduling
- Behavioral or psychometric testing
- Private LinkedIn API usage (unless permitted)

## Key Stakeholders

- **Recruiters/HR Teams**: Primary users who upload JDs/resumes, set match criteria, and view reports
- **Hiring Managers**: Receive candidate shortlists and qualitative assessments
- **Candidates**: Indirect stakeholders whose resumes are processed—goal is fairness and representation
- **Engineering Team**: Builds and maintains the tool, APIs, frontend, and infrastructure
- **Product Manager**: Oversees alignment of features with user needs and HR workflows
- **Compliance/Legal (Future)**: Ensures ethical AI use, especially for fairness, data handling, and GDPR/EEOC compliance

## Guiding Principles

- **Empathy**: Respect for both recruiter workload and candidate dignity
- **Transparency**: Clear scoring logic, human-over-the-loop control
- **Fairness**: Help uncover hidden talent often missed in traditional ATS filters
- **Scalability**: Handle thousands of resumes with speed and reliability
- **Customizability**: Let each HR team define their own notion of a good fit
