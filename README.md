# Sup, it is Dima here! <img src="images/wave.gif" height=30 width=30>

## 👀 About me

- 🔮 Kotlin developer
- 💼 [Link to my CV](https://drive.google.com/file/d/1OS9tyvihp2dLTVcszTX-gm8qA9iQDXzw/view?usp=sharing)
- ✨ C++ enjoyer
- 🗿 [Giga-Chad LLC](https://github.com/Giga-Chad-LLC) member

## 🤝 Contact

[![Telegram Badge](https://img.shields.io/badge/-Telegram-0088cc?style=for-the-badge&logo=appveyor&logo=Telegram&logoColor=white&color=blue)](https://t.me/dmitrii_artuhov)
[![LinkedIn Badge](https://img.shields.io/badge/-Linked%20In-9cf?style=for-the-badge)](https://www.linkedin.com/in/dmitrii-artiukhov/)


## 🎓 Education

Bachelor of  Science in Computer Science

- **Constructor (formerly Jacobs) University Bremen** (CUB)
- **Higher School of Economics in Saint Petersburg** (HSE Spb)

## 👩🏻‍💻 Work

> Most relevant work experience is listed in my CV above or on linkedin.

## 🛠️ Projects

> Projects for each language are listed chronologically, most notable are marked with emoji.


### 💙 C++

- ❗ [Weak Memory Models Simulator](https://github.com/dmitrii-artuhov/weak-memory-models-simulator): a 3rd year semester project at CUB of the same named course. This course tought me differences between hardware & pl memory models (MM) and concepts around weak MM in general (such as transitive and declarative memory model definitions, execution graph consistency criteria, OOTA problem, and different exisiting memory models, such as RC11). In this project I implemented 4 memory models: SC, TSO, PSO, Strong RA, interpretors for them, and lexer + parser for a simple programming language to write multithreaded programs with.

- ❗ [PNG Decoder](https://github.com/dmitrii-artuhov/PNG-decoder): decoder that reads PNG image binary data from disk and parses it as RGB array. It was a part of "Effective C++" course held by Spectral:Technologies during 2nd year of education at HSE (SPb).

- [ASCII Converter](https://github.com/Giga-Chad-LLC/ASCII-Converter): a converter that parses BMP image binary data from disk and creates an ASCII equivalent image (as a plain text file).

- ❗ [InVasion](https://github.com/Giga-Chad-LLC/InVasion): 1st year project at HSE Spb, an online multiplayer shooter game with top-down view. It was my first experience coding a big pet project in C++. It was done completely from scratch on the backend part. For the graphics we (it was a team of 3 people) used Godot engine. My duties were to implement asynchronous server (I created TCP server using Boost Asio), data (de)serialization, and whole front-end.

- **University Labs** (unfortunately, I cannot put them publicly): 1st year at HSE Spb labs which included unit-testing library written using macros, widgets hierarchical collection with virtual methods, tic-tac-toe terminal game with dynamically loaded graphics library, custom unique and shared pointers, TCP-server that emulated bank transactions between arbitrary number of connected users, BMP images parser, custom vector with allocators.

- [Gengo](https://github.com/dmitrii-artuhov/gengo): my high-school experience of writing non-contest code in C++. A very bad programming language. My code here sucks, but I still put it here for the record purposes. Btw, "gengo" means "language" in Japanese 🤓.


### 🔸 Java & Kotlin

- [Devscribe](https://github.com/Giga-Chad-LLC/Devscribe): *(this one is Kotlin project, the rest are in Java)* a 3rd year semester project at CUB in IDE development course. It is a simple IDE with such features as: text modification, shortcuts, mouse navigation, in-file searching, virtual file system (VFS), syntax highlighting for a custom programming language, text scaling and theme switching. It was a project of 2 people, my part was mostly VFS and UI components.

- [Java Symbols Counter](https://github.com/dmitrii-artuhov/symbols-counter-intellij-plugin): Intellij IDEA plugin for counting symbols (classes, methods per each file) in java projects. It was an assessment for one of the JetBrains internships. I crunched pretty hard on it in a short period of time, since I have never worked with IDEA plugins and Swing UI components before.  

- ❗ [Enchanted Towers](https://github.com/Giga-Chad-LLC/Enchanted-Towers): 2nd year semester project at HSE Spb, an android game in which players compete by capturing and holding towers on a real map by casting spells on their phone screens (drawing predefined curves with fingers) or on actual paper (by taking photo of them) and destroying protection walls of towers (thus, capturing the foe's tower). It was a team project of 3 people. My duties were: implementation of canvas interactions (eg. drawing with finger, sending, and receiving curves (spells) via network using gRPC), pattern matching using Hausdorff metric, OpenCV contours extraction from photo, and attacking towers & spectating other players attacks in real time.

- [Mini Git](https://gist.github.com/dmitrii-artuhov/f7c30137703acb7ca00408be7a3c10e8): one of the 2nd year labs at HSE Spb, I implemented git replica with such functionality: staging files, commiting, logging, branching and checkouting. Implemented resources management according to [git internals specification](https://git-scm.com/book/en/v2/Git-Internals-Plumbing-and-Porcelain) with tree-like files dependencies.

- [Threadpool](https://gist.github.com/dmitrii-artuhov/b6b3b66f99ebb6026451df0255459037): one of the 2nd year labs at HSE Spb which is a custom threadpool implementation with *LightFuture* task-class that allows to register execution of a consequent task after completion of the submitted one.


### 🍋 Javascript

- ❗ [Task Manager](https://github.com/dmitrii-artuhov/TaskManager): a complete Trello clone written in MERN stack (MongoDB, ExpressJS, React, NodeJS) with users authentication, boards management, invitation system, and ability for multiple clients to work simultaneously on a shared board. Since Heroku shut down their free hosting plan, the application is not online. When I have the mood, I rehost it somewhere else...

- [Movie Telegram Bot](https://github.com/dmitrii-artuhov/telegram-bot): a simple telegram bot that uses IMDB API for searching movies info. I also implemented watchlist functionality using MongoDB: user can save movies they like for later reference.  


### 🐍 Python

- [Pushdown Automata](https://github.com/Giga-Chad-LLC/pushdown-automata): a formal languages course team project for 2nd year at HSE SPb. Its goal is to implement pushdown automata with other various components such as context-free grammar syntax, grammar lexer and parser, and grammar conversion algorithm. My part was the implementation of algorithm that converts initial arbitrary context-free grammar into [Greibah Weak Form](https://neerc.ifmo.ru/wiki/index.php?title=%D0%9F%D1%80%D0%B8%D0%B2%D0%B5%D0%B4%D0%B5%D0%BD%D0%B8%D0%B5_%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B0%D1%82%D0%B8%D0%BA%D0%B8_%D0%BA_%D0%BE%D1%81%D0%BB%D0%B0%D0%B1%D0%BB%D0%B5%D0%BD%D0%BD%D0%BE%D0%B9_%D0%BD%D0%BE%D1%80%D0%BC%D0%B0%D0%BB%D1%8C%D0%BD%D0%BE%D0%B9_%D1%84%D0%BE%D1%80%D0%BC%D0%B5_%D0%93%D1%80%D0%B5%D0%B9%D0%B1%D0%B0%D1%85) and testing.

- ❗ [MarioDQN](https://github.com/Adore-Coding-Powerfully/MarioDQN): a team (of 5 people) project that won 1st place in the competition of the HSE School of Practical Programming and Data Analysis with the support of JetBrains. It was high school boot-camp aimed to give basic knowledge of Data Analysis & ML to the students. I have studied the basics of neural networks and reinforcement learning algorithms from scratch, implemented the final version of the Deep Q Learning algorithm for agent training (Mario). The results of Mario's progress through the level can be seen in the repo. Also we created a [**habr post**](https://habr.com/ru/companies/hsespb/articles/563118/) about our project.
