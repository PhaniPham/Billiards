# The Cue Club - Billiard Table Timing & Management System

## 1. Business Name and Description
* **Business Name:** The Cue Club[span_1](start_span)[span_1](end_span)
* **Description:** The Cue Club is a modern, web-based billiard hall management application designed to automate table timing, streamline floor operations, and enhance customer engagement[span_2](start_span)[span_2](end_span). 
* **Target Users:** 
  * **Hall Administrators / Staff:** Manage table active sessions, adjust or extend timers, review customer support tickets, and award loyalty points[span_3](start_span)[span_3](end_span).
  * **Players / Customers:** Register accounts, view live table availability across 12 units in real-time, claim free hour rewards, and communicate privately with support[span_4](start_span)[span_4](end_span).

---

## 2. Problem Being Solved
Traditional billiard halls often rely on manual timers, paper logs, or fragmented chat groups, which lead to:
* Billing errors or missed time tracking when tables run past their slots[span_5](start_span)[span_5](end_span).
* Lack of real-time visibility for customers wanting to check table availability before arriving[span_6](start_span)[span_6](end_span).
* Unorganized customer service interactions mixed together in group chats[span_7](start_span)[span_7](end_span).
* Inefficient loyalty tracking for rewarding regular patrons[span_8](start_span)[span_8](end_span).

**The Solution:** This system provides a centralized, cloud-synced digital dashboard where table statuses update instantly across all devices, customer support is handled individually per user, and a built-in point reward system automatically incentivizes repeat players[span_9](start_span)[span_9](end_span).

---

## 3. Feature List
* **Landing & Navigation Page:** A high-end welcome view allowing users to jump directly into the live floor, player portal, or admin login[span_10](start_span)[span_10](end_span).
* **Live Table Management (12 Units):** Real-time countdown timers, occupancy badges, and dynamic status syncing across all connected devices using Firebase[span_11](start_span)[span_11](end_span).
* **User Authentication & Profiles:** Secure registration and login supporting passwords, user sessions, and persistent local tracking[span_12](start_span)[span_12](end_span).
* **Points & Rewards System:** Users earn points (awarded one-by-one by admins) and can redeem every 10 points for a free 1-hour play pass[span_13](start_span)[span_13](end_span). New accounts automatically receive a welcome free hour pass.
* **Individualized Support Chat (CRUD Support):** Private support channels where administrators can converse one-on-one with specific users, clear chat histories (Delete), and award points directly inside active support threads[span_14](start_span)[span_14](end_span).
* **Admin Time Configuration & Extension (CRUD Controls):** Administrators can set custom durations (Create/Update), choose preset intervals (30m, 1h, 2h), instantly terminate sessions (Delete), or extend ongoing game times (+15m, +30m, +1h)[span_15](start_span)[span_15](end_span).

---

## 4. Tech Stack Used
* **Frontend:** Vanilla HTML5, Tailwind CSS (via CDN for responsive modern styling), and modern JavaScript (ES6+ Modules)[span_16](start_span)[span_16](end_span).
* **Backend & Database:** Firebase Realtime Database (for real-time synchronization of tables, user profiles, and chat logs)[span_17](start_span)[span_17](end_span).
* **Deployment Platform:** Netlify (for instant static hosting and drag-and-drop updates)[span_18](start_span)[span_18](end_span).

---

## 5. Setup and Run Instructions (Tested from a clean machine)
Follow these steps to run the project locally or deploy it[span_19](start_span)[span_19](end_span):

1. **Clone or Download the Repository:**
   Download or clone this repository containing the `index.html` file into a local folder on your computer[span_20](start_span)[span_20](end_span).

2. **Open the Project:**
   Navigate into the folder and open `index.html` using any modern web browser (Google Chrome, Microsoft Edge, Safari, or Firefox)[span_21](start_span)[span_21](end_span). Alternatively, open the folder inside a code editor like Visual Studio Code and use the Live Server extension.

3. **Database Configuration:**
   The application is linked to a secure Firebase Realtime Database instance via the modular SDK script[span_22](start_span)[span_22](end_span). Ensure that your Firebase project has the Realtime Database enabled in Test Mode so that read/write operations execute smoothly.

4. **Production Deployment (Optional):**
   To host it live, go to Netlify Drop (app.netlify.com/drop) and drag-and-drop your project folder to generate a live public URL instantly[span_23](start_span)[span_23](end_span).

---

## 6. AI Tools Used & AI Disclosure
**AI Disclosure Statement:**
This project was developed using a human-in-the-loop collaborative workflow with generative artificial intelligence. The AI assistant acted as a technical collaborator, pair programmer, and architectural consultant under the direct supervision, testing, and direction of the human developer[span_24](start_span)[span_24](end_span).

* **Primary AI Tool:** Gemini (Google)[span_25](start_span)[span_25](end_span)
* **What it was used for:**
  * **Code Architecture & Generation:** Designing the single-page application structure, writing vanilla JavaScript ES6+ modules, and integrating the Firebase Realtime Database SDK (V10)[span_26](start_span)[span_26](end_span).
  * **UI/UX Design:** Structuring the minimalist black-and-white aesthetic using Tailwind CSS utility classes and building responsive layouts for up to 12 simultaneous billiard tables[span_27](start_span)[span_27](end_span).
  * **Debugging & Problem Solving:** Troubleshooting asynchronous Firebase event listeners, resolving state synchronization loops, and structuring database JSON nodes[span_28](start_span)[span_28](end_span).
* **Human Oversight:** All generated code structures, database schemas, and security choices were systematically reviewed, tested locally, deployed via Netlify, and verified by the developer to ensure functional correctness[span_29](start_span)[span_29](end_span).

---

## 7. Test Accounts with Sample Credentials

### System Administrator Account[span_30](start_span)[span_30](end_span)
* **Username:** `admin`[span_31](start_span)[span_31](end_span)
* **Password:** `admin`[span_32](start_span)[span_32](end_span)
* *Capabilities:* Unlocks table time configurations, extension tools, admin chat lists, and point-awarding features[span_33](start_span)[span_33](end_span).

### Regular Player Account (Sample)[span_34](start_span)[span_34](end_span)
* **Username:** `PLAYER1`[span_35](start_span)[span_35](end_span)
* **Password:** `password123`[span_36](start_span)[span_36](end_span)
* *Capabilities:* Allows testing of account registration, live table viewing, free-hour pass claims, point redemptions, and private support ticketing[span_37](start_span)[span_37](end_span). 
*(Note: You can also use the "Player Account Login" button to register any custom username and password on the fly to test new account creation).*[span_38](start_span)[span_38](end_span)
