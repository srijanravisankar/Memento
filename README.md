# 🧠 Memento Flashcards

**Memento Flashcards** is a desktop flashcard app designed to help users learn and retain knowledge effectively using **spaced repetition** and other study modes. It is lightweight, intuitive, and designed for personal offline use.

---

## 🚀 Features

- 📁 **Organized Study Structure**:  
  - Create **folders** to group related decks.
  - Folders can contain subfolders and multiple decks.
  - Decks hold multiple flashcards.

- ✍️ **Full Control**:  
  - Create, rename, update, and delete **folders**, **decks**, and **flashcards** with ease.
  - Clean and intuitive interface for managing study materials.

- 📚 **Three Study Modes**:
  1. **FSRS (Free Spaced Repetition Scheduler)**  
     - Uses an algorithm to help you remember cards at optimal intervals.
     - Tracks and updates your flashcard learning state:
       - `Learning`: New card studied for the first time.
       - `Review`: Card that has graduated from learning.
       - `Relearning`: Card that lapsed and is being relearned.
     - Card responses:
       - `Again`: You forgot the card.
       - `Hard`: Remembered with serious difficulty.
       - `Good`: Remembered with hesitation.
       - `Easy`: Remembered easily.

  2. **Ordered Study**  
     - Go through cards in the order they were created.

  3. **Random Study**  
     - Shuffle and study cards in random order.

---

## 🖥️ How to Use

1. **Download the `Memento.zip` file** from the releases page https://github.com/srijanravisankar/Memento/releases.
2. Extract and run the executable for windows.

   ⚠️ **If Windows shows a “Windows protected your PC” warning:**
   - Click **More Info**
   - Then click **Run Anyway**

3. The app will launch in your default browser.
   - Use **Google Chrome** or a **Chromium-based browser** if the app does not open in other browsers.

4. Start organizing your content:
   - Use the **main page** to create folders and decks.
   - Add flashcards to decks and manage them via the UI.

---

## 📁 Database Location

Your flashcard data is stored locally so no internet connection is needed to use the app or access your data.. A new SQLite database file is created automatically when you launch the app for the first time at:
*C:\Users<YourUsername>\AppData\Local\SrijanRavisankar\MementoFlashcards\memento_flashcard_db.sqlite3*

---

## 🔒 Privacy & Licensing

- This app is a closed-source utility distributed in executable form only.
- **Modifying, extracting, or reverse-engineering the app is not permitted.**

---

## 🙋‍♂️ Support

If you run into issues or have suggestions, feel free to open an issue on [GitHub](https://github.com/your-repo/issues) or contact the developer directly through mail. (mailID: srijanvr@gmail.com)

---

## 📌 About

**Developer**: Srijan Ravisankar  
**Project**: Memento Flashcards  
**Built With**: FastAPI, React, SQLite, and FSRS algorithm

---

