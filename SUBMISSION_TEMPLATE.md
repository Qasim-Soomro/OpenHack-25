# OpenHack'25 - Project Submission Guide 

Welcome, hackers!
Follow this **Pull Request-based submission process** carefully to submit your project for OpenHack'25.
Your submission here should **only include your code, model, and technical components.**
*Visuals (like screenshots, UI demos, or videos) will be collected separately through the submission form.*

---

## Step 1: Fork the Repository

1. Go to the official repo: [OpenHack'25 Hackathon Repo](https://github.com/OpenHack-25/Hackathon)
2. Click **"Fork"** to create your own copy.

---

## Step 2: Create Your Project Folder

Inside your forked repo, create a folder using this format:

```
TeamName_ProjectName/
```

Example:

```
CodeWarriors_AI-Waste-Classifier/
```

Your folder must include:

```
CodeWarriors_AI-Waste-Classifier/
├── README.md
├── /src              (source code)
├── /model            (ML model, if used)
├── requirements.txt  (or package.json)
└── main.py / app.js / index.ipynb
```

*No need to include UI designs, screenshots, or videos - only working code and models.*

---

## Step 3: Add a README.md

Each project must include a `README.md` file like this:

````markdown
# Project Title
AI Waste Classifier

## Team Name
CodeWarriors

## Team Members
- Alice - [@alicehub](https://github.com/alicehub)
- Bob - [@bobdev](https://github.com/bobdev)

## Problem Statement
Explain the problem your code or model solves.

## Solution
Describe your approach - how your logic, algorithm, or model works.

## Tech Stack
Languages: Python  
Libraries: TensorFlow, Pandas, NumPy  
Tools: GitHub Actions, Docker (if used)

## Setup Instructions
1. Clone your fork:
   ```bash
   git clone https://github.com/YourGitHubUsername/Hackathon.git
   ```

2. Navigate to your project:
   ```bash
   cd Hackathon/CodeWarriors_AI-Waste-Classifier
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the project:
   ```bash
   python main.py
   ```

## Category
Energy & Climate Change

## Challenges Faced
Briefly describe one or two technical challenges and how you solved them.

## Learnings
What you learned while building your model or logic.

## License
MIT License
````

---

## Step 4: Create Pull Request

Once your project is ready:

1. **Commit your changes:**
   ```bash
   git add .
   git commit -m "Add [TeamName] - [ProjectName] submission"
   ```

2. **Push to your fork:**
   ```bash
   git push origin main
   ```

3. **Create a Pull Request:**
   - Go to your forked repository on GitHub
   - Click **"Contribute"** → **"Open pull request"**
   - Title format: `[SUBMISSION] TeamName - ProjectName - Category`
   - Example: `[SUBMISSION] CodeWarriors - AI Waste Classifier - Energy & Climate Change`

4. **Fill out the Pull Request description:**
   ```markdown
   ## Team Information
   - **Team Name:** CodeWarriors
   - **Project Name:** AI Waste Classifier
   - **Category:** Energy & Climate Change
   - **Team Members:** @alicehub, @bobdev

   ## Project Summary
   Brief description of what your project does and how it solves the problem.

   ## Technical Highlights
   - Key technologies used
   - Main features implemented
   - Any innovative approaches

   ## Submission Checklist
   - [x] Code compiles and runs without errors
   - [x] README.md included with setup instructions
   - [x] All dependencies listed in requirements.txt/package.json
   - [x] Code follows project structure guidelines
   - [x] At least one commit per team member
   ```

---

## Step 5: Complete Official Submission

After creating your Pull Request:

1. Go to the official [Submission Form](https://forms.gle/form) (link coming soon)
2. Provide your Pull Request link, for example:
   ```
   https://github.com/YourGitHubUsername/Hackathon/pull/123
   ```
3. Upload visuals, screenshots, or demo videos in the form

*The Pull Request contains your code - visuals go in the submission form only.*

---

## Submission Rules

* **Pull Request Required:** All submissions must be made via Pull Request to be considered
* Include only **code, logic, or models** - no UI or visuals in the repository
* Make sure your code **runs without errors**
* Your **README must explain your logic and setup clearly**
* Submissions missing README or dependencies will not be reviewed
* **Deadline:** *October 14, 2025 - 11:59 PM*
* Follow the exact Pull Request title format: `[SUBMISSION] TeamName - ProjectName - Category`

---


**Good luck, and happy hacking!**

**Important:** Make sure to submit via Pull Request - GitHub Issue submissions are no longer accepted.

Made with love ❤️ by the OpenHack'25 team
