# 🏏 Cricbuzz LiveStats: Real-Time Cricket Insights & SQL-Based Analytics  

Live App URL- https://cricbuzz-live-stats-nbdsycraxrt2m5q9l7kucg.streamlit.app/

## 📖 Overview  
**Cricbuzz LiveStats** is an interactive cricket analytics dashboard built with **Python, SQL, and Streamlit**, powered by the **Cricbuzz API**.  
The platform integrates real-time cricket data into a SQL database, enabling live match tracking, advanced analytics, and full CRUD operations.  

---

## 🎯 Problem Statement  
The project aims to create a comprehensive cricket analytics platform that delivers:  
- ⚡ Real-time match updates  
- 📊 Detailed player & team statistics  
- 🔍 SQL-driven analytics  
- 🛠️ Full CRUD operations for data management  

---

## 💼 Business Use Cases  
- **Sports Media & Broadcasting** → Real-time insights for commentary & match analysis  
- **Fantasy Cricket Platforms** → Player form tracking & head-to-head stats  
- **Cricket Analytics Firms** → Data-driven modeling and performance evaluation  
- **Educational Institutions** → SQL practice with engaging cricket datasets  
- **Sports Betting & Prediction** → Historical performance insights & venue-based analysis  

---

## 🏗️ Approach  

### 🌐 API Integration  
- Cricbuzz REST API via `requests`  
- Real-time fetching of match data, player stats, and series info  

### 🖥️ Interactive Dashboard  
- Multi-page app using **Streamlit**  
- Live scorecards, player stats, SQL query interface  
- Admin-friendly CRUD operations  

### 🗄️ SQL Database Integration  
- Supports **SQLite, PostgreSQL, MySQL**  
- Centralized connection handling (`utils/db_connection.py`)  
- Optimized queries with indexing  

### ⚙️ CRUD Operations  
- Add, update, and delete player & match records via UI  

---

## 📚 SQL Practice Questions (25 Included)  
The project includes **25 SQL queries** ranging from beginner to advanced:  
- **Beginner**: SELECT, GROUP BY, ORDER BY  
- **Intermediate**: JOINs, subqueries, aggregates  
- **Advanced**: Window functions, CTEs, analytical queries  

Example queries:  
- Top 10 ODI run scorers  
- Matches in the last 30 days  
- Venue stats with >50,000 capacity  
- Toss impact on match outcomes  
- Player form & momentum trends  

---

## 📌 Features (By Page)  

1. **Home Page**  
   - Project overview, tools used, navigation  

2. **Live Match Page**  
   - Real-time match updates from Cricbuzz API  
   - Detailed scorecards, batsmen/bowler stats, venue details  

3. **Top Player Stats Page**  
   - Batting & bowling leaderboards  
   - Most runs, highest scores, most wickets, etc.  

4. **SQL Queries & Analytics Page**  
   - Run 25+ SQL queries directly in Streamlit  
   - Interactive tables for insights  

5. **CRUD Operations Page**  
   - Add, update, delete player/match stats  
   - UI-driven data manipulation  

---

## 🛠️ Tech Stack  
- **Programming**: Python  
- **Framework**: Streamlit  
- **Database**: SQL (SQLite/MySQL/PostgreSQL)  
- **Libraries**: pandas, requests  
- **Data Source**: Cricbuzz API  

---

## 📦 Installation & Setup  

1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/cricbuzz-livestats.git
   cd cricbuzz-livestats
   ```

2. Create & activate a virtual environment:  
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Mac/Linux  
   venv\Scripts\activate      # On Windows  
   ```

3. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```

4. Set up database & environment:  
   - Configure `utils/db_connection.py`  
   - Add `.env` file with API keys and DB credentials  

5. Run the app:  
   ```bash
   streamlit run app.py
   ```

---

## 📊 Expected Results  
- Real-time cricket dashboard  
- SQL-based analytics with 25+ queries  
- Player & team performance tracking  
- CRUD-enabled database operations  

---

## 📑 Deliverables  
- Source code (Python + Streamlit)  
- SQL schema & queries  
- Requirements.txt  
- Documentation (this README + project doc)  
- Working cricket analytics dashboard  

---

## 🏷️ Technical Tags  
`Python` `Streamlit` `SQL` `Database` `REST API` `pandas` `requests` `Sports Analytics` `Web Development`  
