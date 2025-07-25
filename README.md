# NextAria: AI-Powered Musical Theatre Song Recommender

[![Flutter](https://img.shields.io/badge/Developed%20with-Flutter-02569B?logo=flutter)](https://flutter.dev/)
[![Dart](https://img.shields.io/badge/Language-Dart-0175C2?logo=dart)](https://dart.dev/)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

## 🎭 Discover Your Next Broadway Aria 🎶

NextAria is a mobile application designed to revolutionise how musical theatre singers discover new material. Leveraging the power of Generative AI and robust local-first persistence, it provides personalised song recommendations, helps users track their repertoire, and offers tailored practice advice, all within a beautiful and intuitive interface.

<!-- Optional: You could embed screenshots or a short demo video here to visually showcase the app immediately. -->
<!-- Example: -->
<!-- ![NextAria App Screenshot](path/to/your/screenshot.png) -->
<!-- Or: -->
<!-- [![Watch the demo video](https://img.youtube.com/vi/YOUR_VIDEO_ID/hqdefault.jpg)](https://www.youtube.com/watch?v=YOUR_VIDEO_ID) -->

---

### **✨ The Problem**

Finding the *perfect* musical theatre song can be a daunting task for singers of all levels. Common challenges include:
*   **Overwhelm:** Navigating a vast library of songs to find what truly fits.
*   **Relevance:** Identifying material appropriate for one's specific vocal range, type, and experience.
*   **Guidance:** Obtaining actionable advice on how to approach new pieces vocally.
*   **Tracking:** Efficiently managing a growing repertoire of learned or aspiring songs.

---

### **🚀 The NextAria Solution**

NextAria addresses these challenges with intelligent, personalised solutions:

1.  **AI-Powered Personalisation:** At its core, NextAria utilises a **Large Language Model (LLM)** to generate unique song recommendations tailored to the individual user dynamically. This moves beyond static databases, providing truly novel and relevant suggestions.
2.  **Adaptive Vocal Profiling:** The app caters to both seasoned vocalists who know their precise voice type (e.g., Soprano, Tenor) and beginners who are "just starting." For the latter, a user-friendly guided process allows them to express preferences like desired song gender (male, female, or any sung songs on Broadway) and general singing experience, ensuring relevant recommendations without requiring technical jargon.
3.  **Comprehensive Recommendation Details:** Each suggested song comes with rich metadata including its musical, the character who sings it, suitable voice types, a clear, descriptive difficulty level (e.g., "Very Easy," "Medium," "Very Hard"), a brief synopsis, *and* valuable, AI-generated practice notes.
4.  **Local-First & Offline Ready:** All user data and fetched recommendations are intelligently cached and managed on the device using a robust local database (Drift/SQLite). This ensures a fluid, responsive user experience, even without an internet connection.
5.  **Repertoire Management:** Users can easily mark songs as "learned" or "unlearned," keeping their repertoire organised and allowing the AI to refine future suggestions.
6.  **Intuitive User Experience:** The app features a clean, modern UI with clear navigation, integrated loading states, and skeleton loaders for seamless interaction.
7.  **Profile Evolution:** Users can easily update their vocal preferences and experience level at any time, allowing recommendations to adapt as their skills grow.

---

### **🛠️ Underlying Technology & Architecture Highlights**

NextAria is built with a focus on performance, scalability, and maintainability:

*   **Frontend Framework:** **Flutter** - Chosen for its ability to build beautiful, natively compiled applications for mobile from a single codebase.
*   **Language:** **Dart** - For robust, high-performance application logic.
*   **AI/LLM Integration:** Utilizes **Firebase AI SDK** to connect with **Google's Generative AI models (Gemini Flash)**. This is the engine behind the personalised recommendations and practice advice.
*   **Local Data Persistence:** **Drift (powered by SQLite)** - A reactive, type-safe, and highly performant local database solution, replacing `shared_preferences` for structured data storage. This enables the "local-first" data strategy.
*   **State Management:** **Riverpod** - For robust, testable, and maintainable application state.
*   **Routing:** **AutoRoute** - A declarative routing solution for clear and predictable navigation within the app.
*   **Localisation:** Built-in **Flutter `intl`** package - Ensures the app's content, including vocal qualities and difficulty levels, is available in multiple languages.
*   **Unique Identifiers:** Employs the `uuid` package for generating globally unique IDs for all database entries, ensuring data integrity and simplifying potential future synchronisation.

---

### **🛣️ Future Vision**

NextAria is an evolving platform. Key features planned for future iterations include:

*   **Expanded Recommendation Controls:** More advanced filtering and sorting options for a highly customised discovery experience.
*   **Integrated Vocal Warmups:** A curated library of vocal warm-ups, playable directly within the app (e.g., via YouTube embedding), tailored to the user's vocal needs.
*   **Enhanced User Engagement:** Features like explicit user feedback on recommendations ("like/dislike") to further fine-tune the AI.
*   **External Resource Integration:** Direct links to popular music platforms (Spotify, YouTube, sheet music sites) to seamlessly access recommended songs.
*   **Personal Practice Journal:** Empowering users to add private notes and track their progress on individual songs.
*   **Curated Collections:** Expert-selected song lists for auditions, specific musical styles, or common singing challenges.

---

### **📸 Visual Showcase**

<!-- Replace these placeholders with actual links or embedded content -->
*   [Screenshot 1: Onboarding with Voice Type / Gender Preference](path/to/screenshot1.png)
*   [Screenshot 2: Main Recommendations Feed](path/to/screenshot2.png)
*   [Screenshot 3: Detailed Song View with Practice Advice](path/to/screenshot3.png)
*   [Screenshot 4: User Profile Editing](path/to/screenshot4.png)
*   [Link to Demo Video (e.g., on YouTube or Vimeo)](https://www.youtube.com/watch?v=YOUR_VIDEO_ID)

---

### **⭐ Connect with Me**

This project is a testament to my skills in mobile application development, AI integration, and robust data management. Feel free to connect or ask questions about its architecture and implementation!

*   [Link to your Portfolio/Website](https://www.mukiibs.dev)
*   [Link to your LinkedIn Profile](https://linkedin.com/in/joshua-d-mukiibi)
*   [Link to your GitHub Profile (if you have other public repos)](https://github.com/JDMukiibs)

---

### **📄 License**

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
