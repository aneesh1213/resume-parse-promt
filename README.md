# resume-parse-promt
Hi ChatGPT, I need your help to parse my resume into a JSON format. Here's my resume:

[Insert Resume Here]

Please extract the following information and format it in JSON:
- Name
- Contact Information (phone, email, address)
- Professional Summary
- Skills
- Experience (job title, company, duration, responsibilities)
- Education (degree, institution, year)
- Certifications
- Projects (title, description, technologies used)
- Languages

Output the parsed resume in JSON format.



John Doe
123 Main Street, Anytown, USA
(123) 456-7890
john.doe@example.com

Professional Summary:
Experienced software engineer with a strong background in developing scalable applications.

Skills:
- JavaScript
- Python
- React
- Node.js

Experience:
- Senior Software Engineer at TechCorp (Jan 2020 - Present)
  - Led the development of a new feature that increased user engagement by 20%.
  - Mentored junior developers.

- Software Engineer at DevSolutions (Jun 2017 - Dec 2019)
  - Developed and maintained web applications using JavaScript and React.
  - Collaborated with cross-functional teams.

Education:
- B.S. in Computer Science, University of Technology (2013 - 2017)

Certifications:
- AWS Certified Solutions Architect
- Certified Scrum Master

Projects:
- Project Management Tool
  - Developed a tool to help teams manage projects and tasks.
  - Used React, Node.js, and MongoDB.

Languages:
- English
- Spanish



Expected JSON output : 
{
  "name": "John Doe",
  "contact_information": {
    "address": "123 Main Street, Anytown, USA",
    "phone": "(123) 456-7890",
    "email": "john.doe@example.com"
  },
  "professional_summary": "Experienced software engineer with a strong background in developing scalable applications.",
  "skills": [
    "JavaScript",
    "Python",
    "React",
    "Node.js"
  ],
  "experience": [
    {
      "job_title": "Senior Software Engineer",
      "company": "TechCorp",
      "duration": "Jan 2020 - Present",
      "responsibilities": [
        "Led the development of a new feature that increased user engagement by 20%.",
        "Mentored junior developers."
      ]
    },
    {
      "job_title": "Software Engineer",
      "company": "DevSolutions",
      "duration": "Jun 2017 - Dec 2019",
      "responsibilities": [
        "Developed and maintained web applications using JavaScript and React.",
        "Collaborated with cross-functional teams."
      ]
    }
  ],
  "education": [
    {
      "degree": "B.S. in Computer Science",
      "institution": "University of Technology",
      "year": "2013 - 2017"
    }
  ],
  "certifications": [
    "AWS Certified Solutions Architect",
    "Certified Scrum Master"
  ],
  "projects": [
    {
      "title": "Project Management Tool",
      "description": "Developed a tool to help teams manage projects and tasks.",
      "technologies_used": [
        "React",
        "Node.js",
        "MongoDB"
      ]
    }
  ],
  "languages": [
    "English",
    "Spanish"
  ]
}
