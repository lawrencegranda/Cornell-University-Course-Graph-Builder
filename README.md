# Cornell Univeristy Course Prerequisite Graph Builder

## Overview
The Course Prerequisite Graph Builder is a tool designed to extract, organize, and visualize prerequisite relationships between courses offered by Cornell University. The project aims to create a structured graph representing the prerequisites required for different courses, facilitating better understanding and planning for students and academic advisors.

## Features
- **Course Information Extraction:** Utilizes web scraping techniques to extract course details such as department, course number, semesters offered, and prerequisites from university course rosters.
- **Graph Construction:** Constructs a directed graph where nodes represent individual courses, and edges signify prerequisite relationships between courses.
- **Visualization:** Provides a visual representation of the course graph, distinguishing courses based on the semesters they are offered.
- **Filtered Course Lists:** Generates filtered course lists based on specified semesters and departments, aiding in the identification of relevant courses for academic planning.

## Functionality
- **Data Collection:** The system collects course information by parsing HTML content from university course roster web pages using web scraping libraries like BeautifulSoup.
- **Graph Generation:** It utilizes extracted course information to build a graph structure representing the relationships between courses and their prerequisites.
- **Filtered Course Lists:** Allows users to specify semesters and departments, providing filtered course lists meeting the specified criteria.

## Purpose
- **Student Planning:** Helps students plan their academic path by visualizing the prerequisites required for different courses, assisting in selecting suitable classes each semester.
- **Advisor Assistance:** Supports academic advisors in guiding students by presenting clear prerequisite relationships, aiding in curriculum planning.
- **Cornell University:** Provides a structured representation of course prerequisites for universities, assisting in curriculum development and review.

## Technologies Used
- Python
- Requests library for HTTP requests
- BeautifulSoup for web scraping
- Regular Expressions (Regex)
- Graph Visualization Tools ([Graphviz](https://edotor.net/?engine=dot?engine=dot?engine=dot?engine=dot?engine=dot?engine=dot#digraph%20G%20%7B%0Agraph%20%5Bpad%3D%220%22%2C%20nodesep%3D%220.15%22%2C%20ranksep%3D%221%22%5D%3B%0Aoverlap%20%3D%20false%3B%0Asplines%20%3D%20true%3B%0A%0A%22CS%201110%22%0A%22MATH%201910%22%20-%3E%20%22CS%201112%22%0A%22MATH%201110%22%20-%3E%20%22CS%201112%22%0A%22CS%202024%22%0A%22CS%201112%22%20-%3E%20%22CS%202110%22%0A%22CS%201110%22%20-%3E%20%22CS%202110%22%0A%22CS%201110%22%20-%3E%20%22CS%202112%22%0A%22CS%202800%22%0A%22CS%202800%22%20-%3E%20%22CS%203110%22%0A%22CS%202110%22%20-%3E%20%22CS%203110%22%0A%22CS%202024%22%20-%3E%20%22CS%203410%22%0A%22CS%202110%22%20-%3E%20%22CS%203410%22%0A%22ECE%202300%22%20-%3E%20%22CS%203420%22%0A%22ENGRD%202140%22%20-%3E%20%22CS%203420%22%0A%22ECE%202400%22%20-%3E%20%22CS%203420%22%0A%22ENGRD%202300%22%20-%3E%20%22CS%203420%22%0A%22CS%203420%22%20-%3E%20%22CS%204410%22%0A%22CS%203410%22%20-%3E%20%22CS%204410%22%0A%22ECE%202400%22%20-%3E%20%22CS%204414%22%0A%22CS%203410%22%20-%3E%20%22CS%204414%22%0A%22CS%202110%22%20-%3E%20%22CS%204414%22%0A%22CS%202800%22%20-%3E%20%22CS%204820%22%0A%22CS%203110%22%20-%3E%20%22CS%204820%22%0A%22CS%201112%22%20-%3E%20%22ECE%202300%22%0A%22CS%201110%22%20-%3E%20%22ECE%202300%22%0A%22CS%201112%22%20-%3E%20%22ECE%202400%22%0A%22CS%201110%22%20-%3E%20%22ECE%202400%22%0A%22CS%201112%22%20-%3E%20%22ENGRD%202140%22%0A%22CS%201110%22%20-%3E%20%22ENGRD%202140%22%0A%22CS%201112%22%20-%3E%20%22ENGRD%202300%22%0A%22CS%201110%22%20-%3E%20%22ENGRD%202300%22%0A%22MATH%201106%22%0A%22MATH%201110%22%0A%22MATH%201110%22%20-%3E%20%22MATH%201120%22%0A%22MATH%201106%22%20-%3E%20%22MATH%201120%22%0A%22MATH%201910%22%0A%22MATH%201910%22%20-%3E%20%22MATH%201920%22%0A%22MATH%201120%22%20-%3E%20%22MATH%202210%22%0A%22MATH%201110%22%20-%3E%20%22MATH%202210%22%0A%22MATH%201920%22%20-%3E%20%22MATH%202940%22%0A%7D))

## Author Information  
**Author**: Lawrence Granda  
**Institution**: Cornell University  
**Email**: lg626@cornell.edu  
**Course**: ORIE 4999: First year course and education analytics team  
**Advisor**: Dr. David Alan Goldberg
