# Portfolio
Scott Masciulli 
# CS 230 Portfolio Reflection: The Gaming Room

## Project Summary

The client for this project was The Gaming Room, a company that wanted to expand its existing Android game, *Draw It or Lose It*, into a web-based application that could run across multiple platforms, including Windows, macOS, Linux, Android, and iOS. The application needed to support multiple teams and players while maintaining a consistent game experience. Important requirements included allowing multiple users to play simultaneously, ensuring that game names were unique, and maintaining unique identifiers for games, teams, and players. The design also needed to consider security, scalability, memory management, and the best architecture for supporting multiple platforms.

## What I Did Well

I think I did particularly well at organizing the software design document and explaining the technical decisions in a way that could be understood by both developers and the client. I evaluated different operating platforms and considered the advantages and disadvantages of each option. I also focused on important design patterns, including the Singleton pattern for managing the game service and an entity-based structure for organizing games, teams, and players. These decisions helped create a clear plan for developing an application that could grow and support multiple users.

## What I Found Helpful About the Design Process

Working through the design document helped me understand the importance of planning before writing code. By identifying the requirements, constraints, and system architecture early, I had a clearer idea of how the different parts of the application needed to work together. Creating the design first also helped me think about potential problems, such as duplicate game names, managing multiple players, and supporting different operating platforms. This process made the coding stage more organized because I had a plan to follow instead of trying to solve every problem as it appeared.

## What I Would Revise

If I could revise one part of my work, I would improve the explanation of how the application's components communicate and manage multiple simultaneous game sessions. I would include more detailed examples and diagrams showing how the game service interacts with games, teams, and players. I would also explain more clearly how the application could handle increased traffic as more users join. These improvements would make the design easier for developers to follow and provide a clearer picture of how the application would work in a real-world environment.

## Interpreting and Implementing User Needs

I interpreted The Gaming Room's needs by focusing on its goal of expanding *Draw It or Lose It* beyond Android while maintaining a consistent experience for users on different devices. I considered a web-based, client-server approach because it would allow players to access the game through compatible web browsers without requiring a separate native application for every operating system. I also incorporated requirements for unique game names and identifiers, along with a structure for organizing teams and players. Considering user needs is important because the software must solve the client's actual problems rather than simply function from a technical perspective. A successful application should be reliable, accessible, secure, and easy to use.

## My Approach to Software Design

My approach to software design starts with understanding the problem, identifying the client's requirements, and determining the system's constraints before choosing an architecture. I then break the application into smaller components, consider which design patterns would be useful, and evaluate the available technologies. For future projects, I would continue using techniques such as requirements analysis, UML diagrams, object-oriented design, and evaluating platform advantages and disadvantages. I would also use prototypes and testing earlier in the process to identify potential issues before they become more difficult to fix. As I continue developing my software engineering skills, I want to improve my ability to design applications that are maintainable, scalable, secure, and focused on the needs of their users.
