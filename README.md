# issueWiz 🎯


## Basic Details
### Team Name: Bonito Flakes


### Team Members
- Member 1: Mehrin Fathima Shamim - Government Model Engineering College, Thrikkakara
- Member 2: Diya Jojo - Government Model Engineering College, Thrikkakara
- Member 3: Aswathy S Ajith - Government Model Engineering College, Thrikkakara
  
### Hosted Project Link
https://issue-wiz.vercel.app/

### Project Description
IssueWiz is an AI-powered platform designed to lower the barrier to entry for open-source contributions by providing intelligent issue analysis, personalized recommendations, and contextual documentation. The system helps both newcomers and experienced developers navigate complex codebases and find suitable issues to work on.


### The Problem statement
Contributing to open-source projects can be daunting, especially for beginners. The complexity of understanding codebases, identifying relevant files, and navigating through sparse or overwhelming documentation creates barriers to entry .

### The Solution
IssueWiz simplifies this process by providing the following:

- **Issue Analysis Engine** : Analyzes issues, identifies relevant files, and generates contextual documentation with interactive guidance.
- **Skill-Based Issue Matcher** : Matches users' skills with suitable issues, providing ranked recommendations for both learning and contribution.
- **Interactive Learning Assistant** : Offers real-time, AI-driven assistance for understanding code, troubleshooting, and improving development practices.
By lowering these barriers, IssueWiz makes open-source contributions more accessible and engaging for developers of all levels.


## Technical Details
### Technologies/Components Used
For Software:
- **Languages used**: Python, TypeScript
- **Frameworks used**: FastAPI, Next.js
- **Libraries used**: GitHub API, OpenAI API, SentenceTransformer,ThreadPoolExecuter, aiohttp, numpy
- **Tools used**: Render, Vercel

For Hardware:
- No hardware used in this project.

### Implementation
For Software:
#### Installation
```bash
# Clone the repository
git clone https://github.com/yourusername/issuewiz.git
cd issuewiz

# Install dependencies
pip install -r requirements.txt
npm install

# Set up environment variables (GitHub API, OpenAI API, etc.)
# Create a `.env` file and add necessary keys

# Start the backend server
uvicorn backend.main:app --reload

# Start the frontend server
npm run dev
```

#### Run
```bash
# Backend
uvicorn backend.main:app --reload

# Frontend
npm run dev
```
### Project Documentation
For Software:

# Screenshots (Add at least 3)
![image](https://github.com/user-attachments/assets/5cd41a5e-2a13-43f2-8a3f-f3183475561f)
*issueWiz Landing Page*

![image](https://github.com/user-attachments/assets/9a22aa07-a260-46ef-a091-e29d4f0a006b)
*issueWiz features*

![image](https://github.com/user-attachments/assets/7586f338-5bbf-4fc8-b916-b16d2bdf979e)
*Repository analysis*

![image](https://github.com/user-attachments/assets/25c5e572-b148-4f46-a49d-e42c6dab1a2e)
*Issue matcher*

![image](https://github.com/user-attachments/assets/295f3dfe-59d6-465a-9009-c6a0e8ae6907)
*issue recommendation page*



For Hardware:

# Schematic & Circuit
![Circuit](Add your circuit diagram here)
*Add caption explaining connections*

![Schematic](Add your schematic diagram here)
*Add caption explaining the schematic*

# Build Photos
![Team](Add photo of your team here)


![Components](Add photo of your components here)
*List out all components shown*

![Build](Add photos of build process here)
*Explain the build steps*

![Final](Add photo of final product here)
*Explain the final build*

### Project Demo
# Video
[Add your demo video link here]
*Explain what the video demonstrates*

# Additional Demos
[Add any extra demo materials/links]

## Team Contributions
- **Mehrin**: Developed the backend with FastAPI and integrated Supabase for user data and authentication.
- **Diya**: Worked on the frontend development using Next.js, integrating the GitHub API for issue tracking, and AI-powered documentation.
- **Aswathy**: Implemented SentenceTransformer , a deep learning model for issue mapping and code analysis .

---
Made with ❤️ at TinkerHub
