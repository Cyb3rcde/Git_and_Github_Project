# 📘 Git & GitHub Learning Project

### 🔗 Quick Navigation

* [📌 Project Overview](#-project-overview)
* [🎯 Project Purpose](#-project-purpose)
* [🛠️ Tech Stack(Tools)](#-tech-stacktools)
* [🧠 Skills Demonstrated](#skills-demonstrated)
* [💻 Commands Used + Explanations](#-commands-used--explanations)
* [🚀 Highlights](#-highlights)
* [📝 Personal Note](#-personal-note)
* [👤 Author](#-author)
* [📄 License](#-license)
---

## 📌 Project Overview

A practical hands-on project completed as part of my Git and GitHub learning journey.

This repository documents my progress learning version control fundamentals using Git Bash / Command Line, while following structured checkpoint tasks.

It also serves as a record of my early development process, mistakes encountered, and technical growth.

---

## 🎯 Project Purpose

This project was created to primarily to practice core Git workflows such as:

* Creating local repositories / directories
* Navigating directories
* Repository initialisation
* Creating files and folders via terminal
* Tracking file changes
* Staging & committing files/changes
* Writing commit messages
* Viewing commit history
* Removing tracked files
* Global Git configuration
* Pushing repositories to GitHub

Although this started as an assignment, I’m keeping it public as a reflection of my learning path and technical foundation.

---

## 🛠 Tech Stack(Tools)

* Git
* GitHub
* Git Bash / Command Line

---

## 🧠Skills Demonstrated

✅ Version Control Basics
✅ Command Line Usage / Navigation
✅ File Tracking
✅ Git Logs / History
✅ Commit Management
✅ Repository Initialization
✅ Git Configuration
✅ GitHub Workflow(Connecting local repo to Github)
✅ Self Documentation

---

## 💻 Commands Used + Explanations

```bash id="g3ijtt"
cd "C:\Users\Nu_el\OneDrive\Desktop"
```

 Moves terminal into my Desktop directory.

```bash id="5e1i8q"
mkdir learn_git
```

 📁Created the directory / project folder named `learn_git` used to practice this assignment.

```bash id="m0v3gq"
cd learn_git
```

 📂Changes directory / Moves into the newly created project folder `learn_git`.

```bash id="4q1y3j"
git init
```

 🔧Initializes Git tracking inside the `learn_git` folder.

```bash id="f9djlwm"
touch third.txt
```

 📄Created the first file named `third.txt`.

```bash id="jct2ya"
git add third.txt
```

 🗃️Added file `third.txt` to staging area.

```bash id="0k4eq8"
git commit -m "adding third.txt"
```

 ✅Creates commit snapshots(saves first tracked version) with commit message "adding third.txt".

```bash id="mk9tqj"
git log
```

 🔍Displays commit history.

```bash id="m56v6s"
touch fourth.txt
git add .
git commit -m "adding fourth.txt"
```

 🔁Created, staged and committed another file. (`git add .` stages all changes in current folder)

```bash id="v6k7ii"
rm -rf third.txt
git add .
git commit -m "removing third.txt"
```

 🚮Deleted file `third.txt`, staged and committed the change.

```bash id="ekazj8"
git config --global core.pager cat
```

 ⚙️Changed Git pager output behavior.

```bash id="0n7ewt"
git config --global --list
```

 📜Shows global Git settings.

---

 ⚠️🌐 GitHub Note

The process of pushing this project to GitHub was done on a different directory and is not fully covered in this README, but commands used include:

```bash
git remote add origin https://github.com/Cyb3rcde/Git_and_Github_Project.git
git remote -v
git push -u origin main
```

---

## 🚀 Highlights

* Used real Git workflow from terminal
* Practiced commit lifecycle
* Learned configuration management
* Completed all checkpoint tasks successfully
* Preserved progress publicly on GitHub

---

## 📝 Personal Note

This repository represents my early steps into Git, Github and software development as a whole. I’m keeping it public as a reminder of where I started and how I built my knowledge over time. It reflects not just what I learned, but how I learned, including mistakes, fixes, and experimenting. I'm happy that I managed to finish this on my first attempt, all on my own.

---

## 👤 Author

**Cyb3rcde**

GitHub: https://github.com/Cyb3rcde

---

## 📄 License

This project is open for learning and educational purposes.
