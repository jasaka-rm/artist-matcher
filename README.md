# 🎵 ArtistMatch Project

## 📌 Overview
ArtistMatch is a Python-based recommendation system that matches users to singers based on their preferences.

The program uses a structured database of **singers, albums, and authors**, and compares user answers from a questionnaire to find the best match.

---

## 🎯 Features
- 🎤 Database of singers with attributes (genre, mood, era, energy)
- 💿 Album database linked to singers
- 📚 Author database (optional extension)
- ❓ Interactive questionnaire for user preferences
- 🧠 Matching algorithm that scores and ranks singers
- 📊 Option to load data from Excel using **pandas**
- 🧾 Local database fallback for easy testing

---

## 🏗️ Project Structure

The project is organized into several parts:

- **Part 1:** Data model (`Singer`, `Author`, `Album`)
- **Part 2:** Database management (`MediaLibrary`)
- **Part 3:** Questionnaire system (`UserQuestionnaire`)
- **Part 4:** Matching algorithm (`SingerMatcher`)
- **Part 5:** Demo with local database
- **Part 6:** Demo with Excel database

---

## 📂 Files

- `ArtistMatch_script.ipynb` → Main notebook  
- `artistmatch_database.xlsx` → Excel database (3 sheets: singers, authors, albums)  
- `README.md` → Project description  

---

## ▶️ How to Run

1. Open the notebook in **Google Colab** or Jupyter Notebook  
2. Make sure the Excel file is in the same folder (or update the file path)  
3. Run all cells  
4. Use:
   - predefined answers (quick demo), or  
   - the questionnaire (interactive mode)

---

## 🧠 How It Works

1. The user answers questions about:
   - genre  
   - mood  
   - era  
   - energy  

2. Each singer is compared to the answers.

3. A score is calculated (maximum = 4).

4. The program returns:
   - the best matching singer  
   - optionally the top 3 matches  
   - recommended albums  

---

## 🛠️ Technologies Used

- Python 🐍  
- Object-Oriented Programming (OOP)  
- Pandas (for Excel data handling)  
- Google Colab  

---

## 👥 Team

This project was developed by a team of 5 students.

Each member contributed to different parts:
- Data model
- Database management
- Questionnaire
- Matching algorithm
- Testing and integration

---

## 🚀 Possible Improvements

- More advanced scoring system (weighted criteria)
- Larger and richer database
- User interface (GUI or web app)
- Recommendations for authors as well

---

## 📢 Notes

This project is designed as a **beginner-friendly application**, focusing on:
- clean structure
- clear logic
- simple but functional recommendation system

---
