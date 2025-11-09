# Analyzr.AI - An AI-Powered Resume Analyzer

Analyzr.AI is a comprehensive web application that provides AI-powered feedback and analysis for your resumes. It helps job seekers optimize their resumes for Applicant Tracking Systems (ATS) and improve their chances of landing interviews.

## 🚀 Features

### Core Functionality
- **AI-Powered Resume Analysis**: Get detailed feedback on your resume's content, structure, tone, and skills
- **ATS Score Calculation**: Understand how well your resume performs in Applicant Tracking Systems
- **Multi-Category Scoring**: Comprehensive evaluation across four key areas:
    - Tone & Style
    - Content Quality
    - Structure & Formatting
    - Skills Presentation
- **PDF Processing**: Upload PDF resumes and automatically convert them to images for display
- **Cloud Storage**: Secure storage using Puter.js cloud services

### User Experience
- **Responsive Design**: Works seamlessly across desktop and mobile devices
- **Interactive Dashboard**: View all your analyzed resumes in one place
- **Detailed Feedback**: Expandable accordion sections for each scoring category
- **Visual Scoring**: Color-coded badges and circular progress indicators
- **Job-Specific Analysis**: Analyze resumes against specific job descriptions

## 🛠 Technology Stack

- **Frontend**: React with TypeScript, React Router
- **Styling**: Tailwind CSS with custom components
- **Cloud Services**: Puter.js for authentication, storage, and AI capabilities
- **PDF Processing**: PDF.js for PDF to image conversion
- **Build Tool**: React Router Dev Server

## 📋 Usage

### Analyzing a Resume

1. **Navigate to Upload Page**
    - Click "Upload Resume" in the navbar
    - Or access `/upload` directly

2. **Provide Job Information**
    - Enter company name (optional)
    - Specify job title
    - Paste job description

3. **Upload Resume**
    - Drag and drop a PDF file or click to browse
    - Maximum file size: 20MB

4. **Review Analysis**
    - Wait for AI processing (typically 30-60 seconds)
    - View overall score and category breakdown
    - Read detailed suggestions for improvement

## 🎯 Scoring System

### Categories
- **Tone & Style**: Professional language assessment
- **Content**: Relevance and achievement quantification
- **Structure**: Organization and readability
- **Skills**: Technical and soft skills presentation
- **ATS**: Keyword optimization and format compatibility

### Score Ranges
- **70-100 (Green)**: Strong - Minimal improvements needed
- **50-69 (Yellow)**: Good Start - Some areas need work
- **0-49 (Red)**: Needs Work - Significant improvements required

## 🔧 Setup

```bash
# Clone and install
git clone <repository-url>
cd ai-powered-resume-analyzer
npm install

# Start development
npm run dev
```

Visit `http://localhost:5173` to start using the application.

## 📁 Project Structure

```
src/
├── components/     # UI components (Accordion, Score badges, etc.)
├── lib/           # Utilities (PDF conversion, cloud services)
└── routes/        # Pages (Upload, Analysis, Dashboard)
```

Built with ❤️ for job seekers everywhere. Improve your resume, land more interviews, and advance your career with Analyzr.AI.
