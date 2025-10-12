# Team Collaboration Guidelines

## For OpenHack'25 Participants

Each team must submit their project code to the official repository:
**[OpenHack-25/Hackathon](https://github.com/OpenHack-25/Hackathon)**

Follow these steps carefully to collaborate and submit your work:

---

## Team Folder Setup

* Only **one team member (Team Leader)** should create a folder inside the repo.
* Folder name format:

  ```
  TeamName_ProjectName/
  ```

  Example:

  ```
  CodeWarriors_SmartWaste/
  ```

---

## Folder Contents

Your folder should include **only code and technical assets** - no visuals.
Recommended structure:

```
TeamName_ProjectName/
│
├── src/               # main project code
├── model/             # ML model (if any)
├── README.md          # project summary, setup guide, team info
└── requirements.txt   # dependencies (if needed)
```

*Visuals (like screenshots, video demos, or presentations) will be collected separately through the Google Form.*

---

## Working Together

You can choose **one of two collaboration methods**:

### Option A (Recommended):

* The Team Leader forks the main repo.
* Adds all teammates as **collaborators** on their fork.
* Everyone commits their part on branches and merges into the team folder.
* Finally, the Team Leader opens a **Pull Request (PR)** to the main repo.

### Option B (Simpler for beginners):

* Team Leader creates the team folder directly in the main repo.
* Other members share their code (via branches or Google Drive).
* Leader merges everything and pushes the final version.

---

## Before Submission

Make sure your:

* Folder name follows the required format
* Code runs successfully
* README includes:
  * Problem Statement
  * Solution Overview
  * Tech Stack
  * Setup/Run Instructions
  * Team Members

---

## Additional Resources

- **[SUBMISSION_TEMPLATE.md](./SUBMISSION_TEMPLATE.md)** - Complete submission guide with Pull Request process
- **[PROBLEMS.md](./PROBLEMS.md)** - Problem statements (released 15 minutes before hackathon)
- **[CONTRIBUTING.md](./CONTRIBUTING.md)** - General contribution guidelines
- **[README.md](./README.md)** - Hackathon overview and instructions

---

**Need help?** Use [GitHub Discussions](https://github.com/OpenHack-25/Hackathon/discussions) for questions about team collaboration.