# 🌿 Meadow House Repairs

**A simple, accessible repair reporting and maintenance tracking web application.**

## 📌 About the Project

Meadow House Repairs is a browser-based maintenance management system designed to help staff report repair issues, track their progress, and record how each repair was completed.

The application provides a centralised dashboard where users can submit repair reports, assign priorities, update job statuses, and maintain a history of progress updates.

Meadow House is a fictional property created for demonstration purposes.

## ✨ Features

- **Repair Reporting:** Submit repair requests with a description and reporter name.
- **Priority Selection:** Mark repairs as either Normal or Urgent.
- **Job Tracking:** Monitor each repair through three stages: New, In Progress, and Completed.
- **Progress Updates:** Add dated notes to document work carried out on ongoing repairs.
- **Completion Notes:** Record the outcome before marking a repair as completed.
- **Dashboard Statistics:** View the total number of jobs and the number of jobs in each status.
- **Repair History:** Keep a chronological record of status changes and updates.
- **Automatic Job IDs:** Generate unique identifiers for repair jobs, such as `MH-0001`.
- **Local Data Storage:** Save job information in the browser using `localStorage`, allowing it to persist across page reloads in the same browser.
- **Form Validation:** Prevent empty descriptions, reporter names, progress notes, and completion notes.
- **Responsive Design:** Adapt the layout for desktop and mobile screens.
- **Accessibility:** Include form labels, keyboard focus indicators, accessible status announcements, and reduced-motion support.

## 🛠️ Technologies Used

- **HTML5** – Structures the application and its forms.
- **CSS3** – Provides the styling, responsive layout, colour palette, and visual components.
- **JavaScript** – Handles form validation, job creation, status updates, progress history, and dashboard statistics.
- **Browser Local Storage** – Stores repair records locally in the user's browser.
- **Google Fonts** – Uses Fraunces and DM Sans for typography.

## 🚀 Getting Started

No installation or additional dependencies are required.

### Run Locally

1. Download or clone this repository.
2. Locate the `index.html` file.
3. Open `index.html` in a modern web browser.
4. Submit a repair report to create your first job.
5. Update its status, add progress notes, and record its completion.

Alternatively, open the project in a code editor such as Visual Studio Code and use the Live Server extension to preview it.

## 📖 How to Use

### 1. Report a Repair
Enter a repair description, provide the reporter's name, select a priority, and submit the form.

### 2. Track Progress
New jobs appear in the Repair Jobs section. Select **Move to In Progress** when work begins.

### 3. Add Progress Notes
While a job is in progress, add updates describing the work carried out. Each update is saved with a timestamp in the job history.

### 4. Complete a Repair
Enter a completion note describing the outcome and select **Mark as Completed**.

### 5. Monitor All Jobs
Use the dashboard statistics, status badges, and progress indicators to monitor repair activity.

## 💾 Data Storage

Repair records are stored using the browser's `localStorage` under the key `meadowHouseJobs.v2`.

- Data persists across page reloads in the same browser and storage environment.
- Records are not stored on a remote server or shared automatically between users or devices.
- Clearing the browser's site data may remove saved records.
- This project does not include user authentication or a central database.

## 🔒 Privacy and Safety

Meadow House is fictional. Use made-up names and repair details only.

Do not enter real personal information, confidential maintenance records, or sensitive care-related information. The application is a front-end demonstration and is not designed for handling real-world sensitive records.

## 🎯 Project Objectives

- Demonstrate practical front-end web development.
- Apply JavaScript to interactive forms and dynamic content.
- Implement client-side validation and persistent browser storage.
- Present information using clear status indicators and progress tracking.
- Apply responsive design and accessibility principles.

## 🔮 Future Improvements

Potential enhancements include:

- User authentication and role-based access.
- A central database for sharing records across devices.
- Search, filtering, and sorting of repair jobs.
- Editing and deleting existing repair reports.
- Photo attachments for maintenance issues.
- Notifications for urgent or overdue repairs.
- Exporting job records to CSV or PDF.
- Unit tests and automated accessibility checks.

## 📂 Project Structure

```text
meadow-house-repairs/
├── index.html    # Application structure, styling, and JavaScript
└── README.md     # Project documentation
```

## 📄 License

This project is available for educational and demonstration purposes. Add a specific open-source licence if you intend to distribute or reuse the project under formal licence terms.

---

**Built with HTML, CSS, and JavaScript. 🌱**
