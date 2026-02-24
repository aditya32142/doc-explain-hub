# ⚖️ LegalSimplify

LegalSimplify is a web application that helps users understand legal documents in simpler, more readable language.  
The project focuses on frontend structure, user experience, and integrating AI-powered services to make complex legal text easier to explore and interpret.

---

## 🌐 Live Demo
👉 View LegalSimplify in action
  https://legalsimplify.netlify.app/
---

## ✨ Key Features

- Upload legal PDFs or scanned documents (e.g., contracts, agreements)
- Generate plain-English summaries of legal content
- Highlight important or potentially risky sections in documents
- Ask questions about the document through a simple Q&A interface
- Responsive, browser-based UI accessible across devices

---

## 🛠️ Tech Stack

### Frontend
- React (Vite)
- TypeScript
- Tailwind CSS

### AI / Cloud Integration
- AI-based document processing APIs for text extraction and summarization
- Semantic search concepts used for document-based Q&A

### Deployment
- Netlify

---

## 📁 Project Structure

The project follows a component-driven structure:

- `src/` contains the core application logic
- Reusable UI components are organized separately for clarity
- Configuration and constants are centralized to keep the codebase maintainable

This structure helps keep the application scalable and easier to reason about as features grow.

---

## 🎯 Learning Focus

This project was built as a learning-oriented application with emphasis on:

- Structuring a frontend application using React and TypeScript
- Designing clean and readable UI flows for complex content
- Integrating external AI services into a web interface
- Handling loading states and improving overall user experience
- Understanding trade-offs when working with third-party APIs

---

## ⚠️ Limitations

- The accuracy of summaries depends on the quality and clarity of uploaded documents
- The application is not intended to provide legal advice
- Advanced legal validation and compliance checks are out of scope

---

## 🚀 Getting Started Locally

```bash
git clone https://github.com/aditya32142/doc-explain-hub.git
cd doc-explain-hub
npm install
npm run dev
