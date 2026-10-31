# Web Development Projects

A collection of three front-end web development projects created as part of my B.Tech Web Development coursework. These projects demonstrate the use of **HTML5** and **CSS3** to structure, style, and present information through clean, section-based and card-based website layouts.

The repository contains:
1. **FITZONE** – Gym and fitness centre website
2. **Foodie's Corner** – Food menu website
3. **EduPortal** – Student academic dashboard

> **Project scope:** The supplied project reports describe HTML5 and CSS3 implementations. They do not include JavaScript, a database, a server-side application, or an external CSS framework.

---

## 👨‍🎓 Student Details

| Detail | Information |
|---|---|
| Name | G. Rupesh Kumar |
| Course | B.Tech – Computer Science |
| University | Dr. RVR NRI University |
| Subject | Web Development |

*The project reports identify the course as B.Tech – CSE (AI & ML), First Year.*

---

## 🛠️ Technologies Used

| Technology / Tool | Usage |
|---|---|
| HTML5 | Page structure, headings, sections, navigation, forms, tables, and content |
| CSS3 | Styling, colours, spacing, layouts, cards, hover effects, and responsive rules |
| Visual Studio Code | Not specified in the supplied project reports |
| Git and GitHub | Not specified in the supplied project reports; intended repository hosting/version-control tools |

The documented website implementations use **HTML5 and CSS3**. VS Code, Git, and GitHub are listed above for repository workflow context only; the reports do not establish that they were used to build the original projects.

---

## 1. FITZONE – Fitness Website

### Description
FITZONE is a front-end website for a gym and fitness centre. It presents workout options, trainer categories, membership prices, facilities, a weekly class schedule, and a registration form. The page uses a dark header and hero area, orange action buttons, white content cards, and a dark footer.

### Objectives
- Present gym services and workout options in clearly labelled sections.
- Display trainer categories and membership choices.
- Show available facilities and a weekly class schedule.
- Provide a front-end registration form for visitor details and membership selection.

### Features
- Header with in-page navigation: Home, Programs, Trainers, Pricing, and Register.
- Hero section with the message **“BUILD YOUR BEST BODY”** and a **“Join Now”** button.
- Workout program cards: Strength Training, Cardio Fitness, and Yoga & Flexibility.
- Trainer categories: Strength Coach, Cardio Coach, and Yoga Instructor.
- Membership plans:
  - Basic – 999/- per month
  - Standard – 1,499/- per month
  - Premium – 2,499/- per month
- Facilities: Modern Equipment, Locker Rooms, and Personal Training.
- Weekly class schedule: Monday – Yoga, Wednesday – Cardio, and Friday – Strength.
- Registration form with name, email, phone, an additional text field, and membership dropdown.
- CSS card and button hover effects, smooth in-page scrolling, and a media query for smaller screens.

### Technologies
- HTML5
- CSS3 (CSS Grid, Flexbox, hover effects, and media query)

**Implementation note:** The report states that the registration form is a front-end interface only and is not connected to a backend, database, or email service. The “Join Now” button has no configured link or click action. The supplied three-column card grid is not reduced at the 768px breakpoint, so narrow-screen layout refinement remains a possible improvement.

### Output Screenshots

The following screenshots are retained from the supplied FITZONE project report.

![FITZONE homepage and workout programs](screenshots/fitzone-1.png)

![FITZONE trainers, membership plans, and facilities](screenshots/fitzone-2.png)

![FITZONE class schedule and registration form](screenshots/fitzone-3.png)

---

## 2. Foodie's Corner – Restaurant Theme Website

### Description
Foodie's Corner is a simple food menu webpage that displays a selection of food and drink items with photographs, names, and prices. It uses a warm colour theme and a card-based layout to make menu information easy to view.

### Objectives
- Present a small food and drink menu in one place.
- Display each menu item's photograph, name, and price clearly.
- Organise the menu using a flexible card layout.

### Features
- Header displaying **“Foodie's Corner”** and the tagline **“Delicious food,Happy Mood”**.
- **“Our special menu”** heading.
- Four menu cards:
  - Veg pizza – 199/-
  - Burger – 99/-
  - Biryani – 300/-
  - Milk shake – 89/-
- Food photographs sized to fit each card.
- Flexible layout that can wrap cards when the available width becomes smaller.
- White cards with rounded corners and light shadows.
- Hover effect that slightly enlarges a menu card.
- Footer message: **“Thank you ! Visit Again 💖”**.

### Technologies
- HTML5
- CSS3 (Flexbox, image sizing, card styling, shadows, and hover effects)

### Output Screenshot

![Foodie's Corner menu page](screenshots/restaurant.png)

---

## 3. EduPortal – Student Dashboard

### Description
EduPortal is a student academic dashboard website designed to organise important academic information. It provides a dashboard overview and focused pages or sections for profile details, semester results, attendance, subjects, examinations, and announcements.

### Objectives
- Provide an overview of student academic information.
- Display student identity, course, semester, and academic status.
- Present semester grades, credits, and SGPA in a table.
- Show subject-wise attendance percentages using progress bars.
- List subjects with course codes and credit values.
- Display an examination timetable and academic announcements.
- Provide sidebar navigation between dashboard areas and individual pages.

### Features
- Dashboard layout with a dark navy sidebar and main content area.
- Student profile information and active-student status.
- Summary cards for CGPA, overall attendance, total subjects, and credits earned.
- Semester results table with grades and credits.
- Subject-wise attendance percentages and coloured progress bars.
- Subject cards with course codes and credit values.
- Examination timetable with subjects, dates, and times.
- Announcements for internal examinations, attendance reminders, and assignment submissions.
- Shared CSS stylesheet and a responsive rule for screens up to 650px.

### Technologies
- HTML5
- CSS3 (Grid, layout styling, tables, progress bars, and responsive media query)

### Output Screenshots

The following screenshots are retained from the supplied EduPortal project report.

![EduPortal dashboard overview](screenshots/student-dashboard-1.png)

![EduPortal semester results and attendance](screenshots/student-dashboard-2.png)

![EduPortal subjects and examination schedule](screenshots/student-dashboard-3.png)

![EduPortal examination timetable and announcements](screenshots/student-dashboard-4.png)

---

## 📸 Project Screenshots

All eight screenshots below are extracted from the original screenshots embedded in the three supplied Word project reports and are included in this repository's `screenshots/` folder.

| Project | Included screenshots |
|---|---|
| FITZONE | `fitzone-1.png`, `fitzone-2.png`, `fitzone-3.png` |
| Foodie's Corner | `restaurant.png` |
| EduPortal | `student-dashboard-1.png` to `student-dashboard-4.png` |

---

## 📄 Project Documentation

The three PDF reports were supplied for preparing this README. The paths below are **suggested repository paths**, not confirmed existing GitHub paths. Create a `docs/` folder and add the corresponding PDF files there, or change the links to match the paths you use.

- [FITZONE Web Development Project Report](docs/FITZONE_Web_Development_Project_Report.pdf)
- [Foodie's Corner Web Development Project Report](docs/Foodies_Corner_Web_Development_Project_Report.pdf)
- [EduPortal Student Academic Dashboard Project Report](docs/EduPortal_Student_Academic_Dashboard_Project_Report.pdf)

---

## ▶️ How to Run

These are front-end HTML and CSS projects. No backend setup or database configuration is described in the supplied reports.

1. Clone or download this repository:
   ```bash
   git clone <your-repository-url>
   ```
2. Open the downloaded project folder in Visual Studio Code or another code editor.
3. Locate the relevant HTML entry file and keep its linked CSS file and any required image assets in the expected relative locations.
4. Open the HTML file in a web browser.

### Entry files identified in the reports

| Project | HTML entry file | Related files / notes |
|---|---|---|
| FITZONE | `index.html` | `style.css` |
| Foodie's Corner | `index(1).html` | `style(1).css` and the four supplied food image files (`pizza.jpg.jpeg`, `burger.jpg.jpeg`, `biryani.jpg.jpeg`, `milkshake.jpg.jpeg`) |
| EduPortal | `index.html` | `style.css`; the report also lists profile, results, attendance, subjects, exams, and announcements pages |

**EduPortal filename check:** The report identifies the attendance page as `attendance.htm`, while the sidebar link points to `attendance.html`. Make the filename and link target consistent before relying on that navigation link. The report also notes that `index.html` and `student_dash board.html` contain the same dashboard markup.

---

## 🎯 Learning Outcomes

Through these projects, I practised and demonstrated:

- Structuring webpages with HTML5 elements and meaningful sections.
- Applying CSS3 colours, typography, spacing, borders, and backgrounds.
- Creating card-based layouts using CSS Grid and Flexbox.
- Styling navigation links, buttons, forms, tables, and progress bars.
- Adding hover effects, shadows, rounded corners, and smooth scrolling.
- Using images and controlling image size with CSS.
- Building a multi-page website connected through navigation links and a shared stylesheet.
- Applying CSS media queries to improve layouts on smaller screens.

---

## 🚀 Future Improvements

The following are **future plans**, not features currently confirmed in the supplied project reports:

- Improve responsive layouts and test all pages on mobile, tablet, and desktop screen sizes.
- Add JavaScript for client-side interactions and form validation.
- Connect the FITZONE registration form to a suitable backend or form-handling service.
- Add ordering or enquiry functionality to Foodie's Corner.
- Connect EduPortal to a backend and database so that student, result, attendance, and timetable information can be managed dynamically.
- Review navigation targets, filenames, accessibility, and consistency across all pages.
- Deploy the completed projects so they can be accessed online.

---

## 👤 Author

**G. Rupesh Kumar**  
B.Tech – Computer Science  
Dr. RVR NRI University

---

*This README is based on the three supplied project reports. Features and technologies are described as documented; missing repository assets and paths are identified as placeholders rather than treated as uploaded files.*
