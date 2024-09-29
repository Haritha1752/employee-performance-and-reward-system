# Employee Performance and Rewarding System

### Project Overview
The **Employee Performance and Rewarding System** is designed to streamline and enhance the process of evaluating employee performance and distributing rewards. By integrating SQL, NoSQL (MongoDB), and Python, this system provides a comprehensive platform for managing employee data, performance metrics, and reward distribution. This project addresses the need for data-driven, fair, and efficient employee evaluation methods, ultimately fostering a motivated and high-performing workforce.

### Table of Contents
1. [Introduction](#introduction)
2. [Objectives](#objectives)
3. [Database Design](#database-design)
4. [Technologies Used](#technologies-used)
5. [Conclusion](#conclusion)

---

### Introduction
In today's corporate environment, recognizing employee achievements is often inconsistent and inefficient. This project aims to address these issues by creating a system that simplifies the process of evaluating performance and distributing rewards. The system stores information on employee goals, performance scores, rewards, and qualifications, enabling transparent and fair performance reviews.

The system categorizes rewards into **monetary** and **non-monetary** types, ensuring appropriate recognition for various achievements. Additionally, the system tracks employee leaves and project assignments, providing a comprehensive view of employee performance.

---

### Objectives
The primary goals of this project include:
- **Data Management**: Store and manage employee information, including performance scores, qualifications, leave details, and rewards.
- **Reward Distribution**: Assign monetary and non-monetary rewards based on employee performance.
- **Performance Evaluation**: Facilitate the comparison of employee goals and scores for evaluation purposes.
- **Integration**: Use MySQL and MongoDB for data storage, with Python for query execution and visualization.

---

### Database Design
The database was modeled using a relational structure in MySQL and a document-based structure in MongoDB. Key entities include:
- **Employee**: Stores employee details such as ID, name, and job title.
- **Performance**: Stores performance scores and related data.
- **Goal**: Contains data on employee targets and deadlines.
- **Leave**: Records the details of employee leaves.
- **Reward**: Stores details about monetary and non-monetary rewards.

---

### Technologies Used
- **MySQL**: Relational database for storing structured data.
- **MongoDB**: NoSQL database for unstructured or semi-structured data.
- **Python**: Used for executing queries and generating visualizations.
- **SQLAlchemy**: Python library for connecting to MySQL databases.
- **Matplotlib**: Used for data visualization.

---

### Conclusion
The **Employee Performance and Rewarding System** successfully provides a robust platform for managing employee data, evaluating performance, and distributing rewards. By integrating SQL for relational data, MongoDB for NoSQL, and Python for data analysis and visualization, the system enhances organizational efficiency and ensures fairness in performance evaluation. The combination of these technologies helps streamline the process of recognizing employee contributions, improving overall morale, job satisfaction, and retention.

