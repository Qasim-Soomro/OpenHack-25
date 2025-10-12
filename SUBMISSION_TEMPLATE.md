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

## Project Categories

Choose one of these categories for your project:

### Education
Build solutions that enhance learning, teaching, or educational access

### Agriculture
Create tools for farming, food security, or agricultural innovation

### Energy and Climate Change
Develop solutions for sustainability, renewable energy, or environmental challenges

### Health Care
Design tools for health monitoring, medical access, or wellness improvement

---

## Project Types

Your solution can be implemented as:

- **Mobile App** - iOS, Android, or cross-platform applications
- **Web App** - Websites, web services, or browser-based tools  
- **Developer Tools** - CLI tools, plugins, frameworks, or libraries
- **Other Creative Solutions** - Games, hardware projects, or innovative approaches

---

## Judging Criteria

Your project will be evaluated based on:

| Main Criteria | Weight | Sub-Criteria | Sub-Weight | Description |
|---------------|--------|--------------|------------|-------------|
| **Uniqueness** | 15% | Application of Technologies | 50% | How innovative is the use of technology |
|  |  | Innovation | 50% | Originality and creative approach |
| **Proof of Concept** | 15% | Understanding of Problem to be Solved | 50% | Clarity of problem definition and solution approach |
|  |  | Understanding of Business Environment | 50% | Market awareness and business viability |
| **Functionalities and Features** | 15% | User Requirements | 50% | How well the solution meets user needs |
|  |  | Compatibility and Interoperability | 50% | Technical integration and system compatibility |
| **Quality** | 30% | Content & Standards | 60% | Code quality, documentation, and adherence to standards |
|  |  | Product Stability & Reliability | 40% | Performance, error handling, and robustness |
| **Creativity & Code Quality** | 25% | Originality and Innovation of the Idea | 50% | Creative problem-solving and unique approach |
|  |  | Clean, Well-documented, Maintainable Code | 50% | Code organization, comments, and maintainability |

---

## Need Help?

- **Submission Process:** Refer to this guide or [CONTRIBUTING.md](./CONTRIBUTING.md)
- **Questions:** Use [GitHub Discussions](https://github.com/OpenHack-25/Hackathon/discussions)
- **Technical Issues:** Contact organizers through official communication channels
- **General FAQ:** Check our [FAQ section](./README.md#faq) in the main README

---

**Good luck, and happy hacking!**

**Important:** Make sure to submit via Pull Request - GitHub Issue submissions are no longer accepted.

Made with love by the OpenHack'25 team