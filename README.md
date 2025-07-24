# 📘 Mini Social Network – JSON Data Processing & Recommendations (Pure Python)

This project simulates a small-scale social network system using only core Python. It reads data from JSON files, cleans and structures that data, and provides basic **friend** and **page** recommendations — without using any external libraries.

---

## 📂 Project Overview

This project includes:

1. **Data Loading & Display**  
   Displaying users, their friendships, and liked pages in a readable format.

2. **Data Cleaning**  
   - Removed users with missing names  
   - Eliminated duplicate friends and pages  
   - Filtered out users with no friends or liked pages

3. **Friend Suggestion Algorithm**  
   Recommends friends based on mutual friends (i.e., “friends of friends”).

4. **Page Suggestion Algorithm**  
   Suggests pages a user might like based on common liked pages with other users.

---

## 📁 Files in This Repository

| File                      | Description |
|---------------------------|-------------|
| `display_data.ipynb`         | Displays user and page data in a readable format |
| `clean_data.ipynb`           | Cleans and saves structured JSON data |
| `friend_recommendation.ipynb`| Suggests friends based on mutual connections |
| `page_recommendation.ipynb`  | Suggests pages using shared interests |
| `data.json`, `data2.json` | Sample input datasets |
| `massive_data.json`       | Larger dataset for testing recommendations |

---

## ▶️ How to Run

Make sure you have **Python 3.x** installed.  
Then run any script in the terminal:

```bash
python display_data.ipynb
python clean_data.ipynb
python friend_recommendation.ipynb
python page_recommendation.ipynb
```

Each script loads data from a JSON file, processes it, and prints the result to the console.

---

## ✨ What I Learned

- Parsing and processing real-world structured data (JSON)
- Cleaning data with conditions and deduplication
- Working with dictionaries, sets, and lists in Python
- Designing recommendation logic from scratch
- Structuring a multi-file Python project

---

## 🔧 Possible Improvements

- Add a user interface using **Flask** or **Streamlit**
- Store recommendations in a separate JSON file
- Visualize user connections with graphs (e.g., using `networkx`)

---

## 👤 Author

**Omer Raza**  
Aspiring Data Scientist & AI Engineer  
M.Sc. Data Science Student  
[GitHub](https://github.com/omerwritescode)

---
