# 🧹 Cleaned eSports Survey Dataset

This project involves cleaning and preprocessing a raw eSports survey dataset using **Python (Pandas)**, followed by data pivoting and summarization in **Microsoft Excel**.

## 📂 About the Dataset

The dataset contains responses to an online survey focused on eSports viewership behavior and preferences, including:

- Age group
- Gender
- Familiarity with eSports
- Frequency of watching tournaments
- Preferred game genres
- Platforms used for viewing
- Whether they follow teams or players

## 🛠️ Data Cleaning & Processing

The raw Excel file was cleaned using Python and Pandas:

- ✅ Converted timestamp to `date` and `time` columns
- ✅ Cleaned inconsistent age group entries (e.g., “35 and above” → “35+”)
- ✅ Standardized game type names (e.g., “First-person shooters (e.g., CS:GO, Valorant)” → “First-person shooters”)
- ✅ Dropped unnecessary columns
- ✅ Removed milliseconds from time values

## 📊 Pivot Analysis in Excel

After cleaning, key pivot tables were created in Excel to derive insights such as:

- Preferred game types by age group
- Platform preferences across genders
- Frequency of tournament viewing by demographic

## 📁 Files

- `cleaned_esports_data.xlsx` – Cleaned dataset with added pivot analysis
- `notebook.ipynb` *(optional)* – Jupyter notebook used for cleaning (if you want to include it)

## 🚀 Tools Used

- Python (Pandas)
- Jupyter Notebook
- Microsoft Excel

## 🔍 Sample Insights (optional)

> 🧠 Majority of 18–24 age group prefer **MOBA** games  
> 📱 YouTube and Twitch dominate platform preferences  
> 🎮 A strong overlap exists between frequent viewers and those who follow specific teams or players

## 📌 Author

**Rachan** – Passionate about data, gaming, and building smart solutions.

---

⭐️ If you found this dataset useful or interesting, feel free to star the repo!
