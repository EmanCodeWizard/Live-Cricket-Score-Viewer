# Live-Cricket-Score-Viewer
🏏 Live Cricket Score Viewer
This is a Python GUI application built with Tkinter that fetches live cricket match scores from Cricbuzz using web scraping (requests + BeautifulSoup). Users can select ongoing matches and view live score details, match headers, and summaries.

(Make sure this image exists in your project folder)

📌 Features
GUI built with Tkinter

Match selection using a Combobox

Live cricket scores via Cricbuzz scraping

Displays:

Match title

Scorecard

Match summary

Styled with a background image

Error handling and user-friendly prompts

🚀 Getting Started
📁 Clone this repository
bash
Copy
Edit
git clone https://github.com/yourusername/cricket-score-tkinter.git
cd cricket-score-tkinter
📦 Prerequisites
Python 3.7+

Internet connection (to fetch live data)

📥 Install Dependencies
bash
Copy
Edit
pip install pillow requests beautifulsoup4
🛠️ How to Run
Make sure the file cric.jpg exists in the same folder as the script.

bash
Copy
Edit
python cricket_score_gui.py
A window will open allowing you to select a live match and view scores in real-time.

📂 Project Structure
bash
Copy
Edit
.
├── cricket_score_gui.py    # Main Python script
├── cric.jpg                # Background image (required)
└── README.md               # Project documentation
📸 Screenshot
(Replace with actual screenshot if available)

⚠️ Disclaimer
This project uses web scraping to fetch data from Cricbuzz. Changes in their HTML structure may break the app. Please use responsibly and avoid overloading their servers.

🙌 Credits
Live data from Cricbuzz

GUI: Tkinter

Parsing: BeautifulSoup

