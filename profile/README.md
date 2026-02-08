# Introduction to Design Track 3 (Android App Development)
![Contributors](https://img.shields.io/badge/contributor-PiranitaGomez-pink)![Contributors](https://img.shields.io/badge/contributor-CleberCarvalho-green)

> Design is not just what it looks like and feels like. Design is how it works.
> 
> -- <cite>Steve Jobs</cite>

# Description
This repository contains the Android Studio versions of the apps developed in the Introduction to Design Track 3 (ID3) course. ID3 is an introductory Android development course designed for beginners, offered every spring semester to freshmen at Kyoto University of Advanced Science (KUAS), Japan.

In the ID3 course, MIT App Inventor serves as the official IDE, providing a visual programming environment for students to create Android apps. This repository hosts the Android Studio refactors of those apps, most of which have been adapted into smartwatch apps to enhance portability and accessibility—pushing the boundaries of app development and enabling seamless, ubiquitous interactions directly on the wrist.

## What you’ll find here

### Android Studio refactors of weekly apps
These repos contain Android Studio implementations of weekly hands-on tasks from the course:

- **Week 2 — BMI App**
  - Repo: `ID3_w2BMIApp`
  - Includes:
    - `week2_BMIapp` (Android)
    - `week2_BMI4watch` (Wear OS)

- **Week 3 — Quiz App (Wear OS + Android)**
  - Repo: `ID3_w3QuizApp`
  - Includes:
    - `week3_Quizapp` (Android)
    - `week3_Quiz4Watch` (Wear OS)
    - `quizAppWatchDemo` (demo assets)

- **Week 4 — Voice Quiz App**
  - Repo: `ID3_w4VoiceQuizApp`
  - (Work-in-progress / minimal scaffolding in the current public version)

### Student final projects
- `civilian` — final projects from civilian teams  
- `swat` — final projects from S.W.A.T teams  

### Organization utilities
- `.github` — org-level GitHub settings (e.g., templates, workflows)

## Getting started

### Prerequisites
- **Android Studio** (recent stable version recommended)
- JDK as required by your Android Studio version
- For Wear OS apps: a **Wear OS emulator** or physical Wear OS device

### Run an app
1. Clone the repo you want:
   ```bash
   git clone https://github.com/ID3-AndroidAppDev/<REPO_NAME>.git
2. Open it in Android Studio.
3. Select the appropriate run configuration/module (Android or Wear OS).
4. Run on an emulator/device.

# Notes on Android Gradle Plugin (AGP) compatibility
Some repos may use newer AGP versions than older Android Studio installations support. If you see an AGP compatibility error, you have two options:
* Upgrade Android Studio / Gradle to match the project, or
* Downgrade the project’s AGP/Kotlin versions (commonly via libs.versions.toml, plus any necessary updates in build.gradle.kts and gradle-wrapper.properties).
  
Each repo may include a short note in its README with guidance.

# Contributing
If you’re a student in the course, feel free to fork the weekly repos and experiment. Keep commits small and meaningful. When submitting improvements, include:
* a short description of what changed,
* screenshots (for UI changes),
* and device/emulator info when relevant.

If you’re an external contributor, issues and PRs are welcome for bug fixes, documentation improvements, and refactoring suggestions.

# License
Most weekly-app repositories in this organization use the Apache License 2.0, while some student project repositories may use different licenses (e.g., MIT).
Please check the LICENSE file in each repository for details.

# Miscellaneous
### The ID3 Course
We have been offering the ID3 course since 2020 and have published several papers at prestigious educational conferences and journals. For more details, refer to the following publications:
> Liang Z. (2024) [More Haste, Less Speed?: Relationship between Response Time and Response Accuracy in Gamified Online Quizzes in an Undergraduate Engineering Course](https://www.frontiersin.org/journals/education/articles/10.3389/feduc.2024.1412954/full). Front. Educ. - Higher Education, 9. Doi: 10.3389/feduc.2024.1412954. (SCI/Scopus)

> Liang Z. (2023) [Enhancing Learning Experience in University Engineering Classes with Kahoot! Quiz Games](https://library.apsce.net/index.php/ICCE/article/view/1036). In Proceedings of the 31st International Conference on Computers in Education (ICCE 2023), Takamatsu, Japan. (SCI/Scopus)

> Liang Z. (2023) [Comparing Attitudes Towards Mobile App Development between International Students and Domestic Japanese Student](https://ieeexplore.ieee.org/document/10398300). In Proceedings of the 2023 IEEE International Conference on Teaching, Assessment and Learning for Engineering (TALE 2023), Auckland, New Zealand. (SCI/Scopus)

> Liang Z, Piumarta I. (2023) [An Experience Report on English Medium Instruction (EMI) based Computing Education in a Faculty of Engineering in Japan](https://ieeexplore.ieee.org/document/10229348). In Proceedings of the 35th IEEE International Conference on Software Engineering Education and Training (CSEE&T 2023), Tokyo, Japan. (SCI/Scopus)

> Liang Z. (2022) [Contextualizing introductory app development course for first-year engineering students](https://ieeexplore.ieee.org/document/10148503). In Proceedings of the 2021 IEEE Conference on Teaching, Assessment, and Learning for Engineering (TALE 2022), Hong Kong. (SCI/Scopus)

> Liang Z, Nishi M, Kishida I. (2021) [Teaching Android App Development to First Year Undergraduates: Textual Programming or Visual Programming?](https://ieeexplore.ieee.org/document/9678602) In Proceedings of the 2021 IEEE Conference on Teaching, Assessment, and Learning for Engineering (TALE 2021), Wuhan, China. (SCI/Scopus)  

### The Research Group
The instructor and TAs of the ID3 course are affiliated with the Ubiquitous and Personal Computing (UBICOMP) Lab at KUAS, where one of the primary research focuses is on smartwatch interaction and smartwatch-supported health behavior change. Feel free to visit the homepage of our [UBICOMP Lab](http://www.ubicomp-lab.org). 

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
