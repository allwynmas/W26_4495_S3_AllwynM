| Date       | Number of Hours | Description of Work |
|------------|------------------|----------------------|
| 15th Jan   | 2                | Conducted initial research on OWASP Top 10 vulnerabilities and reviewed documentation for DVWA, WebGoat, and Juice Shop. Compared their learning approaches and identified opportunities for a simpler, framework based platform. |
| 20th Jan   | 1                | Participated in instructor led project consultation. Discussed project direction, technology stack, and how to embed vulnerabilities safely within a Spring Boot MVC application. |
| 21st Jan   | 1.5              | Co drafted the pre proposal for instructor approval. Summarized research findings and outlined the initial problem definition, research questions, and project scope. |
| 22nd Jan   | 1                | Researched Spring Boot security misconfigurations and common vulnerability patterns (e.g., insecure authentication flows, improper input validation). Documented potential implementation strategies. |
| 23rd Jan   | 1                | Attended scheduled Friday team meeting. Finalized task distribution and reviewed proposal template. |
| 23rd Jan   | 1.5              | Created and organized the GitHub Project Kanban board. Added tasks for proposal writing, research, vulnerability implementation, and documentation. Assigned responsibilities and set up workflow columns. |
| 24th Jan   | 2                | Collaborated with Thilan on drafting the full project proposal. Wrote sections on scope, methodology, and technology stack. Ensured the proposal met the rubric requirements for introduction and research design. |
| 25th Jan   | 2                | Continued refining the proposal independently. Reviewed the draft for clarity, strengthened the methodology section, and added additional justification for the selected technology stack. Prepared notes for the upcoming Saturday meeting. |
| 26th Jan   | 1                | Reviewed and refined the proposal draft. Added details to the methodology and expected results sections. Submitted the document to Blackboard and GitHub. |
| 27th Jan   | 1                | Participated in in‑class proposal check‑in. Instructor requested adding industry data to justify the project. Reviewed Fortinet’s 2024 Skills Gap Report and incorporated the statistic that 58% of IT decision‑makers cite lack of hands‑on skills as a top cause of breaches.  |
| 31st Jan   | 1                | Attended scheduled Friday team meeting. Discussed Week 5 implementation tasks, including setting up the Spring Boot skeleton and configuring the H2 database. |
| 1st Feb    | 1.5              | Attended scheduled Saturday team meeting. Reviewed architecture outline and refined backend workflow diagrams. Finalized vulnerability placement strategy for SQL Injection, Broken Authentication, and IDOR. |
| 3rd Feb    | 1                | Began setting up backend project structure. Created initial controller and service templates to prepare for SQL Injection implementation. |
| 4th Feb    | 1.5              | Completed Spring Boot skeleton setup. Verified project builds successfully, configured H2 database, and tested basic backend routing. |
| 5th Feb    | 1                | Conducted deeper research on SQL Injection exploitation in Java applications. Reviewed insecure query patterns and prepared notes for implementing the first vulnerability. |
| 6th Feb    | 1                | Drafted backend‑focused content for Progress Report 1, summarizing architecture planning, backend setup, and SQL Injection research. |
| 7th Feb | 2 | Began implementing the SQL Injection (SQLi) module. Set up the `/sql-injection` controller, added request parameter handling, and prepared backend structure for safe and vulnerable query execution. |
| 9th Feb | 2 | Implemented the vulnerable SQL query using string concatenation. Verified that SQLi payloads produced unsafe behavior and returned unintended results. |
| 10th Feb | 1.5 | Implemented the safe SQL query using prepared statements. Ensured parameterized queries blocked injection attempts and added backend logic to toggle between safe and vulnerable modes. |
| 13th Feb | 1 | Weekly team meeting. Reviewed SQLi progress, discussed RXSS routing improvements, and planned controller refactoring for better modularity. |
| 14th Feb | 1 | Continued team meeting. Finalized SQLi backend logic and confirmed the structure for GET‑based reflection in the upcoming RXSS controller. |
| 15th Feb | 1 | Added backend support for executed SQL query display and improved error handling for malformed SQL payloads. Ensured the application returned meaningful error messages without breaking. |
| 17th Feb | 1 | Created a dedicated `RxssController` to separate XSS logic from other modules. Cleaned up routing and ensured proper GET‑based reflection behavior. |
| 18th Feb | 1 | Adjusted the CSP header from `Content-Security-Policy` to `Content-Security-Policy-Report-Only` to allow XSS payload execution for demonstration while still logging violations. |
| 20th Feb | 1 | Performed integration testing for SQLi and RXSS modules. Verified backend compatibility with UI components, dropdown behavior, and scroll helper functionality. |
| 21st Feb | 1.5 | Wrote backend sections of SQLi implementation details and RXSS controller explanation. Participated in recording the midterm demonstration video. Uploaded updated code, the completed midterm report, and the demonstration video to the GitHub repository.  |

