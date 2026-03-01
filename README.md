# Admission_Chatbot
🌸 SIGC Admission Chatbot — Zyra
A fully self-contained, single-file web application for Shrimati Indira Gandhi College (SIGC), Tiruchirappalli.
It provides an interactive college website with a built-in AI-style virtual assistant named Zyra that answers student queries about admissions, programmes, fees, placements, and more.

🖥️ Live Demo
Simply open Sigc_Admission_Chatbot.html in any modern browser — no server, no dependencies, no installation required.

✨ Features
🌐 Multi-Section College Website
SectionDescriptionHomeHero banner, highlights, and key statsAboutHistory, milestones timeline, vision & missionAcademicsUG/PG/PhD programmes and 
departmentsAdmissionsStep-by-step admission process and eligibilityPlacementsRecruiter logos, stats, and success storiesCampus LifeFacilities,
clubs, and student activitiesContactAddress, phone, map directions, and contact form
🤖 Zyra — Virtual Admission Assistant

Floating chatbot accessible from any page
Smart NLP keyword matching to understand natural language queries
Quick-reply chips for common questions
Answers cover: programmes, fees, scholarships, eligibility, placements, campus, contact info, and more
Typing animation for a realistic chat feel
Fully keyboard accessible (Enter to send)


🚀 Getting Started
Option 1 — Open Directly
bash# Clone the repository
git clone https://github.com/your-username/sigc-admission-chatbot.git

# Open the file in your browser
open Sigc_Admission_Chatbot.html
Option 2 — GitHub Pages (Recommended)

Fork or push this repository to your GitHub account.
Go to Settings → Pages.
Set the source branch to main and root folder to /.
Your site will be live at https://your-username.github.io/sigc-admission-chatbot/Sigc_Admission_Chatbot.html.


📁 Project Structure
sigc-admission-chatbot/
│
├── Sigc_Admission_Chatbot.html   # Entire app in one file
└── README.md                     # This file
The project is intentionally a single HTML file — all CSS, JavaScript, and content are embedded inline for maximum portability.

🛠️ Tech Stack
TechnologyUsageHTML5Semantic structure and multi-section layoutCSS3Custom properties, Grid, Flexbox, animationsVanilla JavaScriptNavigation engine, chatbot NLP logicGoogle FontsCormorant Garamond + DM Sans typography
No frameworks. No build tools. No external dependencies beyond Google Fonts.

💬 Chatbot — Topics Zyra Can Answer

Programmes offered (UG, PG, MBA, MCA, PhD)
Admission process and important dates
Eligibility criteria
Fee structure and scholarship details
Placement statistics and top recruiters
Campus facilities (library, labs, hostels, sports)
NAAC grade and accreditations
Contact details and how to reach the campus
About the college — history, vision, mission


🎨 Customisation
To adapt this for another institution:

College info — Search and replace Shrimati Indira Gandhi College and SIGC with your college name throughout the file.
Colours — Edit the CSS variables at the top of the <style> block:

css   :root {
     --burgundy: #7b2d9b;
     --gold: #6a1b9a;
     --accent: #f9a825;
     /* ... */
   }

Chatbot knowledge base — Update the zyraKB array in the <script> section with your college's specific information.
Navigation sections — Add or remove <section> tags and corresponding nav links as needed.


🏫 About SIGC
Shrimati Indira Gandhi College was founded in 1984 by Vidya Seva Ratnam K. Santhanam in Tiruchirappalli, Tamil Nadu. It is one of the first two women-only colleges in Tamil Nadu, affiliated to Bharathidasan University, and holds NAAC 'A' Grade accreditation and ISO 9001:2015 certification.

📍 College Road, Chatram, Tiruchirappalli – 620 002
📞 0431-2702797 / 2701453
🌐 sigc.edu.in


📄 License
This project is open-source and available under the MIT License.

🙌 Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you'd like to change.

Fork the repository
Create your feature branch (git checkout -b feature/your-feature)
Commit your changes (git commit -m 'Add some feature')
Push to the branch (git push origin feature/your-feature)
Open a Pull Request


Made with ❤️ for SIGC, Tiruchirappalli
