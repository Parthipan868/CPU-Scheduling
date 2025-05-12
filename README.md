CPU SCHEDULING ALGORITHM STIMULATOR


Description
This is an interactive web-based simulator for visualizing and comparing different CPU scheduling algorithms used in operating systems. The application allows users to input process details (arrival time, burst time, and priority) and simulate the execution of various scheduling algorithms, displaying results through a Gantt chart and performance metrics.
Features

Supports five CPU scheduling algorithms:
First Come First Serve (FCFS)
Shortest Job First (SJF)
Shortest Remaining Time First (SRTF)
Round Robin (RR)
Priority Scheduling


Interactive process management: add, remove, and edit processes.
Visual Gantt chart to display process execution timeline.
Detailed results table showing completion, waiting, turnaround, and response times.
Summary metrics for average waiting, turnaround, and response times.
Responsive design with a clean and modern UI.
Input validation to ensure valid process parameters.

Technologies Used

HTML5: For the structure of the web application.
CSS3: For styling, including custom variables and responsive design.
JavaScript: For implementing the scheduling algorithms and dynamic UI updates.

Installation
Clone the repository:git clone https://github.com/your-username/cpu-scheduling-algorithms.git


Navigate to the project directory:cd cpu-scheduling-algorithms

Open the index.html file in a web browser:
You can double-click the index.html file, or
Use a local server (e.g., with VS Code's Live Server extension or Python's HTTP server):python -m http.server 8000

Then, navigate to http://localhost:8000 in your browser.

Usage

Open the application in a web browser.
Select a scheduling algorithm from the buttons at the top (e.g., FCFS, SJF).
Add or remove processes using the "Add Process" and "Remove" buttons.
Edit process details in the table:
Arrival Time: When the process arrives (non-negative integer).
Burst Time: CPU time required (positive integer).
Priority: Priority level for Priority Scheduling (positive integer, lower number means higher priority).


For Round Robin, set the time quantum in the input field.
Click "Run Algorithm" to simulate the selected algorithm.
View the Gantt chart and results table to analyze the scheduling outcome.


Contributing
Contributions are welcome! Please follow these steps:

Fork the repository.
Create a new branch (git checkout -b feature-branch).
Make your changes and commit (git commit -m "Add feature").
Push to the branch (git push origin feature-branch).
Open a pull request.
