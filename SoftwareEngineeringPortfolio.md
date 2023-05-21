# Project Portfolio

## Platform for Health Tech

I worked in a team of six developers to develop a system for our client in the IFLS  (Institute for Life Sciences) of the University of Southampton.

Our client wanted a system that can matchmake Clinicians with Technologists, who both work in different domains and so had problems understanding each other. Previously, they used to run workshops that allowed for inter-departmental colloboration, but the Covid pandemic exposed the need for a scalable, online solution. 

Our final solution was inspired by social media networks like Facebook but tailored towards medical and technical professionals.

### Solution
* A web app for virtual networking and problem resolution, that should be intuitive and easy to use.
* The system allows users to create posts, through which they can describe a problem, ask for help, or simply share an idea or project they are currently working on.
* It matchmakes Clinicians and Technologists by recommending relevant posts to them.
* Users can interact with each other - so we included liking and commenting features.

![](Images/MatchMaking.gif)


### Technology Stack
* **Front End:** React framework, with libraries such as Redux and Formik for state management and form validation, respectively.
* **Back End:** Express framework, with libraries such as Knex and Cloudinary for query building and image storage, respectively.
* We created a REST API for communication between the client and the server.
* For the database, we used PostgreSQL as it is feature-rich and our group has experience with it.
* We hosted our application on Microsoft Azure using a University-provided subscription.

![](Images/TechStack.png)

## Simulating the Social Exchange Theory
[https://github.com/kimathinyota/social-group-simulator](https://github.com/kimathinyota/social-group-simulator) 

* This project involves simulating people, as intelligent agents, interacting
with each other in a social environment and finding emergent social phenomena. 
* This
environment will take the form of a game, where the agents can use their skills to compete
for gold and their decisions will be influenced by their assigned personality and skill level.
* These agents are given the options to mentor, steal from, help and befriend another agent, and this decision will be influenced by the agent’s personality and skill level.
* An experiment was designed for the purpose of finding combination of agents that corresponds with greater social phenomena.

### Solution
Below shows the simulation running for 12 agents in a limited-resource environment
![](Images/Simulation.gif)

### Technology Stack
* Python graphics.py module for displaying the simulation
* Python Threading module allowing each Agent to occupy a seperate thread from each other and their environment.
* Python networkx for constructing graphs/networks of Agent interactions and for calculating point centrality
* Python numpy to represent Q-matrix for the purpose of applying reinforcement learning to agents
* MySQL database and SQL for storing and processing experimental data



## NoteBankFX: Note-Taking Software
[https://github.com/kimathinyota/NoteBankFX](https://github.com/kimathinyota/social-group-simulator)
* I built a system in Java to help me study for exams. 
* The system lets users store, view, create and study notes
* Users can group notes into collections called Ideas under a statement, question or set of keywords.
* Users can generate quizzes to study notes by picking a specific collection of ideas
* Users can generate study plans, where a user can enter the topic and the date of an upcoming exam and it would automatically generate hourly/daily quizzes for studying.

### Solution
#### Creating and Viewing Notes
![](Images/NoteBankFX/CreatingViewingNotes.gif)

#### Creating and Viewing Ideas
![](Images/NoteBankFX/ViewingCreatingIdea.gif)

#### Creating and Completing Quizzes
![](Images/NoteBankFX/CreatingCompletingQuiz.gif)

#### Creating and Completing Study Sessions
![](Images/NoteBankFX/CreatingDoingStudySession.gif)

### Technology Stack
Used MVC (Model, View, Controller) architecture to develop this program.
* **View**: UI created using JavaFX via FXML and CSS
* **Model**: Used XML and file system for data storage
* **Controller**: Java/JavaFX


## Programming Language and Compiler
[https://github.com/kimathinyota/PLC](https://github.com/kimathinyota/social-group-simulator)

* I worked in a pair to design a programming language specialising in integer stream manipulation. 
* The language was functional and supported recursion and the following data structures: lists, strings and integers. 
* It read in integer streams from stdin, it provided functions for writing onto stdout and any errors were outputted on stderr


### Solution
* SPL is a domain specific language used to process (potentially multiple) streams. 
* SPL programs will output results as the input is being processed meaning that unbounded strings can be handled. 
* The language is mainly built around the process stream function with other functions being mostly used as parameters for the process stream function.


### Technology Stack
* Used Happy (Haskell) for parsing and constructing the grammar: https://www.haskell.org/happy/
* Used Alex (Haskell) to generate lexical analyser: https://www.haskell.org/alex/
* Standard Haskell for the rest of the project


## Recommender System
[https://github.com/kimathinyota/RecommenderSystem](https://github.com/kimathinyota/social-group-simulator)

I worked in a pair to create an Item Based Collaborative Filtering Recommender System.

### Solution
Given a large data set of user ratings on item, our system was developed to predict the ratings of users on items they haven't yet rated.
Our system took several parameters, and we developed an experiment to find the optimal parameter configuration for our recommender system.


### Technology Stack
* SQL and MySQL database for faster processing of given CSV data files
* Code written in Java









