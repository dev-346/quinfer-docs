# Running a Live Diagnostic Quiz

This feature turns your computer into a local server, allowing students to connect, take a quiz, and submit their responses in real-time.

## The Dashboard: Your Command Center
The Dashboard is the first page you'll see after setting up. It's your mission control for understanding what's happening in your classroom. It surfaces the most important information, helping you decide what to focus on. Here's what you'll find:

-   **Action Alerts:** The most urgent tasks that need your attention, like a diagnostic quiz that's ready to be analyzed or a class that requires an immediate reteaching session.
-   **Priority Learning Gaps:** Highlights the most critical, recurring misconceptions that the AI has identified across different classes and subjects.
-   **Tomorrow’s Focus:** A concise, AI-generated to-do list for your next lesson, based on the results of your latest diagnostic.
-   **Recent Assessments:** Quick access to the assessments you've created most recently.

## Creating a New Assessment
The core of TeachLens is its powerful AI-powered assessment generator. You can create two main types of assessments from the New Assessment page:

*   **Standard Assessment:** Perfect for generating homework, in-class worksheets, or practice tests.
*   **Class Diagnostic Quiz:** Designed to be run live in the classroom to identify student misconceptions in real-time.

**To create an assessment:**

1.  Navigate to **New Assessment** from the sidebar.
2.  Fill out the form with the details of your assessment. You can provide the content source by entering a **Topic** (e.g., "Linear Equations"), pasting in **Lesson Text**, or eventually, uploading a document.
3.  Configure the number and type of questions you want (e.g., 5 MCQs, 2 Short Answer).
4.  Click **"Generate Questions"**. The AI will create a new assessment based on your specifications.
5.  After generation, you are taken to the **Edit Assessment** screen where you can review and finalize the questions.

## Downloading PDFs for Printing
For any assessment you create, you can easily generate print-ready documents, which is ideal for standard assessments used as worksheets or homework.

1.  After creating or opening an assessment from the **Library** or **Diagnostics** page, you'll be on the **Edit Assessment** screen.
2.  Click the **Download PDFs** button.
3.  TeachLens will generate and save two PDF files to your computer:
    *   **Question Paper:** A clean document containing only the questions and options, perfect for display or as a reference.
    *   **Worksheet Version:** A document with dedicated answer spaces below each question, ideal for printing and distributing to students.
    
## The Library Page
The **Library** page (accessible from the sidebar) is the central archive for every assessment you've created, both standard and diagnostic. From here, you can:
- Browse and search all your past assessments.
- Open an assessment to view, edit, or download it again.
- Manage your assessments, including deleting old ones.

## A Note on Local Network Setup

For the live quiz features to work, all devices **must be connected to the same local Wi-Fi network**.

-   ✅ **Recommended Setup:** Connect the teacher's computer and all student devices to a single, stable Wi-Fi router (e.g., your school's Wi-Fi or a home router). This is the most reliable method.
-   📱 **Mobile Hotspot:** A mobile hotspot from a phone can also be used. However, some hotspots have a security feature that can prevent devices from connecting to each other. If you experience issues, this may be the cause. A portable travel router is often a great alternative in these situations.

## Teacher: Start and Share the Session
1.  **Create Quiz:** First, create an assessment, making sure to select **"Class Diagnostic Quiz"** as the type.
2.  **Go to Diagnostics:** From the sidebar, click on **Diagnostics**. This page lists all of your diagnostic quizzes.
3.  **Start Session:** Click on your newly created quiz. This takes you to the results page and automatically starts a "listening" session. **You must keep this page open to receive student responses.**
4.  **Share with Students:** Click the **Share** button. A dialog will appear with a **QR Code** and a **6-Character Quiz Code**.

## Student: Join and Take the Quiz
1.  **Connect to Wi-Fi:** Ensure the student device is on the same Wi-Fi network as the teacher.
2.  **Join the Session:**
    *   **Option A (Easiest):** Scan the QR code on the teacher's screen using the device camera.
    *   **Option B:** Open a browser, navigate to the app's join page (e.g., `http://<teacher-ip>:3000/quiz/join`), and enter the 6-character code. The teacher's IP address will be displayed in the Share dialog.
3.  **Enter Name & Take Quiz:** Enter your full name. The quiz will load automatically. The status indicator should change to **"Connected to Teacher"**.
4.  **Submit:** Click "Submit" to send the response directly to the teacher's device.
