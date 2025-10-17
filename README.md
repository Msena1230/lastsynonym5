# Synonym Finder

Synonym Finder is a web-based application that helps you find context-aware synonyms for words in an English text. It dynamically suggests alternatives with Japanese translations and allows for one-click replacement, powered by the Google Gemini API. It also includes a history panel and a flashcard quiz feature to enhance your learning experience.

*(A screenshot of the application would be great here!)*

---

## ✨ Features

- **Context-Aware Synonym Generation**: Utilizes the Gemini API to provide high-quality synonyms that match the word's meaning in the sentence (e.g., distinguishing between "book" as a noun and "book" as a verb).
- **One-Click Word Replacement**: Simply click on a suggestion to replace the original word in the text.
- **Japanese Translations**: Displays Japanese translations for both the original words and the synonym candidates.
- **Interactive UI**:
    - A three-panel layout showing History, Text Input, and Synonym Candidates.
    - Hovering over a suggestion on the right highlights the corresponding word on the left.
    - Clicking a replaceable word in the text scrolls to its suggestion card.
- **Collapsible History Panel**:
    - Automatically saves your processed texts, grouped by date (Today, Yesterday, etc.).
    - The panel stays collapsed on the left and expands on hover for a clean workspace.
    - Clicking a history item restores the text and the original synonym analysis.
- **Bookmark & Flashcard System**:
    - Bookmark interesting words and their synonyms for later review.
    - Launch a flashcard quiz from your bookmarked words.
    - Flip cards to test your knowledge and delete words you've mastered.
- **Smart Filtering**: Common words (like 'the', 'a', 'is') are automatically filtered out to keep the synonym list focused and relevant.
- **Theme Support**: Switch between light and dark modes. Your preference is saved locally.
- **Secure API Key Handling**: Your API key is stored only in your browser's local storage.

## 🚀 Setup and Usage

To get this application running on your local machine or to deploy it on GitHub Pages, follow these simple steps.

### Prerequisites

- A modern web browser (e.g., Chrome, Firefox, Edge).
- A Google Gemini API key.

### Instructions

1.  **Get the Code**
    - Clone the repository or download the ZIP file and extract it.

2.  **Open the Application**
    - Simply open the `index.html` file in your web browser.

3.  **Set Up Your API Key**
    - Click the gear icon (<i class="fas fa-cog"></i>) in the top-right corner to open the settings modal.
    - Get your API key from [Google AI Studio](https://aistudio.google.com/app/apikey).
    - Paste your key into the input field and click "Save". The application is now ready to use!

## 🛠️ Technologies Used

- **HTML5**
- **CSS3**: With CSS Variables for easy theming.
- **Vanilla JavaScript**: No frameworks, just pure JS for a lightweight experience.
- **Google Gemini API**: For all natural language processing tasks.