# 📖 The Translation Guide: From SPSS to Python

**Don't panic.** You don't need to relearn math. You just need to learn the new vocabulary for the concepts you already know.

If you have used SPSS or Excel, you are already thinking like a Data Scientist. Here is your dictionary to translate those thoughts into Python code.

| Concept | 🧠 In Psychology / SPSS | 🐍 In Python (Pandas) |
| :--- | :--- | :--- |
| **The Entire Dataset** | The Spreadsheet / "Data View" | `df` (short for DataFrame) |
| **A Column** | A Variable (e.g., "Age", "RT") | `Series` |
| **A Row** | A Participant / Subject | `Index` |
| **Cleaning Data** | Removing outliers manually / "Select Cases" | `df.dropna()` or `df[df['RT'] < 1000]` |
| **Statistics** | Clicking "Analyze > Correlate" | `df.corr()` |
| **Descriptive Stats** | Clicking "Analyze > Descriptives" | `df.describe()` |
| **Graphs** | Chart Builder | `seaborn` or `matplotlib` |
| **Loading Data** | File > Open > Data... | `pd.read_csv('filename.csv')` |

---

### 💡 The Big Difference
* **In SPSS:** You **click** on what you want to do (Menu-based).
* **In Python:** You **type** what you want to do (Code-based).

*The logic remains exactly the same!*
