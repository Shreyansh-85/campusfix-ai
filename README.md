🎓 CampusFix AI

A simple web application prototype to report campus issues with AI-style categorization and priority.

CampusFix AI allows students or campus users to describe problems (like maintenance or infrastructure issues) and receive a category and priority for the issue.

📸 Preview
![CampusFix AI Preview](assets/preview.png)

🚀 Features

Simple and intuitive UI

Input field to describe campus issues

AI-style analysis (demo logic)

Displays:

Category (e.g., Infrastructure)

Priority (e.g., High)

Fully responsive, clean design

No external libraries or frameworks required

🛠️ Built With

HTML5

CSS3

JavaScript (Vanilla)

📁 Project Structure
campusfix-ai/
│
├── index.html       # Main app file
├── README.md        # Project documentation
└── assets/
    └── preview.png  # Screenshot for README

▶️ How to Use

Clone this repository:

git clone https://github.com/Shreyansh-85/campusfix-ai.git


Open index.html in your browser.

Type your campus issue in the input box.

Click Analyze Issue to see a demo category and priority.

🧠 How It Works

The current version uses a static JavaScript function:

function analyzeIssue() {
  document.getElementById("result").innerHTML =
    "<b>Category:</b> Infrastructure<br><b>Priority:</b> High";
}


⚠️ This is a placeholder. Future versions can integrate a real AI model for dynamic issue classification.

📌 Example

Input:

Water leakage in the library ceiling.


Output:

Category: Infrastructure
Priority: High

🔮 Future Improvements

Integrate AI API for dynamic classification

Add backend database to store reported issues

Admin dashboard for monitoring

User authentication

Image uploads for reporting issues

Mobile-friendly improvements

📄 License

This project is licensed under the MIT License.

⭐ Contribution

Feel free to fork this repository and submit pull requests. Feedback and suggestions are welcome.
