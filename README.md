# Hello World! | Witaj Świecie!  | ¡Hola Mundo!

## Table of Contents

1. [**About Me**](#about-me)
2. [**My Tool Stack**](#my-tool-stack)
    1. [Languages](#languages)
    2. [Database Management Systems](#database-management-systems)
    3. [API Development](#api-development)
    4. [Development Environments](#development-environments)
    5. [AI Tools](#ai-tools)
3. [**My Top 5 Projects**](#my-top-5-projects)
    1. [Microservice-Based Workout Scheduling App Using Evolutionary Computation](#microservice-based-workout-scheduling-app-using-evolutionary-computation-may-2026)
    2. [Music Royalties on Blockchain](#music-royalties-on-blockchain-may-2026)
    3. [Share Trader Desktop Application](#share-trader-desktop-application-april-2026)
    4. [Optimising PID Controllers For Lower-Limb Robots in Python Using a Hybrid Evolutionary Algorithm](#optimising-pid-controllers-for-lower-limb-robots-in-python-using-a-hybrid-evolutionary-algorithm-december-2025)
    5. [Honours Project: Calorie Burnout Scheduler From Exercise Using MAP-Elites](#honours-project-calorie-burnout-scheduler-from-exercise-using-map-elites-april-2025)
4. [**Why Hire Me?**](#why-hire-me)

## About Me

My name is Mateusz and I am Master's graduate in Software Engineering. More personally, I am a passionate programmer who just wants to make computers do cool stuff, informally-speaking. I am most experienced in Python, Java and C# programming languages, among other languages that I am familiar with. My academic interests involve Evolutionary Computation - the field of nature-inspired optimisation founded on survival of the fittest. My Honours Dissertation explored scheduling workout plans by calorie expenditure and deadlines, using the MAP-Elites algorithm, designed and built from a Software Engineering perspective - looking at development process methods, system design, and patterns.

## My Tool Stack

The tool stack tables below reflect on my confidence level, relative to the tool(s) that I am most confident with.

### Languages

| Python | C# | Java | CSS | HTML | PL/SQL | SQL | JavaScript | C++ | Solidity |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| ★★★★★ | ★★★★☆ | ★★★★☆ | ★★★☆☆ | ★★★☆☆ | ★★★☆☆ | ★★★☆☆ | ★★☆☆☆ | ★☆☆☆☆ | ★☆☆☆☆ |

### Database Management Systems

| SQLite | Oracle SQL | MySQL |
|:---:|:---:|:---:|
| ★★★★☆ | ★★★☆☆ | ★★☆☆☆ |

### API Development

| Flask | Postman | FastAPI | ASP.NET |
|:---:|:---:|:---:|:---:|
| ★★★★☆ | ★★★★☆ | ★★★☆☆ | ★☆☆☆☆ |

### Development Environments

| PyCharm |Jupyter Notebook/Lab| DataGrip | IntelliJ IDEA | Rider | Visual Studio | VS Code |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| ★★★★★ | ★★★★★ | ★★★★☆ | ★★★★☆ | ★★★★☆ | ★★★☆☆ | ★★★☆☆ | 

### AI Tools

| Claude | ChatGPT | GitHub Copilot |
|:---:|:---:|:---:|
| ★★★★☆ | ★★★☆☆ | ★★★☆☆ |

## My Top 5 Projects

### [Microservice-Based Workout Scheduling App Using Evolutionary Computation](), May 2026

A Master's group project coursework inspired by my Honours Project, extending the scope of exercise routine optimisation and placing the optimiser on a microservice.

***Note:*** The full implementation resides inside the `develop` branch, and my contributions reside inside the `src/services/ea-service/` directory.

***Complete Tool Stack:***
- Python
- SQLite
- JavaScript
- React
- Firebase
- Flask
- Fast API
- Docker
- Postman


### [Music Royalties on Blockchain](), May 2026

This Cryptography coursework explores the application of blockchain outside of just finance. A model music royalty system has been developed, inspired by Imogen Heap's efforts to publish her music and its royalties on blockchain as it eliminates the involvement of intermediaries, providing her with more control over her songs and making share distribution easier.

***Complete Tool Stack:***
- Python
- Solidity
- Flask
- Postman

### [Share Trader Desktop Application](), April 2026

This was a coursework for Enterprise Computing, which required the development of a share trading system using the Component Based Development approach, undertaking a series of component mining, qualification, categorisation, and adaptation. Each incorporated component was placed inside appropriate microservices to separate their responsibilities from one another.

***Note:*** Last time I attempted to run the application, I experienced bugs. The project's repository still requires execution instructions and Issues of identified bugs. I intend on reviewing and fixing this project this month.

***Complete Tool Stack:***
- Python
- Python Libraries:
  - PyJWT
  - Argon2-cffi
  - Yfinance
  - SQLAlchemy
  - Faker
  - Pandas
  - CustomTkinter
  - Matplotlib
- Docker

### [Optimising PID Controllers For Lower-Limb Robots in Python Using a Hybrid Evolutionary Algorithm](), December 2025

This is more of an inter-disciplinary research coursework, bridging control systems and evolutionary optimisation. This project attempted to model an existing PID optimiser, developed in MATLAB, to Python. The optimiser is a Hybrid GA-PSO - the combination of the Genetic Algorithm with Particle Swarm Optimisation - which performs the search of an optimum in two steps; 1, a global search is performed with GA to find a global optimum; 2, a local search is conducted with PSO to explore that part of the search space further, in search of a local optimum. A major difficulty encountered in this project was computing the objective function, consisting of indefinite integration and Laplace Transforms. The computation complexity reduced the optimiser's performance. As a result, the scope of the project was reduced to simply mimicking the simulation of the transfer functions and plotting them onto a graph.

***Complete Tool Stack:***
- Python
- Python Libraries:
    - DEAP
    - Sympy
    - Numpy
    - Matplotlib
    - PySwarms
- Jupyter Notebooks

### [Honours Project: Calorie Burnout Scheduler From Exercise Using MAP-Elites](), April 2025

My Honours Project focused on exploring workout scheduling methods using Evolutionary Algorithms. In this project, I focused on using MAP-Elites as the algorithm of choice as it illuminates solutions on a heatmap based on their fitness scores and a vector of secondary characteristics used as axes to the heatmap. Due to the weight of necessary research and limited resources, the algorithm optimised mainly for the difference in target and actual weights, computed using calorie expenditure models and MET values, supplied by the Adult Compendium of Physical Activities. The ultimate goal was to build a server-based algorithm, allowing it to be accessed via API, however, due to knowledge gaps, I focused solely on developing the algorithm, running experiments, and producing results.

***Complete Tool Stack:***
- Python
- Python Libraries
  - Pandas
  - Matplotlib
  - Numpy
- Jupyter Notebooks

## What Am I Currently Learning?

- **Django**

## Why Hire Me?

One of my strongest traits is the ability to get up to speed on unfamiliar technologies quickly. During my Cryptography coursework, for instance, I had no prior experience with Solidity, yet within a few weeks I had built a working blockchain-based royalty system. My Honours Project posed a similar challenge: I began with no background in Evolutionary Computation and developed the necessary expertise independently, primarily through academic literature and iterative experimentation. I am motivated as much by problem-solving itself as by any particular type of role, which is why I remain open to a broad range of software engineering positions rather than committing early to a narrow specialism. Whatever the specific demands of a role may be, I am confident in my ability to learn them quickly and apply them effectively.
