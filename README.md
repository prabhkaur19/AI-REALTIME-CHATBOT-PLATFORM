# AI-Powered IT Support Chatbot Platform

An automated, intelligent IT helpdesk solution built to streamline organizational support. The application leverages Natural Language Processing (NLP) to classify user intents, answer common FAQs, guide employees through step-by-step troubleshooting, and handle service ticket management seamlessly.

---

## 🚀 Key Features

*   **Intelligent Intent Classification:** Utilizes native NLP parsing to classify queries like greetings, password resets, ticket status lookups, and software bugs.
*   **Automated Knowledge Base:** Instantly answers static FAQs (such as company working hours or support contact info).
*   **Step-by-Step Troubleshooting:** Preloaded resolution workflows for common workplace problems (e.g., Network/Wi-Fi issues, VS Code crash faults).
*   **Robust Input Validation:** Fully integrated request validation using Zod/Schema layers across registration, login, chat streaming, ticket dispatch, and user feedback.
*   **Secure Authentication:** Built-in identity management powered by NextAuth.

---

## 🛠️ Tech Stack & Architecture

*   **Framework:** Next.js (utilizing server external packages configuration)
*   **Language:** TypeScript
*   **Database:** MongoDB Atlas (NoSQL backend store)
*   **Authentication:** NextAuth.js
*   **Natural Language Processing:** `node-nlp`
*   **Testing Suite:** Vitest
*   **Linting:** ESLint


## 📁 Environment Setup

Create a local `.env` file in the root directory of your project (similar to your `env.example` template) and populate it with the following variables:

```env
# MongoDB Atlas connection string
MONGODB_URI=mongodb+srv://username:password@cluster.mongodb.net/it-support-chatbot?retryWrites=true&w=majority

# NextAuth secret — generate with: openssl rand -base64 32
NEXTAUTH_SECRET=your-super-secret-key-change-in-production
NEXTAUTH_URL=http://localhost:3000

# Optional: confidence threshold for NLP (0-1)
NLP_CONFIDENCE_THRESHOLD=0.6
