# **App Name**: AssessAI

## Core Features:

- Assessment Generation: Generate various types of assessment questions (MCQ, short answer, extended response, true/false, fill in the blanks) based on topic name, lesson text, notes, or curriculum keywords, using an LLM accessed via Cloud Functions with API key securely stored in settings.
- Curriculum Alignment: Tag assessments and questions with US-specific curriculum standards (CCSS, NGSS, SAT/ACT, AP) and subjects (ELA, Math, Science, Social Studies).
- Multiple Versions: Tool to Generate multiple versions (A/B) of assessments to reduce cheating, by using the LLM tool to vary the wording of each question
- Export Options: Export assessments in printable PDF format (question paper and answer key with scoring rubric) and as a Google Form (with a Cloud Function stub for the Google Form API).
- Question Bank: Store generated questions in a searchable question bank, filterable by subject, grade, type, and difficulty, for reuse in new assessments. Uses Firestore.
- Settings Page: Configure LLM provider (OpenAI, Gemini, Claude) and API key, model name, school branding (name, logo) and other credentials necessary to run the assessment such as external API connections.
- Assessment Result Storage: Assessment definitions and LLM-generated question results will be stored in the Firestore database.

## Style Guidelines:

- Primary color: A deep teal (#008080), reminiscent of the focus and discipline found in academic settings.
- Background color: A very light gray (#F0F0F0) background for optimal readability.
- Accent color: A muted gold (#B8860B) to highlight important elements such as buttons and key information.
- Headline font: 'Space Grotesk', sans-serif, for a techy, scientific, modern feel, best suited to headlines and titles.
- Body font: 'Inter', sans-serif, providing a modern, neutral look that ensures readability across various devices.
- Code font: 'Source Code Pro' for any code snippets.
- Use simple, clear icons to represent different question types, export formats, and settings options.
- Employ a clean, card-based layout to present assessment information, questions, and settings in an organized manner.
- Incorporate subtle animations for actions such as generating questions, saving, and exporting, to provide visual feedback.