# 📘 TeachLens

TeachLens is a privacy-first, AI-powered diagnostic and teaching decision support system designed to help teachers clearly understand student learning and take the right instructional action — without relying on cloud storage or centralized student data.

TeachLens focuses on learning patterns, misconceptions, and instructional clarity, not just scores.

## 🌱 Built for Teachers

TeachLens acts like a teaching assistant that helps educators answer:

-   What are my students struggling with?
-   Why are these mistakes happening?
-   What should I teach next — practice, review, or reteach?

All analysis happens locally, keeping student data fully under the teacher’s control.

## 🔐 Privacy-First by Design

TeachLens is built with strict data privacy principles.

| ✅ What TeachLens DOES                                    | ❌ What TeachLens DOES NOT do          |
| :-------------------------------------------------------- | :------------------------------------- |
| Stores all data locally on the teacher’s device           | No cloud database                      |
| Conducts quizzes over the local network (LAN)             | No student data uploaded to servers    |
| Uses teacher-provided AI API keys only for processing     | No central backend storage             |
| Keeps full ownership of student data with the teacher     | No tracking or analytics collection    |

**Your classroom data never leaves your system.**

This makes TeachLens suitable for:
- Schools
- Coaching institutes
- Tuition centers
- Privacy-sensitive classrooms

## 🧠 What TeachLens Does

TeachLens goes beyond grading. It analyzes:
-   Student answer patterns
-   Common incorrect choices
-   Error mechanisms
-   Conceptual vs procedural mistakes

Then translates this into clear teaching decisions.

### 🎯 Teaching Decision Support

Each diagnostic ends with one of the following statuses:

| Status                | Meaning                                       |
| :-------------------- | :-------------------------------------------- |
| 🟢 Move On            | Strong understanding; proceed                 |
| 🟡 Practice Required  | Minor errors; accuracy improvement needed   |
| 🟠 Review Suggested   | Understanding uneven; clarify key ideas       |
| 🔴 Reteach Required   | Foundational misconception detected           |

Teachers are told what to do next, not just what went wrong.

### 📊 Diagnostic Insights

TeachLens automatically generates:
-   Primary learning concern
-   Secondary supporting weaknesses
-   Instructional focus (concept rebuild / guided practice / enrichment)
-   Teaching move suggestions
-   Student grouping for small-group instruction

### 👥 Student Grouping

Students are automatically grouped into:
-   **Concept Rebuild** — needs foundational reteaching
-   **Guided Practice** — understands concept but needs accuracy
-   **Enrichment** — ready for challenge

This supports differentiated instruction without manual analysis.

### 📝 AI-Powered Assessment Creation

Teachers can generate questions using:
-   Topic names
-   Lesson text
-   Keywords or instructions

Supports:
-   MCQs
-   Word problems
-   Conceptual reasoning
-   Multi-step questions
-   Adjustable difficulty levels

Teachers must provide their own AI API key, ensuring transparency and cost control.

## How to Use the App

### Step 1: Network Setup (Crucial for In-Class Use)

For the local network features to work, all devices **must be connected to the same standard Wi-Fi network**.

-   ✅ **Ideal Setup:** Connect the teacher's laptop and all student devices to a single, stable Wi-Fi router (e.g., your school's Wi-Fi, a home router, or a portable travel router). This is the recommended method for reliable performance.
-   ❌ **Unreliable Setup:** Using a **mobile hotspot** is **not recommended**. Most mobile hotspots isolate connected devices from each other for security, which will prevent student devices from finding and connecting to the teacher's session. If you must use a hotspot, ensure that "AP Isolation" or "Client Isolation" is turned off in its settings.

### Step 2: Teacher - Create and Share a Diagnostic Quiz

1.  **Create Assessment:** Navigate to **New Assessment** and fill out the form. Make sure to select **"Class Diagnostic Quiz"** as the type.
2.  **Finalize & Start Session:** After generating, you'll be on the edit page. Navigate to the **Diagnostics** page and click on your newly created quiz. This automatically takes you to the results page and starts a "listening" session for students. **Keep this page open to receive responses.**
3.  **Share the Session:** Click the **Share** button. A dialog will appear with a **QR Code** and a **6-Character Quiz Code**.

### Step 3: Student - Join and Take the Quiz

1.  **Connect to Wi-Fi:** The student ensures their device is on the same Wi-Fi network as the teacher.
2.  **Join the Session:**
    *   **Option A (Easiest):** Scan the QR code on the teacher's screen.
    *   **Option B:** Open a browser, navigate to the app's join page (e.g., `http://<teacher-ip>:3000/quiz/join`), and enter the 6-character code.
3.  **Enter Name & Take Quiz:** The student enters their full name. The quiz will load automatically. The status indicator at the top should change from "Connecting..." to **"Connected to Teacher"**.
4.  **Submit:** The student clicks "Submit". The response is sent directly to the teacher's device.

### Step 4: Teacher - View Live Results & Analyze

1.  **Receive Responses:** As students submit, their responses will arrive on your device in real-time.
2.  **Analyze Results:** On the diagnostic results page, click the **"Analyze Results"** button. The page will update with a full breakdown of class performance, common misconceptions, and AI-powered teaching recommendations.
3.  **Generate Follow-ups:** Use the "Action Center" to generate a reteaching plan or an adaptive follow-up quiz based on the analysis.

### Offline Submission with QR Codes (`Collect Responses` page)

In cases where a real-time connection isn't possible, TeachLens provides a robust offline option:

1.  **Student Finishes Quiz:** If a student cannot connect to the teacher's session, after they finish the quiz, a QR code will be displayed on their screen. This QR code contains their complete, encrypted response.
2.  **Teacher Scans Code:** The teacher navigates to the **"Collect Responses"** page in the app. Using the device's camera, they can scan the QR code directly from the student's screen.
3.  **Instant Import:** The student's response is instantly and securely imported into the diagnostic results, ready for analysis.

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

## 🔒 Security & Trust

-   No student accounts
-   No personal data collection
-   No external storage
-   No vendor lock-in
-   Fully teacher-controlled system

TeachLens respects classrooms as private learning spaces.

## 📫 Support

📧 devangwangde@gmail.com
