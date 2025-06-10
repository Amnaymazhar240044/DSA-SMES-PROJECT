# DSA-SMES-PROJECT
About The Project
This project is a console-based application built in C++ that simulates a basic voting system. It allows users to register as voters, securely log in, cast votes for pre-defined candidates, and manage their vote within a short time window. An administrative panel provides oversight, enabling viewing of voter details and real-time election results.

The system emphasizes the practical application of fundamental data structures and algorithms, ensuring data persistence across program executions by utilizing text files.

Features
Voter Management: Register new voters with ID, name, and age (18+ requirement).
Secure User Login: Voters authenticate using their ID, first name, and last name.
Vote Casting: Voters can cast their ballot for a chosen candidate within a 15-second time limit.
Vote Cancellation: An option to retract a vote within 1 minute of casting it.
Admin Panel: Access to an administrator interface for viewing:
All registered voters and their voting status.
The list of available candidates.
Real-time election results and the winning candidate.
Data Persistence: All voter and vote data is automatically saved to and loaded from local text files (voters.txt, votes.txt).
Core Data Structures & Algorithms
This project primarily utilizes the following standard C++ data structures:

std::vector (Dynamic Array): Employed for flexible storage and management of voter records and candidate names.
std::map (Key-Value Store): Used to efficiently track and update vote counts for each candidate.
QuickSort Algorithm: Implemented to sort voter records by ID, enhancing data organization and laying groundwork for potential search optimizations.
How to Run Locally
To get the voting system up and running on your machine:

Prerequisites: Ensure you have a C++ compiler (e.g., VISIUAL STUDIO , DEV C++) installed.

Clone the Repository:


Compile the Source Code:



Admin Credentials
For accessing the Admin Panel:
Username: admin
Password: admin123


Project Structure
CPPVotingSystem/
├── src/
│   └── main.cpp             # Main source code
├── data/
│   ├── voters.txt           # Persistent storage for voter information
│   └── votes.txt            # Persistent storage for vote counts
├── .gitignore               # Files/folders to be ignored by Git
└── README.md                # Project overview and instructions
