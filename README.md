# 📘 TeachLens

TeachLens is a smart classroom decision-support app designed for teachers.
It helps teachers quickly create assessments, run diagnostic quizzes, and understand exactly where students are struggling — without complex analytics or manual analysis.

TeachLens acts like a teaching assistant: it analyzes student responses, detects learning gaps, highlights misconceptions, and recommends clear next steps such as practice, review, or reteaching. All data is stored locally, quizzes can run over a local network, and student privacy is fully maintained — no cloud dependency required.

In short, TeachLens helps teachers see their class clearly and teach with confidence.

TeachLens focuses on learning patterns, misconceptions, and instructional clarity, not just scores.

## 🌱 Built for Teachers

TeachLens acts like a teaching assistant that helps educators answer:

-   What are my students struggling with?
-   Why are these mistakes happening?
-   What should I teach next — practice, review, or reteach?

All analysis happens locally, keeping student data fully under the teacher’s control.

## 🔐 Privacy-First by Design

TeachLens is built with a core commitment to data privacy. All student data, assessments, and results are stored exclusively on the teacher's local device—no cloud databases, no central servers, and no student accounts required. Quizzes are conducted over your local Wi-Fi network, so no student information is ever uploaded to the internet. Because you provide your own AI API key and all data stays on your computer, you retain full ownership and control over your classroom data, making TeachLens a secure choice for any educational setting.

## 🚀 Getting Started: Initial Setup

This one-time setup will get you up and running with TeachLens.

### Step 1: Activate Your License

The first time you open TeachLens, you will be prompted to enter your license key.

1.  **Find Your Key:** Your license key was sent to the email address you used during purchase. It's a long string of characters.
2.  **Enter the Key:** Copy the entire key and paste it into the activation field.
3.  **Activate:** Click the "Activate" button.

Once activated, your license is locked to your device and cannot be used on another computer.

### Step 2: Get Your Google AI API Key

TeachLens uses Google's powerful Gemini models to generate high-quality assessment content. To use this feature, you need an API key from Google AI Studio. Your key is stored securely and locally on your device.

1.  **Visit Google AI Studio:** Open your web browser and go to [https://aistudio.google.com/app/apikey](https://aistudio.google.com/app/apikey).
2.  **Sign In:** Sign in with your Google account.
3.  **Create API Key:** Click on **"Create API key"**. You can create a key in a new or existing Google Cloud project. Follow the on-screen instructions.
4.  **Copy Your Key:** A new API key will be generated. It's a long string of random characters. Click the copy icon next to it.

> **Free vs. Paid Usage:** Google provides a generous **free tier** for the Gemini API which is sufficient for most teachers' day-to-day needs. If you are a heavy user and generate a very large number of assessments, you may need to enable billing on your Google Cloud project to move to a pay-as-you-go plan.

> **Important:** Treat your API key like a password. Do not share it publicly.

### Step 3: Configure TeachLens Settings

Now, let's add your new API key to TeachLens.

1.  **Navigate to Settings:** In the TeachLens app, click on the **Settings** icon in the left-hand sidebar.
2.  **Paste Your Key:** In the "Gemini API Key" field, paste the key you copied from Google AI Studio.
3.  **Select a Model (Optional):**
    *   **Gemini 1.5 Flash:** Recommended for most users. It's fast and provides a great balance of quality and cost.
    *   **Gemini 1.5 Pro:** More powerful for complex topics, but slightly slower.
4.  **Save Settings:** Click the **"Save All Settings"** button.

You are now ready to start creating assessments!


## How to Use the App

### The Dashboard: Your Command Center

The **Dashboard** is the first page you'll see after setting up. It's your mission control for understanding what's happening in your classroom. It surfaces the most important information, helping you decide what to focus on. Here's what you'll find:

-   **Action Alerts:** The most urgent tasks that need your attention, like a diagnostic quiz that's ready to be analyzed or a class that requires an immediate reteaching session.
-   **Priority Learning Gaps:** Highlights the most critical, recurring misconceptions that the AI has identified across different classes and subjects.
-   **Tomorrow’s Focus:** A concise, AI-generated to-do list for your next lesson, based on the results of your latest diagnostic.
-   **Recent Assessments:** Quick access to the assessments you've created most recently.

### Creating a New Assessment

The core of TeachLens is its powerful AI-powered assessment generator. You can create two main types of assessments from the **New Assessment** page:

*   **Standard Assessment:** Perfect for generating homework, in-class worksheets, or practice tests.
*   **Class Diagnostic Quiz:** Designed to be run live in the classroom to identify student misconceptions in real-time.

**To create an assessment:**

1.  Navigate to **New Assessment** from the sidebar.
2.  Fill out the form with the details of your assessment. You can provide the content source by entering a **Topic** (e.g., "Linear Equations"), pasting in **Lesson Text**, or eventually, uploading a document.
3.  Configure the number and type of questions you want (e.g., 5 MCQs, 2 Short Answer).
4.  Click **"Generate Questions"**. The AI will create a new assessment based on your specifications.
5.  After generation, you are taken to the **Edit Assessment** screen where you can review and finalize the questions.

### Downloading PDFs for Printing

For any assessment you create, you can easily generate print-ready documents, which is ideal for standard assessments used as worksheets or homework.

1.  After creating or opening an assessment from the **Library** or **Diagnostics** page, you'll be on the **Edit Assessment** screen.
2.  Click the **Download PDFs** button.
3.  TeachLens will generate and save two PDF files to your computer:
    *   **Question Paper:** A clean document containing only the questions and options, perfect for display or as a reference.
    *   **Worksheet Version:** A document with dedicated answer spaces below each question, ideal for printing and distributing to students.
    
### The Library Page

The **Library** page (accessible from the sidebar) is the central archive for every assessment you've created, both standard and diagnostic. From here, you can:
- Browse and search all your past assessments.
- Open an assessment to view, edit, or download it again.
- Manage your assessments, including deleting old ones.

### Running a Live Diagnostic Quiz

This feature turns your computer into a local server, allowing students to connect, take a quiz, and submit their responses in real-time.

#### A Note on Local Network Setup

For the live quiz features to work, all devices **must be connected to the same local Wi-Fi network**.

-   ✅ **Recommended Setup:** Connect the teacher's computer and all student devices to a single, stable Wi-Fi router (e.g., your school's Wi-Fi or a home router). This is the most reliable method.
-   📱 **Mobile Hotspot:** A mobile hotspot from a phone can also be used. However, some hotspots have a security feature that can prevent devices from connecting to each other. If you experience issues, this may be the cause. A portable travel router is often a great alternative in these situations.

#### Teacher: Start and Share the Session

1.  **Create Quiz:** First, create an assessment, making sure to select **"Class Diagnostic Quiz"** as the type.
2.  **Go to Diagnostics:** From the sidebar, click on **Diagnostics**. This page lists all of your diagnostic quizzes.
3.  **Start Session:** Click on your newly created quiz. This takes you to the results page and automatically starts a "listening" session. **You must keep this page open to receive student responses.**
4.  **Share with Students:** Click the **Share** button. A dialog will appear with a **QR Code** and a **6-Character Quiz Code**.

#### Student: Join and Take the Quiz

1.  **Connect to Wi-Fi:** Ensure the student device is on the same Wi-Fi network as the teacher.
2.  **Join the Session:**
    *   **Option A (Easiest):** Scan the QR code on the teacher's screen using the device camera.
    *   **Option B:** Open a browser, navigate to the app's join page (e.g., `http://<teacher-ip>:3000/quiz/join`), and enter the 6-character code. The teacher's IP address will be displayed in the Share dialog.
3.  **Enter Name & Take Quiz:** Enter your full name. The quiz will load automatically. The status indicator should change to **"Connected to Teacher"**.
4.  **Submit:** Click "Submit" to send the response directly to the teacher's device.

#### Teacher: View Live Results & Analyze

1.  **Receive Responses:** As students submit, their responses will appear on your results page in real-time. The dashboard will show you how many students have responded.
2.  **Analyze Results:** Once you have enough responses, click the **"Analyze Results"** button. The AI will perform a deep analysis of the answers. The page will update with a full breakdown, including:
    *   **Teaching Decision Status:** A clear, color-coded recommendation on what to do next (e.g., 🔴 Reteach Required, 🟡 Practice Required, 🟢 Move On).
    *   **Primary Learning Concern:** A plain-language explanation of the biggest conceptual misunderstanding in the class.
    *   **Question-by-Question Insights:** A breakdown of each question, showing common wrong answers and an AI-powered insight into *why* students made those errors.
    *   **Student Grouping:** Students are automatically clustered into groups like "Concept Rebuild" or "Guided Practice," allowing for easy differentiated instruction.
3.  **Generate Follow-ups:** Use the "Action Center" on the results page to generate a customized **Reteaching Plan** or an **Adaptive Follow-up Quiz** that targets the identified weak areas.

### Offline Submission with QR Codes (`Collect Responses` page)

In cases where a real-time Wi-Fi connection isn't possible or a student's device disconnects, TeachLens provides a robust offline submission option.

1.  **Student Finishes Quiz:** If a student cannot connect to the teacher's session (or loses connection), after they finish the quiz, a unique QR code will be displayed on their screen. This QR code contains their complete, encrypted response.
2.  **Teacher Scans Code:** The teacher navigates to the **"Collect Responses"** page in the app. Using the device's camera, they can scan the QR code directly from the student's screen.
3.  **Instant Import:** The student's response is instantly and securely imported into the diagnostic results, ready for analysis alongside the live responses.

## 🧭 Philosophy Behind TeachLens

TeachLens is not an LMS.
It is not a grading tool.

It is a **teaching awareness system**.

> “Marks tell you who is weak.
> TeachLens tells you why — and what to do next.”

## 👩‍🏫 Who TeachLens Is For

-   School teachers
-   Private tutors
-   Coaching institutes
-   Educators seeking data-informed teaching
-   Teachers who want clarity, not complexity

## 📫 Support

📧 devangwangde@gmail.com
