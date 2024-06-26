# Unified-Data-Structures-and-Algorithms-Visualizer
Welcome to the Renee's Unified Data Structures and Algorithms Visualiser project! This application serves as a comprehensive tool for visualizing and managing various data structures and algorithms, leveraging Java, Spring Boot, MySQL, and modern web technologies.
Key Features:

Contact Management System:

CRUD Operations: Add, update, delete, and retrieve contacts stored in a MySQL database.
Spring Boot Integration: Efficient backend processing with a RESTful API interface.
Sorting Algorithm Visualizer:

Bubble Sort and Quick Sort: Demonstrates two fundamental sorting algorithms with backend processing and visual output.
Interactive Input: Users can input arrays and view sorted results through intuitive visualizations.
Pathfinding Algorithm Visualizer:

Dijkstra’s and A Algorithms*: Explore two popular pathfinding algorithms with dynamic visualizations on a grid.
Customizable Grid: Users can define grid obstacles and start/end points to see how paths are calculated in real-time.
Binary Search Tree Visualizer:

Tree Operations: Insert, delete, and search nodes in a Binary Search Tree with detailed visual representations.
D3.js Visualizations: Utilizes D3.js to render the tree structure dynamically, providing a clear view of operations and changes.
Technologies Used:

Backend: Java, Spring Boot, Spring Data JPA
Frontend: HTML, CSS, JavaScript, D3.js
Database: MySQL

How to Run:

Clone the repository:

bash
Copy code
git clone https://github.com/your-username/unified-visualizer.git
cd unified-visualizer
Set up the database:

Create a MySQL database named visualizer_db.
Update application.properties with your MySQL username and password.
Build and run the application:

bash
Copy code
./mvnw spring-boot:run
The backend will start on http://localhost:8080.
Access the application:

Open index.html in your web browser to interact with the visualizer.
Usage:

Contact Management: Use the form to add and manage contacts. Click "Load Contacts" to view all saved contacts.
Sorting Algorithms: Enter an array of numbers separated by commas and choose a sorting method to see the sorted output.
Pathfinding: Define grid obstacles, set start and end points, and choose an algorithm to visualize the path.
Binary Search Tree: Insert and delete values to dynamically update and view the tree structure.
Contributions:

Contributions to enhance this project are welcome. Please open issues or submit pull requests with your improvements and suggestions.
