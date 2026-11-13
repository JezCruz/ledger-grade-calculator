# Little Ledger

**A simple, minimalist college grade calculator with a warm sepia aesthetic.**

Little Ledger is a browser-based grade calculator designed for college students. It allows users to organize their quizzes, activities, assignments, projects, and other academic scores while automatically calculating their overall percentage average.

## Features

- **No Login Required** – Start using the calculator immediately.
- **Student Name** – Personalize your grade dashboard.
- **Flexible Grade Entries** – Add quizzes, activities, assignments, projects, examinations, recitations, laboratory work, and custom entries.
- **Points-Based Computation** – Enter points earned and total possible points (e.g., 18/20).
- **Two Result Modes** – View your average as a percentage or a college grade equivalent.
- **Custom Grade Scale** – Adjust grade conversion thresholds according to your school's grading system.
- **Grade Management** – Add, edit, and delete grade entries.
- **Local Storage** – Keep your grades saved in your browser.
- **Clear All** – Remove your saved name and grade entries whenever you want.
- **Music Player** – Listen to a YouTube playlist with playback and volume controls.
- **Responsive Design** – Works on desktop and mobile devices.

## Grade Computation

Little Ledger uses a points-based computation:

`Average = (Total Points Earned / Total Possible Points) × 100`

Example:

| Activity | Score |
|---|---:|
| Quiz 1 | 18/20 |
| Activity 1 | 20/20 |
| Project 1 | 85/100 |
| **Total** | **123/140** |

Overall Average: **87.857%**

## Technology Stack

- HTML5
- CSS3
- Vanilla JavaScript
- Browser Local Storage
- YouTube IFrame Player API

## Getting Started

1. Clone this repository:

   ```bash
   git clone https://github.com/JezCruz/ledger-grade-calculator
   ```

2. Open the project folder.
3. Make sure the main file is named `index.html`.
4. Open `index.html` in your preferred browser.

No installation or package manager is required.

## Data Privacy

- No account registration or login.
- No custom backend or database.
- Grade information is stored in the user's browser using Local Storage.
- Data is not synchronized between devices or browsers.
- Users can delete their saved data using the Clear All option.

**Note:** Clearing browser site data or using a different browser may remove access to previously saved grades.

## Music

The built-in music player uses the YouTube IFrame Player API. An internet connection is required for music playback. Playback availability depends on YouTube and the playlist's embedding permissions.

## Deployment

Little Ledger can be deployed as a static website using Vercel or GitHub Pages.

For Vercel:
1. Import the GitHub repository.
2. Select the appropriate framework preset for a static site, if available.
3. Leave the Build Command and Output Directory empty when using a root-level `index.html` with no build process.
4. Deploy the project.

## License

Choose and add an appropriate open-source license before allowing others to reuse or redistribute the project.
