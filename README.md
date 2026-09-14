# Campus Voice Hub

Build a Student Complaint Portal web application matching the layout, structure, and feature set from the attached reference screenshot, but with a clean, minimal light theme featuring soft light yellow/cream backgrounds and warm orange accents (not dark mode).

Key elements to include:
1. Navigation Sidebar:
   - Header with graduation cap icon and "Student Complaint Portal"
   - Nav items: Home (active), New Complaint, My Complaints, Track Status, Notifications (badge count 3), Knowledge Base, Profile, Settings
   - Bottom branding card: "Better Campus Together" with warm abstract wave accents

2. Top Bar:
   - Search bar ("Search complaints, keywords... Ctrl + K")
   - Notification bell with dropdown
   - User profile badge ("Rahul Sharma", B.Tech - Computer Science)

3. Welcome Hero Banner:
   - "Welcome back, Rahul 👋"
   - "Your voice matters. Submit your complaint and help us make the campus better."
   - "Submit New Complaint >" primary button
   - Campus architectural graphic/photo
   - Motivational quote: "A better campus starts with your voice."

4. Overview & Quick Actions (Right Column):
   - Metric cards: Total Complaints (2), In Progress (1), Resolved (1), Pending (0)
   - Quick Actions: Submit New Complaint, Track Your Complaint, View FAQs
   - Campus admin quote card with subtle warm wavy accents

5. Complaint Categories Grid (6 cards):
   - Academic Issues (Results, Attendance, Faculty)
   - Infrastructure (Hostel, Classrooms, Labs)
   - Facilities (Wi-Fi, Library, Sports)
   - Behavior & Discipline (Ragging, Harassment)
   - Fees & Payments (Refunds, Dues, Scholarship)
   - Other (General / Miscellaneous)
   - Clicking any category opens the complaint submission flow pre-selecting that category

6. Recent Complaints Table:
   - Header with "View All ->"
   - Table columns: ID (#SC-2025-0148, etc.), Subject, Category, Date, Status pill badges (In Progress, Pending, Resolved)
   - Interactive rows allowing the user to view full status and timeline

7. Complaint Submission Flow:
   - Modal or dedicated view to file a complaint (Title, Category, Urgency, Description, Attachment upload, Anonymous toggle, Submit)
   - Track status modal/drawer with timeline stepper (Submitted -> Under Review -> In Progress -> Resolved)

Visual styling:
- Palette: Soft warm light yellow / cream background (`bg-amber-50/30`, ivory), warm crisp card backgrounds with delicate warm borders, vibrant orange and amber primary accents and buttons, deep charcoal text for crisp legibility. Minimal, modern, and polished.

This project was built with [Lovable](https://lovable.dev).

## Build with Lovable

Continue developing this project in the [Lovable editor](https://lovable.dev/projects/c410d911-d473-4828-8a1e-febbd3914ea5).

- **Ship faster**: describe what you want to build and Lovable handles the code.
- **Stay in sync**: every change made in Lovable is committed straight to this repository.
- **Full ownership**: this code is yours. Push to `main` on GitHub and your changes sync back into Lovable, ready for your next prompt.

## Development

Prefer working locally? You need Node.js and npm — [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating).

```sh
git clone <this-repository-url>
cd <repository-name>
npm i
npm run dev
```
