🚨 Disaster Response Simulator
A C++ project that simulates natural disaster events like Earthquakes, Floods, and Fires using Object-Oriented Programming (OOP). This simulator allows users to create disasters, simulate responses with appropriate response units, handle exceptions, and log all actions to files.

📁 Project Structure
css
Copy
Edit
DisasterResponseSimulator/
├── include/
│   └── DisasterSimulator.h
├── src/
│   └── DisasterSimulator.cpp
├── main.cpp
├── log.txt
├── disasters.txt
├── report/
│   └── DisasterResponseReport.pdf
│   └── UML_Diagram.png
└── README.md
🛠️ Features
✅ Implements Inheritance, Polymorphism, Abstraction, and Encapsulation

✅ Abstract class Disaster with virtual function

✅ Derived classes: Earthquake, Flood, and Fire

✅ Central SimulationManager to handle disasters

✅ Exception handling for file and input errors

✅ File I/O for disaster logs and records

✅ Clean console-based UI for interaction

🔧 How to Compile and Run
Using Visual Studio (Windows)
Open Visual Studio.

Create a new C++ project.

Add main.cpp, DisasterSimulator.h, and DisasterSimulator.cpp to your project.

Make sure to set the language standard to C++14 or higher.

Build and run.

Using g++ (Linux/macOS/Windows WSL)
bash
Copy
Edit
g++ -std=c++14 -o simulator main.cpp src/DisasterSimulator.cpp
./simulator
💻 Sample Output
pgsql
Copy
Edit
--- Disaster Simulator ---
1. Create Disaster
2. Run Simulation
3. View Logs
4. Exit

Select an option: 1
Enter type (1: Earthquake, 2: Flood, 3: Fire): 2
Enter location: Riverside
Enter severity (1-10): 7
Enter time (HH:MM): 15:45

Disaster created successfully!

--- Running Simulation ---
[Flood] - Location: Riverside, Severity: 7, Time: 15:45
Response Team Deployed: Rescue boats, Medical Units, Emergency Teams
📂 Files Used
log.txt: Stores simulation logs

disasters.txt: Stores disaster information entered by user

📘 OOP Concepts Demonstrated
Principle	Implementation
Abstraction	Disaster as abstract class
Inheritance	Derived disaster types from Disaster
Polymorphism	simulateResponse() overridden in child classes
Encapsulation	Private member variables

🧪 Requirements
C++14 or higher

Console I/O

File read/write permissions

📜 License
This project is intended for academic use in learning Object-Oriented Programming (OOP) with C++.

