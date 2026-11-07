# 🏆 Sports Explorer

**Sports Explorer** is a Python desktop application built with PyQt5 that allows users to explore different sports, discover famous athletes, search for sports teams, and view team information.

The application features a colorful graphical user interface, sports photographs, famous player pictures, and team details powered by TheSportsDB API.

## 🌟 Features

### 🏅 Explore Different Sports
Explore 10 different sports:

- ⚽ Soccer
- 🏀 Basketball
- 🎾 Tennis
- ⚾ Baseball
- 🏈 American Football
- 🏏 Cricket
- 🏉 Rugby
- 🏒 Ice Hockey
- ⛳ Golf
- 🏐 Volleyball

### ⭐ Famous Athletes
Discover popular athletes from different sports, including:

- Lionel Messi
- Cristiano Ronaldo
- Pelé
- Kylian Mbappé
- Neymar
- Michael Jordan
- LeBron James
- Stephen Curry
- Serena Williams
- Roger Federer
- Novak Djokovic

Player photographs are retrieved when available.

### 🏀 Basketball Teams
Includes a built-in list of all 30 NBA teams, including:

- Los Angeles Lakers
- Boston Celtics
- Golden State Warriors
- Chicago Bulls
- Miami Heat
- New York Knicks
- Dallas Mavericks

The application also attempts to retrieve basketball team information from TheSportsDB.

### 🔎 Search Teams
Search for teams by name and explore matching results.

### 📋 Team Information
View available information about selected teams, including:

- Team name
- Sport
- League
- Stadium
- Country
- Year founded
- Team description
- Team logo

### 🎨 Colorful GUI
The application includes:

- Vibrant blue and cyan colors
- Colorful sport cards
- Sports photographs
- Featured athlete cards
- Separate team and information panels
- Easy-to-use search bar

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Main programming language |
| PyQt5 | Graphical user interface |
| Requests | API requests and image downloads |
| TheSportsDB API | Sports and team information |
| Wikipedia REST API | Available athlete photographs |

## 📦 Installation

### 1. Install Python

Download Python from:

https://www.python.org/downloads/

Make sure Python is added to your system PATH during installation.

### 2. Install the Required Libraries

Open your terminal in VS Code and enter:

```bash
pip install PyQt5 requests
```

### 3. Download or Clone the Project

Clone the repository:

```bash
git clone YOUR_REPOSITORY_URL
```

Or download the project files directly from GitHub.

### 4. Open the Project

Open the project folder in Visual Studio Code.

### 5. Run the Application

Run the following command:

```bash
python sports_explorer.py
```

## 🌐 API Information

This project uses **TheSportsDB API** to retrieve sports and team information.

API website:

https://www.thesportsdb.com/

The application uses the public test API key:

```python
API_URL = "https://www.thesportsdb.com/api/v1/json/123"
```

Some API endpoints have usage limits, so results may vary depending on API availability.

## 📁 Project Structure

```text
Sports-Explorer/
│
├── sports_explorer.py
│
└── README.md
```

## ⚙️ How It Works

1. Launch the Sports Explorer application.
2. Choose a sport from the sports gallery.
3. Browse famous athletes associated with that sport.
4. Search for a team using the search bar.
5. Select a team from the results.
6. View its available information and logo.

If basketball teams are unavailable through the API, the application uses its built-in NBA team list as a fallback.

## 🚀 Future Improvements

Possible future updates include:

- Live sports scores.
- Upcoming match schedules.
- Player statistics.
- Team standings and rankings.
- More sports and international teams.
- Improved player profiles.
- More team photographs and logos.

## 👨‍💻 Author

Created as a Python programming project to explore APIs, object-oriented programming, GUI development, and sports data.

## 📜 License

This project is intended for educational and personal use. Please follow the terms of service of the APIs and image sources used by the application.

---

**Explore sports. Discover teams. Learn about legendary athletes. 🏆**
