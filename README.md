# The Cue Club - Billiard Table Timing & Management System

## 1. Business Name and Description
* **Business Name:** The Cue Club
  
* **Description:** The Cue Club is a modern, web-based billiard hall management application designed to automate table timing, streamline floor operations, and enhance customer engagement
  
* **Target Users:** 
  * **Hall Administrators / Staff:** Manage table active sessions, adjust or extend timers, review customer support tickets, and award loyalty points
    
  * **Players / Customers:** Register accounts, view live table availability across 12 units in real-time, claim free hour rewards, and communicate privately with support

## 2. Problem Being Solved
Traditional billiard halls often rely on manual timers, paper logs, or fragmented chat groups, which lead to:
* Billing errors or missed time tracking when tables run past their slots
* Lack of real-time visibility for customers wanting to check table availability before arriving
* Unorganized customer service interactions mixed together in group chats
* Inefficient loyalty tracking for rewarding regular patrons

**The Solution:** This system provides a centralized, cloud-synced digital dashboard where table statuses update instantly across all devices, customer support is handled individually per user, and a built-in point reward system automatically incentivizes repeat players

## 3. Feature List
* **Landing & Navigation Page:** A high-end welcome view allowing users to jump directly into the live floor, player portal, or admin login
* **Live Table Management (12 Units):** Real-time countdown timers, occupancy badges, and dynamic status syncing across all connected devices using Firebase
* **User Authentication & Profiles:** Secure registration and login supporting passwords, user sessions, and persistent local tracking
* **Points & Rewards System:** Users earn points (awarded one-by-one by admins) and can redeem every 10 points for a free 1-hour play pass. New accounts automatically receive a welcome free hour pass.
* **Individualized Support Chat (CRUD Support):** Private support channels where administrators can converse one-on-one with specific users, clear chat histories (Delete), and award points directly inside active support threads
* **Admin Time Configuration & Extension (CRUD Controls):** Administrators can set custom durations (Create/Update), choose preset intervals (30m, 1h, 2h), instantly terminate sessions (Delete), or extend ongoing game times (+15m, +30m, +1h)

## 4. Tech Stack Used
* **Frontend:** Vanilla HTML5, Tailwind CSS (via CDN for responsive modern styling), and modern JavaScript (ES6+ Modules)
* **Backend & Database:** Firebase Realtime Database (for real-time synchronization of tables, user profiles, and chat logs)
* **Deployment Platform:** Netlify (for instant static hosting and drag-and-drop updates)

## 5. Setup and Run Instructions (Tested from a clean machine)
Follow these steps to run the project locally or deploy it

1. **Clone or Download the Repository:**
   Download or clone this repository containing the `index.html` file into a local folder on your computer

2. **Open the Project:**
   Navigate into the folder and open `index.html` using any modern web browser (Google Chrome, Microsoft Edge, Safari, or Firefox). Alternatively, open the folder inside a code editor like Visual Studio Code and use the Live Server extension.

3. **Database Configuration:**
   The application is linked to a secure Firebase Realtime Database instance via the modular SDK script. Ensure that your Firebase project has the Realtime Database enabled in Test Mode so that read/write operations execute smoothly.

4. **Production Deployment (Optional):**
   To host it live, go to Netlify Drop (app.netlify.com/drop) and drag-and-drop your project folder to generate a live public URL instantly.

## 6. AI Tools Used & AI Disclosure
**AI Disclosure Statement:**
This project was developed using a human-in-the-loop collaborative workflow with generative artificial intelligence. The AI assistant acted as a technical collaborator, pair programmer, and architectural consultant under the direct supervision, testing, and direction of the human developer.

* **Primary AI Tool:** Gemini (Google)
* **What it was used for:**
  * **Code Architecture & Generation:** Designing the single-page application structure, writing vanilla JavaScript ES6+ modules, and integrating the Firebase Realtime Database SDK (V10).
  * **UI/UX Design:** Structuring the minimalist black-and-white aesthetic using Tailwind CSS utility classes and building responsive layouts for up to 12 simultaneous billiard tables.
  * **Debugging & Problem Solving:** Troubleshooting asynchronous Firebase event listeners, resolving state synchronization loops, and structuring database JSON nodes.
* **Human Oversight:** All generated code structures, database schemas, and security choices were systematically reviewed, tested locally, deployed via Netlify, and verified by the developer to ensure functional correctness.

---

## 7. Test Accounts with Sample Credentials

### System Administrator Account[span_30](start_span)[span_30](end_span)
* **Username:** `admin`
* **Password:** `admin`
* *Capabilities:* Unlocks table time configurations, extension tools, admin chat lists, and point-awarding features.

### Regular Player Account (Sample)
* **Username:** `PLAYER1`
* **Password:** `password123`
* *Capabilities:* Allows testing of account registration, live table viewing, free-hour pass claims, point redemptions, and private support ticketing. 
*(Note: You can also use the "Player Account Login" button to register any custom username and password on the fly to test new account creation).
