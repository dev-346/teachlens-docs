# 🚀 Running a Live Diagnostic Quiz

The Class Diagnostic Quiz turns the teacher’s computer into a local server, enabling students to join a live quiz session, submit responses in real time, and allowing instant diagnostic analysis.

### ⚠️ Prerequisites: Local Network Setup

**Critical Requirement**

The teacher’s computer and all student devices must be connected to the same local Wi-Fi network or mobile hotspot.

A standard school or home Wi-Fi router is recommended.

Internet access is not required once all devices are on the same local network.

---

# 👨‍🏫 Teacher Guide: Starting a Live Quiz

### **1️⃣ Create a Diagnostic Quiz**

-   Navigate to **New Assessment**
-   Fill out the assessment form
-   Select **Class Diagnostic Quiz** as the Assessment Type
-   Add questions
    -   *Only Multiple Choice Questions (MCQs) are supported*
-   Click **Generate Questions**
-   Review and edit questions on the Edit Assessment screen

### **2️⃣ Start the Listening Session**

You can start the live quiz session in two ways:

-   **Option A: Start Immediately**
    -   Click **Start & Share Session** after editing the quiz
    -   You will be redirected to the Diagnostic Results Page
-   **Option B: Start from Diagnostics**
    -   Navigate to **Diagnostics**
    -   Locate your quiz in the list
    -   Click the quiz to open it

📌 **In both cases:**

-   The Diagnostic Results Page opens
-   A local listening session starts automatically

**Important Notes**

-   The Results Page must be opened at least once to start the session
-   Do not close the application while the quiz is active
-   You may minimize the app or use other features
-   The session automatically ends once all student responses are received

### **3️⃣ Share the Quiz with Students**

-   On the Diagnostic Results Page, click **Share Quiz Link**
-   Students can join using:
    -   **QR Code (Recommended)** – scan using device camera
    -   **Join Link & Quiz Code**
        -   Example: `http://<teacher-ip>:3000/quiz/join`
        -   Includes a 6-character quiz code

---

# 👩‍🎓 Student Guide: Joining the Quiz

### **1️⃣ Connect to the Same Network**

-   Ensure the student device is connected to the same Wi-Fi or hotspot as the teacher

### **2️⃣ Join the Session**

-   **Option A:** Scan the QR code displayed by the teacher
-   **Option B:**
    -   Open a web browser
    -   Visit the join link
    -   Enter the 6-character quiz code

### **3️⃣ Enter Details & Take Quiz**

-   Enter full name (first and last name)
-   Quiz loads automatically
-   Status indicator shows **Connected to Teacher**

### **4️⃣ Submit Responses**

-   Click **Submit** after answering all questions
-   Responses are sent instantly to the teacher’s device

---

## 🌐 Offline Submission (QR-Based Recovery)

Students can submit answers even if they lose network connectivity.

-   **Student**
    -   Complete the quiz and click **Submit**
    -   A QR code appears containing encrypted responses
-   **Teacher**
    -   On the Diagnostic Results Page, click **Scan QR Responses**
    -   Scan the student’s QR code using the device camera
-   **Result**
    -   Responses are securely and instantly imported into the diagnostic results
