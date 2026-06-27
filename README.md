# AI-Powered IT Support Chatbot Platform

An automated, intelligent IT helpdesk solution built to streamline organizational support. The application leverages Natural Language Processing (NLP) to classify user intents[cite: 4], answer common FAQs, guide employees through step-by-step troubleshooting, and handle service ticket management seamlessly.

---

## 🚀 Key Features

*   **Intelligent Intent Classification:** Utilizes native NLP parsing to classify queries like greetings, password resets, ticket status lookups, and software bugs[cite: 4].
*   **Automated Knowledge Base:** Instantly answers static FAQs (such as company working hours or support contact info)[cite: 3, 4].
*   **Step-by-Step Troubleshooting:** Preloaded resolution workflows for common workplace problems (e.g., Network/Wi-Fi issues, VS Code crash faults)[cite: 3].
*   **Robust Input Validation:** Fully integrated request validation using Zod/Schema layers across registration, login, chat streaming, ticket dispatch, and user feedback.
*   **Secure Authentication:** Built-in identity management powered by NextAuth.

---

## 🛠️ Tech Stack & Architecture

*   **Framework:** Next.js (utilizing server external packages configuration)[cite: 11]
*   **Language:** TypeScript[cite: 10, 12]
*   **Database:** MongoDB Atlas (NoSQL backend store)[cite: 6]
*   **Authentication:** NextAuth.js[cite: 6]
*   **Natural Language Processing:** `node-nlp`[cite: 11]
*   **Testing Suite:** Vitest[cite: 3, 4, 5]
*   **Linting:** ESLint[cite: 10]
