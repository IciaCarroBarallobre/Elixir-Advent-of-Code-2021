# Elixir-Advent-of-Code 🤶

Hey! Will try to solve advent of code (AOC) using Elixir 💧 &amp; Livebook 📚. 

📅 Advent of Code (AOC) is an Advent calendar of **small programming puzzles** for a variety of skill sets and skill levels that can be solved in any programming language you like.

**Index**
* [Project Installation](#project-installation)
* [Project Structure](#project-structure)

## Project Installation 

📚 If you want to use Livebook: 

* Step 1: Install and configure Git with GitHub: ([What is Git and GitHub?](#what-is-git-and-github))
* Step 2: Install Elixir: ([What is Elixir?](#what-is-elixir)).
* Step 3: Install Livebook ([What is Livebook?](#what-is-livebook))
* Step 4: Fork this GitHub Repo.
  * [How to fork a repo...](https://docs.github.com/es/get-started/quickstart/fork-a-repo)
* Step 5: Download the project with GitHub Desktop, by https or by ssh. For example with https:

```shell
git clone https://github.com/IciaCarroBarallobre/Elixir-Advent-of-Code.git
```

* Step 6: Initiallizate Livebook and search the file: AdventOfCode.livemd
  
💧 Although we are going to use Livebook, we are going to share the solution in a elixir file too.

## Project Structure

```vim

|   README.md             <-- This file: Introduction and abstract of the project, include a installation links and steps.
|   AdventOfCode.livemd   <-- AOC abstracts and links to the different puzzles.
|   .gitignore            <-- File placed in the repository that tells git not to track certain files.
|   
\---Puzzles
    +---Day1              <-- Include Livebook and Elixir statement and solution for day 1 puzzle.
    |       Day1.ex
    |       Day1.livemd
    ...    
    |
    |       
    \---DayX
```

(Made with: `tree /f /a > tree.txt`)

## More info

### What is Elixir?

Elixir is a dynamic, functional language for building scalable and maintainable applications.
It runs on the Erlang VM, known for creating low-latency, distributed, and fault-tolerant systems.

[Install path](https://elixir-lang.org/install.html)

### What is LiveBook?

Livebook allows you to write interactive & collaborative code notebooks in Elixir.

Some useful features:

* Interactive documents: Notebooks are documents that mix text, code, and rich output. Share knowledge, explore code, and visualize data using tables, charts, maps, and much more!
* Collaborate as a team: Write code, analyze results, and document your findings together, in realtime.

[Install path](https://livebook.dev/#install)

### What is Git and GitHub?

**GIT:** Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency. 
[Install path](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)

**GITHUB:** GitHub is an Internet hosting service for software development and version control using Git.
[How to configure GitHub](https://docs.github.com/en/get-started/quickstart/set-up-git)
