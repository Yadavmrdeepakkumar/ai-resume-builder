# ResumeCraft

**ResumeCraft** is an AI-powered resume builder designed to help users create professional, customized resumes with ease. By leveraging AI, ResumeCraft ensures that each resume is tailored to highlight the user’s skills, experience, and achievements effectively.


## <a name="features">✨ Features </a>

- **AI-Powered Resume Generation:** Generate a professional resume using AI.

- **User Authentication:** Secure login and registration with Clerk.

- **Real-Time Preview:** See live updates as you fill out the resume form.

- **Easy Customization:** Edit sections like experience, education, skills, and more.

- **Save and Share:** Save your resume and share a link with potential employers.

- **Responsiveness:** Ensures the application adapts seamlessly to various screen sizes and devices.

## <a name="tech-stack">⚙️ Tech Stack</a>

- **Frontend:** Next.js 14.2.5

- **Authentication:** Clerk

- **AI Integration:** Gemini API

- **Styling:** TailwindCSS

- **Backend:** Node.js

- **Database:** MongoDB

## Getting Started

### Prerequisites

- **Node.js** (v22.0 or later) and **npm** (v6 or later) installed on your computer.

### Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/exclusiveabhi/ai-resume-builder.git
   ```

2. **Navigate to the Project Directory**

   ```bash
   cd ai-resume-builder
   ```

3. **Install Dependencies**

   ```bash
   npm install
   ```

4. **Configure Environment Variables**

   Create a `.env.local` file in the project root and add the values shown in
   `.env.local.example`. Set `MONGODB_URL` to your MongoDB connection string.
   Set `GEMINI_API_KEY` to a valid key created in
   [Google AI Studio](https://aistudio.google.com/app/apikey). An invalid or
   restricted key will prevent AI suggestions from working.
   For MongoDB Atlas, create a database user, allow your development machine's
   IP address in Network Access, and copy the application's connection string.
   Replace its username, password, and database name with your own values; do
   do not share or commit this string or your API key.

   ```env
   MONGODB_URL=mongodb+srv://<username>:<password>@<cluster>/<database>?retryWrites=true&w=majority
   GEMINI_API_KEY=<your-valid-gemini-api-key>
   ```

   Make sure `.env.local` contains a real, non-empty URI (not the angle-bracket
   placeholders) and a valid Gemini API key. Restart the development server
   after changing it.

5. **Start the application**

   ```bash
   npm run dev
   ```

   The app will be running on `http://localhost:3000`.

## Contributing

If you would like to contribute to **ResumeCraft**, please follow these steps:

1. **Fork the Repository**
2. **Create a New Branch**

   ```bash
   git checkout -b feature/YourFeatureName
   ```

3. **Make Your Changes**
4. **Commit Your Changes**

   ```bash
   git commit -am 'Add new feature'
   ```

5. **Push to the Branch**

   ```bash
   git push origin feature/YourFeatureName
   ```

6. **Create a Pull Request**

## Please give a star ⭐ to the repository if you like it.
 
