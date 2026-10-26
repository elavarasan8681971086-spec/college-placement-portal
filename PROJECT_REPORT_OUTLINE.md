# Project Report Outline
## CampusPath — College Placement Portal

### Cover Page
Project title; student name and register number; department/institution; subject/lab course; guide name; academic year.

### Abstract
CampusPath is a responsive front-end portal that helps students explore sample campus placement opportunities and organise application progress. It displays role details, company, location, package/stipend, deadline, minimum CGPA, eligible branches and suggested skills. Users can search and filter opportunities, view details, track applications and update status. It uses HTML, CSS, JavaScript and browser localStorage. It does not submit applications to employers or connect to a server.

### 1. Introduction
Describe how placement announcements, eligibility rules and deadlines can be scattered across notices and messages. Explain the value of a searchable portal.

### 2. Problem Statement
Students may miss deadlines or lose track of application stages when placement information is spread across multiple sources. The project demonstrates one interface for sample opportunities and application tracking.

### 3. Objectives
- Display placement and internship opportunities.
- Show eligibility and deadline information.
- Search by company, role, location and skills.
- Filter full-time and internship roles.
- Track and update application status.
- Provide a responsive interface and deploy with GitHub Pages.

### 4. Scope
This is a static front-end prototype using fictional vacancy data and browser-local tracking. It has no accounts, shared multi-user data, live vacancy verification or employer application submission.

### 5. Technologies
HTML5 for structure; CSS3 for styling and responsive layout; JavaScript for search, filtering, details and application tracking; localStorage for demo persistence; GitHub Pages for static hosting.

### 6. Modules
1. Dashboard and summary statistics
2. Opportunity listing
3. Search and role-type filtering
4. Opportunity details and eligibility display
5. Application tracking and status updates
6. Local browser storage

### 7. Requirements
Hardware: computer, tablet or phone with a modern browser. Software: Chrome/Edge/Firefox, optional code editor, GitHub account for hosting. No build tools or database required.

### 8. Workflow
Open the site → load sample opportunities → search/filter → view opportunity details → track an application → update/remove status → save tracking information in localStorage.

### 9. File Structure
- `index.html`: page layout, cards, table and dialog.
- `style.css`: theme, cards, tables and responsive rules.
- `script.js`: sample data, rendering, search/filter and application tracking.

### 10. Testing Plan
| Test | Expected result | Status |
|---|---|---|
| Open index.html | Dashboard and cards display | To be tested |
| Search a role | Matching opportunities appear | To be tested |
| Filter Internship | Only internship roles appear | To be tested |
| View details | Details dialog opens | To be tested |
| Track opportunity | It appears in My Applications | To be tested |
| Change status | Selected status is shown | To be tested |
| Remove application | Application disappears | To be tested |
| Refresh browser | Applications persist in same browser | To be tested |
| Mobile screen | Layout adjusts to screen width | To be tested |

### 11. Advantages
Beginner-friendly; no server setup; demonstrates search, filtering, event handling and localStorage; responsive design; can be hosted as a static site.

### 12. Limitations
Fictional vacancies; data saved only in the current browser; no login; no employer application submission; eligibility rules are demo assumptions.

### 13. Future Enhancements
Add backend and database; secure student/placement-officer login; use verified vacancy sources; add resume upload; send deadline notifications; add placement analytics.

### 14. Deployment
Create public GitHub repository; upload the three files to root; open Settings → Pages; choose Deploy from a branch, `main`, `/(root)`; save and test the published URL.

### 15. Conclusion
CampusPath demonstrates a placement-focused interface using HTML, CSS and JavaScript. Opportunity search, eligibility details and application tracking distinguish it from student record management. A backend, authentication and verified vacancy source would be required for production use.

### References
- MDN Web Docs: https://developer.mozilla.org/
- GitHub Pages: https://docs.github.com/pages
- WHATWG HTML Standard: https://html.spec.whatwg.org/
