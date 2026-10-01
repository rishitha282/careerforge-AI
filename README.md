# careerforge-AI
VAbsolutely — here is a complete `README.md` file for your **CareerForge AI** project.

````markdown
# 🚀 CareerForge AI

### AI-Powered Career Guidance & Job Matching Platform

CareerForge AI is a modern, responsive, browser-based career guidance platform that helps students and job seekers understand their skills, analyze their resumes, discover suitable jobs, identify skill gaps, explore global career destinations, and build a personalized career roadmap.

---

## 🌟 Project Overview

Choosing the right career can be difficult when students do not know:

- What skills they already have
- Which jobs match their profile
- Which skills they are missing
- What they should learn next
- What salary ranges they can expect
- Which countries offer relevant opportunities
- How to track their job applications

**CareerForge AI** brings these features together in one interactive platform.

The application analyzes the resume provided by the user and generates career insights using browser-based JavaScript and NLP-style keyword analysis.

---

# ✨ Features

## 🏠 1. AI-Powered Home Page

The landing page includes:

- CareerForge AI branding
- Modern dark/glassmorphism UI
- Animated AI robot
- AI scanning animation
- Career-focused hero section
- Smooth navigation
- Responsive design

### Main Actions

- Analyze My Resume
- Explore Jobs
- Try Demo Resume

---

# 📄 2. Resume Analyzer

Users can provide their resume using:

- PDF
- DOCX
- TXT
- Copy and paste

The application extracts available resume text directly in the browser.

### Extracted Information

CareerForge AI detects:

- Name
- Degree
- Branch / specialization
- Graduation year
- Programming languages
- AI / ML skills
- Web development skills
- Database skills
- Cloud skills
- Tools
- Frameworks
- Projects
- Certifications
- Experience
- Languages

---

# 🧠 3. Resume Analysis

After analyzing the resume, the application calculates a resume score based on detected information.

The analysis includes:

- Resume score
- Education
- Skills
- Experience
- Projects
- Certifications
- Languages
- Graduation information

The score is calculated dynamically from the resume content.

---

# 📊 4. Skill Match Analysis

CareerForge AI calculates skill coverage across different categories.

### Skill Categories

#### Programming

- Python
- Java
- C
- C++
- JavaScript

#### AI & Machine Learning

- Artificial Intelligence
- Machine Learning
- Deep Learning
- NLP
- TensorFlow
- PyTorch

#### Web Development

- HTML
- CSS
- JavaScript
- React
- Node.js

#### Data

- SQL
- Excel
- Power BI
- Pandas
- NumPy

#### Cloud & DevOps

- AWS
- Azure
- Docker
- Git
- GitHub

#### Databases

- MySQL
- PostgreSQL
- MongoDB

Skill percentages are calculated dynamically.

---

# 💼 5. Smart Job Matching

The application contains a browser-based job database.

Example career roles include:

- AI / ML Engineer
- Data Scientist
- Data Analyst
- Python Developer
- Full Stack Developer
- Machine Learning Intern
- AI Research Intern
- Cloud Engineer
- DevOps Engineer
- Software Engineer
- Frontend Developer

Each job contains:

- Job title
- Company
- Country
- City
- Required skills
- Preferred skills
- Experience
- Salary range
- Currency
- Language requirements
- Work mode
- Job type
- Official career/application URL

---

# 🎯 6. Dynamic Job Matching

CareerForge AI calculates job compatibility using the user's detected skills.

The core skill matching formula is:

```text
Skill Match =
Matched Required Skills / Total Required Skills × 100
````

Additional resume information such as:

* Education
* Projects
* Certifications
* Experience

is also considered when calculating the job compatibility score.

---

# 🔎 7. Job Filters

Users can filter jobs by:

* Job title
* Company
* Country
* City
* Minimum match percentage
* Remote
* Hybrid
* On-site
* Internship
* Full-time

The job cards update dynamically without reloading the page.

---

# 📚 8. Skill Gap Analysis

Users can select a target job and see:

### Skills You Have

Skills already detected in the resume.

### Skills You Need

Skills required by the selected job.

### Skill Gap

Only missing required skills are displayed.

This helps users understand exactly what they need to learn.

---

# 🎓 9. Learning Recommendations

For missing skills, CareerForge AI provides:

* Why the skill matters
* Difficulty level
* Estimated learning time
* Suggested project

Example:

```text
Machine Learning

Difficulty:
Intermediate

Estimated Learning:
5–8 weeks

Suggested Project:
House Price Prediction Model
```

---

# 🛣️ 10. Personalized Career Roadmap

CareerForge AI creates a roadmap based on the user's missing skills.

Example roadmap:

```text
1. Learn Python
2. Learn SQL
3. Learn Machine Learning
4. Learn TensorFlow
5. Build practical projects
6. Strengthen portfolio
7. Prepare for interviews
8. Apply to matching jobs
```

The roadmap changes according to the selected career and detected skills.

---

# 🌍 11. Global Destination Explorer

Users can compare career destinations including:

* 🇮🇳 India
* 🇩🇪 Germany
* 🇨🇦 Canada
* 🇦🇺 Australia
* 🇸🇬 Singapore
* 🇬🇧 United Kingdom
* 🇺🇸 United States

The destination section includes:

* Animated globe
* Revolving airplane
* Currency
* Estimated salary
* Cost of living
* Housing
* Food
* Transportation
* Utilities
* Language information
* Career-readiness information

---

# 💰 12. Salary Information

The platform displays estimated salary ranges.

Example:

```text
India
₹4.5L – ₹12L / year

Germany
€45K – €85K / year

United States
$70K – $145K / year
```

### Important

Salary values included in this prototype are estimates for career-planning purposes.

Users should verify current salary information through:

* Official company career pages
* Government sources
* Authoritative employment sources
* Current job listings

---

# 📝 13. Direct Job Application

The **Apply** button opens the configured employer's official career/application page in a new browser tab.

This allows users to continue the application directly through the employer's website.

The application tracker also records the job as:

```text
Interested
```

when the user first clicks Apply.

---

# 📋 14. Application Tracker

Users can track applications using statuses such as:

* Interested
* Applying
* Applied
* Interview
* Selected
* Rejected

The tracker stores:

* Job
* Company
* Application date
* Match percentage
* Application status

Application information is saved using browser `localStorage`.

---

# 📊 15. Career Dashboard

The dashboard displays:

* Resume Score
* Overall Skill Match
* Matching Jobs
* Skill Gaps
* Recommended Career
* Top Skill to Learn

The dashboard updates automatically after resume analysis.

---

# 🤖 16. AI Career Assistant

CareerForge AI includes a floating career assistant.

The assistant can answer questions such as:

```text
What skills should I learn first?
```

```text
Which job matches me?
```

```text
Why is my score low?
```

```text
What projects should I build?
```

```text
What salary can I expect?
```

The assistant uses the resume and job database available in the browser.

It is a browser-based rule-driven assistant and does not require an external AI API key.

---

# 🧪 17. Demo Resume

Users can click:

```text
Try Demo Resume
```

A sample resume is automatically inserted:

```text
Alex Kumar

B.Tech Artificial Intelligence

Skills:
Python
Java
SQL
HTML
CSS
JavaScript
Machine Learning
Git
GitHub
Pandas
NumPy
Artificial Intelligence
NLP

Projects:
AI Resume Analyzer
Student Management System
Machine Learning Prediction System
```

The demo goes through the same analysis functions as a user-provided resume.

---

# 💾 18. Local Storage

CareerForge AI uses browser `localStorage` to preserve:

* Resume text
* Extracted resume information
* Application tracker
* Selected destination
* User preferences

Therefore, information can remain available after refreshing the page.

---

# 🔄 19. Skill Normalization

The application recognizes common skill aliases.

Examples:

```text
JS → JavaScript

ReactJS → React

ML → Machine Learning

AI → Artificial Intelligence

Node → Node.js

Postgres → PostgreSQL
```

Matching is case-insensitive and whitespace-aware.

---

# 🧩 20. Single Source of Truth

The core skill-matching function is:

```javascript
function calculateSkillMatch(userSkills, requiredSkills) {
    // normalize skills
    // compare skills
    // identify matched skills
    // identify missing skills
    // calculate percentage
}
```

It returns:

```javascript
{
    percentage: 0,
    matchedSkills: [],
    missingSkills: [],
    totalRequired: 0,
    totalMatched: 0
}
```

This function is reused throughout the application for:

* Skill analysis
* Job matching
* Skill gap analysis
* Job details
* Career roadmap
* Dashboard

---

# 🎨 UI / UX

CareerForge AI uses a modern technology-inspired design.

### Design Features

* Dark theme
* Glassmorphism
* Gradient effects
* Responsive cards
* Animated AI robot
* Animated scanning line
* Animated globe
* Revolving airplane
* Progress bars
* Circular score indicators
* Responsive layout
* Mobile navigation
* Smooth scrolling
* Interactive buttons
* Icon-based interface

---

# 🛠️ Technologies Used

## Frontend

* HTML5
* CSS3
* JavaScript ES6+

## Libraries

### PDF.js

Used for browser-side PDF text extraction.

### Mammoth.js

Used for extracting text from DOCX files.

### Font Awesome

Used for interface icons.

### Google Fonts

Used for modern typography.

---

# 📁 Project Structure

This project is designed as a single-file application.

```text
CareerForge-AI/
│
├── index.html
│
└── README.md
```

All major HTML, CSS and JavaScript functionality is contained inside:

```text
index.html
```

---

# 🚀 How to Run

## Method 1 — Directly in Browser

1. Download or create `index.html`.
2. Double-click the file.
3. It will open in your browser.

Recommended browsers:

* Google Chrome
* Microsoft Edge
* Firefox

---

## Method 2 — VS Code

1. Open VS Code.
2. Create a folder called:

```text
CareerForge-AI
```

3. Create:

```text
index.html
```

4. Paste the project code.
5. Save the file.
6. Open it using a browser.

You can also use the VS Code Live Server extension.

---

# 📌 Browser Requirements

The application works best with a modern browser that supports:

* JavaScript ES6+
* Local Storage
* File APIs
* PDF.js
* Modern CSS

An internet connection is recommended because some interface libraries are loaded from CDNs.

---

# 🔐 Privacy

Resume analysis is performed in the browser using JavaScript.

The application does not require a backend server for its core functionality.

Resume data is stored in the browser's local storage when saved by the application.

For a production version, additional privacy and security controls should be implemented before handling sensitive personal information.

---

# ⚠️ Important Limitations

CareerForge AI is a frontend prototype designed for career guidance and hackathon demonstration.

The current version does not provide:

* Live job vacancies
* Real-time salary APIs
* Real-time company databases
* Guaranteed job availability
* Professional career certification
* Automated submission of job applications

The displayed job and salary information should be verified before making actual career decisions.

---

# 🔮 Future Improvements

Possible future versions can include:

### 🤖 Real AI Integration

Connect the application to an LLM API for deeper resume analysis and personalized recommendations.

### 🌐 Live Job APIs

Integrate legitimate job APIs to retrieve current vacancies.

### 📄 Advanced Resume Parsing

Support:

* Better PDF parsing
* DOC parsing
* Resume section detection
* Experience extraction
* Project extraction
* Certification extraction

### 🔑 User Accounts

Add:

* Login
* Registration
* Cloud profiles
* Saved jobs
* Saved resumes

### 📈 Advanced Analytics

Add:

* Career growth trends
* Skill demand trends
* Salary trends
* Job-market analysis

### 🎓 Learning Platform Integration

Recommend courses from legitimate learning platforms based on missing skills.

---

# 🏆 Hackathon Value

CareerForge AI addresses a real-world problem:

> Students often have skills but struggle to understand which careers and jobs fit those skills.

The platform provides a complete career journey:

```text
Resume
   ↓
AI Analysis
   ↓
Skill Detection
   ↓
Skill Match
   ↓
Job Recommendations
   ↓
Skill Gap
   ↓
Learning Recommendations
   ↓
Career Roadmap
   ↓
Job Application
   ↓
Application Tracking
```

This makes CareerForge AI suitable for:

* College Hackathons
* Technical Expos
* AI Projects
* Web Development Projects
* Final Year Project Demonstrations
* Career Technology Demonstrations

---

# 👥 Target Users

CareerForge AI is designed for:

* College students
* Fresh graduates
* Job seekers
* Internship seekers
* Career switchers
* Early-career developers
* AI/ML students
* Data science students
* Software engineering students

---

# 📜 License

This project can be used for educational and hackathon purposes.

Before using third-party libraries or external company/job information in a production application, review their respective licenses and usage terms.

---

# 👨‍💻 Project

## CareerForge AI

### Turn Your Resume Into Your Future Career.

Built as an interactive AI-inspired career guidance platform using HTML, CSS and JavaScript.

---

```

Save this as **`README.md`** in the same folder as your `index.html`.
```
