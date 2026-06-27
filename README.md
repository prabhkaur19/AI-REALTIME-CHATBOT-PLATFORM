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
