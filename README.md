# Lab 2: Tool Library REST API with Express
- Stanley Nguyen
- Humber College
- CPAN-212-RNA
- Dor Zauri
- September 27, 2026

---

## 1. What This Project Is
This lab I work on building a REST API behind its catalogue with Express 5. 

---
## 2. How to Run the Project
1) npm install
2) .env.example .env
3) npm run dev

---
## 3. PORT Environment Variables
- The API runs at http://localhost:4000. Set PORT in .env to use a different port.

---
## 4. List of the Routes
| Method | Path | What it does |
|--------|------|--------------|
| GET | /api/tools | Every tool. `?category=garden` keeps only one category. |
| GET | /api/tools/:id | One tool, or 404. |
| POST | /api/tools | Create a tool (201), or 400 with invalid fields. |
| PUT | /api/tools/:id | Replace a tool’s fields (200), 400 or 404. |
| DELETE | /api/tools/:id | Remove a tool (204), or 404. |

---
## 5. AI Use
- Microsoft Copilot to help figure out and learn how to use bruno (Did not have to use bruno yet after reading the updated lab 2)
- Used Copilot to understand certain syntax of codes every so often and small errors I created in my code 

---
## 6. Credit
- Used the cpan212-fall-2026/labs/lab-2-starter folder from professor Dor github page to help set up and get a head start in lab 2