# ATS Resume Checker

A simple browser-based tool that analyzes your PDF resume against Applicant Tracking Systems (ATS).

## Features

- Upload a PDF resume and get an instant ATS score (0–100)
- Select your target job role for relevant keyword matching
- Score breakdown across 4 categories: Keyword Match, Formatting, Resume Length, and Action Verbs
- Highlights found and missing keywords
- Detects formatting issues and gives actionable improvement tips

## How to Use

1. Open `index.html` in any modern browser
2. Select your target job role from the dropdown
3. Upload your resume as a PDF file
4. Click **Analyze My Resume**
5. Review your score and follow the recommendations

## Scoring

| Category       | Max Points |
|----------------|------------|
| Keyword Match  | 40         |
| Formatting     | 30         |
| Resume Length  | 15         |
| Action Verbs   | 15         |

## Supported Job Roles

- Software Developer / Engineer
- Data Scientist / Analyst
- Marketing / Digital Marketing
- Finance / Accounting
- UI/UX Designer
- Project Manager / MBA
- General / Other

## Tech Stack

- Plain HTML, CSS, JavaScript
- [PDF.js](https://mozilla.github.io/pdf.js/) for PDF text extraction

## Requirements

- No installation needed
- Works entirely in the browser
- PDF must be text-based (not a scanned image)
