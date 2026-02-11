# sahalat-campus-navigation
# Sahalat | Campus Mobility & Parking Solution 🚗

**Sahalat** is a User-Centered Interaction (UCI) project designed to solve the chronic parking congestion at King Saud University (KSU). By combining real-time parking reservations with shuttle bus tracking, the application aims to reduce student tardiness and campus traffic.

**Tools:** Figma, Google Forms, Data Analysis

## 🚩 The Problem
[cite_start]Our initial research [cite: 920, 1012] surveying 138+ KSU students revealed critical logistics issues:
* [cite_start]**52%** of students spend more than **10 minutes** just searching for a spot[cite: 1017].
* [cite_start]**90%** of students reported arriving late to class specifically due to parking issues[cite: 1059].
* [cite_start]**88%** of CCIS students reported frustration with the lack of designated parking data[cite: 1086].

## 💡 The Solution
Sahalat provides a dual-solution approach to campus mobility:

### 1. Smart Parking Reservation
* [cite_start]**Real-Time Availability:** Visual grid showing Green (Available) vs. Red (Occupied) slots[cite: 1319].
* [cite_start]**Hold Timer:** A 10-minute countdown timer locks the spot for the user while they drive to the location[cite: 1331].
* [cite_start]**Navigation:** Direct integration with map services to guide the user to the specific slot (e.g., Slot A4-8)[cite: 1351].

### 2. Shuttle Bus Tracker
* [cite_start]**Live Schedule:** Detailed departure and arrival times for campus shuttles[cite: 1412].
* [cite_start]**Stop Locator:** Interactive map showing all bus stops relative to the user's location[cite: 1365].

## 🎨 Design Process (HCI Lifecycle)

### Phase 1: User Research
We conducted a demographic and behavioral survey to define our personas.
* [cite_start]**Key Insight:** 83% of students end up parking much farther from their college than preferred[cite: 1048].

### Phase 2: Task Analysis
We broke down the user journey into 6 core tasks, including:
1.  **Login:** University credential authentication.
2.  **Reserve:** Filtering by college $\to$ Selecting slot $\to$ Confirming.
3.  [cite_start]**Accessibility:** Configuring color blindness modes (Protanopia/Deuteranopia) and Text-to-Speech[cite: 1475].

### Phase 3: Usability Testing & Iteration
We tested the high-fidelity prototype with 10 participants and tracked quantitative metrics.
* [cite_start]**Success Rate:** Achieved an **83.33%** task completion rate[cite: 1550].
* [cite_start]**Ease of Use:** Rated **4.6/5** by participants[cite: 1577].

#### 🔄 Design Evolution (Based on Testing)
Our testing revealed specific usability flaws which we fixed in the final iteration:
1.  [cite_start]**The Logout Error:** 50% of users tried to logout via "Settings" instead of "Profile"[cite: 1615].
    * [cite_start]*Fix:* Added a redundant Logout button in the Settings menu to match user mental models[cite: 1615].
2.  [cite_start]**Map Interaction:** 30% of users tried to zoom in on the Bus Map, which was static[cite: 1609].
    * [cite_start]*Fix:* Enabled pinch-to-zoom gestures on all map interfaces[cite: 1610].
3.  **Login Friction:** Users frequently entered personal emails instead of KSU emails.
    * [cite_start]*Fix:* Added bold red warning text and visual cues for "University Credentials"[cite: 1587].

## 📱 Screenshots
*(Place your exported Figma screens here in an /assets folder)*
![Parking Reservation Flow](./assets/parking_flow.png)
![Bus Schedule Map](./assets/bus_map.png)

## 👥 The Team
* **Abdullah Bamukhayyar**
* Abdulmalik Alsaleh
* Haidar Alhassan
