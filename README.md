Data Analysis AI Agent (v6.0)
Ek powerful aur intelligent Python-based AI Agent jo CSV files (jaise Book5.csv) ko analyze karta hai aur aapke sawalat ke mutabiq Short ya Detailed answers provide karta hai.

✨ Key Features
Smart Query Handling: Agar aap specific sawaal poochenge (e.g., "Yasir Bilal ka hostel?"), to ye sirf wahi info dega. Agar aap "full details" mangenge, to poora record dikhayega.

Fuzzy Name Matching: Student ka naam likhne mein halki phulki galti ho jaye tab bhi ye sahi student detect kar leta hai.

Dynamic Data Visualization: Ek click ya command par Department-wise charts, Hostel occupancy aur Marks distribution graphs generate karta hai.

Interactive GUI: customtkinter ka istemal karte hue ek modern aur dark-themed interface.

Live Data Table: Poori CSV file ko app ke andar hi table format mein browse karne ki sahulat.

🛠️ Tech Stack
Language: Python

GUI: CustomTkinter

Data Handling: Pandas

Visualization: Matplotlib, Seaborn

Logic: FuzzyWuzzy (for name matching), Regex

🚀 How to Run
Clone the Repository:

Bash
git clone https://github.com/your-username/your-repo-name.git
Install Dependencies:

Bash
pip install pandas customtkinter matplotlib seaborn fuzzywuzzy python-Levenshtein
Prepare Data:
Apni CSV file ko C:\Users\sys\Desktop\Book5.csv path par rakhen ya code mein path update karen.

Launch App:

Bash
python your_script_name.py
🤖 Example Queries
"Ahmed ke marks kitne hain?" (Short Answer)

"Yasir Bilal ka hostel name?" (Specific Answer)

"Show full details of Student009" (Complete Data)

"Show marks distribution graph" (Visualization)
