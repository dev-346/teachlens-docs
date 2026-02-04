# 🚀 Running a Live Diagnostic Quiz

A "Class Diagnostic Quiz" is a powerful feature that turns your computer into a local server, allowing students to join a live session, take a quiz, and submit their responses in real-time for instant analysis.

## ❗️ Critical: Local Network Setup

For the live quiz feature to work, the teacher's computer and all student devices **must be connected to the same local Wi-Fi network or mobile hotspot**. A standard school or home Wi-Fi router is the most reliable setup.

---

## 👨‍🏫 Part 1: Teacher Steps (Start the Session)

### Step 1: Create the Diagnostic Quiz
- Navigate to **New Assessment**.
- Fill out the form, making sure to select **"Diagnostic Quiz"** as the Assessment Type.
- Configure your questions (Diagnostic Quizzes only support Multiple Choice questions) and click **"Generate Questions"**.
- Review the questions on the "Edit Assessment" screen.

### Step 2: Start the Listening Session
- You can start a session in two ways:
    - After creating/editing a quiz, click the **"Start & Share Session"** button.
    - From the sidebar, go to **Diagnostics**, find your quiz, and click its action button (e.g., "View Progress").
- This takes you to the results page and automatically starts a "listening" session.
- **Important:** You must keep this page open to receive live student responses. The session ends automatically when all expected responses are in.

### Step 3: Share with Students
- On the diagnostic results page, click the **Share Quiz Link** button.
- A dialog will appear with two ways for students to join:
    1.  **📱 QR Code:** The easiest method. Students can scan this with their device's camera.
    2.  **🔗 Join Link & Quiz Code:** A URL and a 6-character code are provided for students who cannot scan the QR code.

---

## 👩‍🎓 Part 2: Student Steps (Join the Quiz)

### Step 1: Connect to the Correct Wi-Fi
- Ensure the student device is on the same Wi-Fi network as the teacher.

### Step 2: Join the Session
- **Option A (Easiest):** Scan the QR code displayed on the teacher's screen.
- **Option B (Manual):** Open a web browser, navigate to the join link (e.g., `http://<teacher-ip>:3000/quiz/join`), and enter the 6-character quiz code.

### Step 3: Enter Name & Take Quiz
- The student will be prompted to enter their full name.
- After entering their name, the quiz will load automatically. The status indicator should show **"Connected to Teacher"**.

### Step 4: Submit Responses
- After answering all questions, the student must click the **"Submit"** button to send their responses to the teacher's computer.

---

## 🌐 Offline Submission with QR Codes

If a student loses their connection, they can still submit their answers.
1.  **Student Finishes Quiz:** After the student clicks "Submit" without a connection, a unique QR code will appear on their screen. This code contains their encrypted response.
2.  **Teacher Scans Code:** On the diagnostic results page, the teacher clicks the **"Collect via QR"** button. Using the device's camera, they can scan the QR code directly from the student's screen.
3.  **Instant Import:** The student's response is instantly and securely imported into the diagnostic results.
