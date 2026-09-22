# 🚦 Seoul Traffic Viewer

## Team Information

**Course:** Object-Oriented Programming (OOP)

**Project Name:** Seoul Traffic Viewer

**Team Members:**

* Member 1
* Member 2
* Member 3
* Member 4
* Member 5

---

## Project Overview

Seoul Traffic Viewer is an application that visualizes traffic congestion information in Seoul. The system allows users to view traffic conditions on a map, select specific districts, and check congestion levels through an intuitive color-based interface.

This project is designed to demonstrate the application of Object-Oriented Programming principles, including class design, encapsulation, abstraction, and responsibility separation.

---

## Problem Statement

Traffic congestion is a common issue in large cities such as Seoul. Drivers and commuters often need quick access to traffic information in different districts. However, traffic data can be difficult to interpret when presented only as text.

This project provides a simple visual solution by displaying congestion levels on a map using color indicators.

---

## Project Objectives

* Visualize traffic congestion information in Seoul.
* Allow users to select districts and view traffic details.
* Provide an easy-to-understand color-based traffic status system.
* Demonstrate Object-Oriented Programming concepts through practical implementation.

---

## Main Features

### 1. Seoul Map Display

Display a map of Seoul for traffic visualization.

### 2. Traffic Congestion Visualization

Traffic conditions are represented using colors:

| Color     | Status            |
| --------- | ----------------- |
| 🟢 Green  | Low Congestion    |
| 🟡 Yellow | Medium Congestion |
| 🔴 Red    | High Congestion   |

### 3. District Selection

Users can select districts such as:

* Gangnam
* Songpa
* Jongno
* Mapo
* Yongsan

### 4. Traffic Information View

Display traffic information for the selected district.

### 5. Data Refresh

Users can refresh traffic information to view updated data.

---

## System Architecture

### TrafficData

**Attributes**

* congestionLevel
* district
* updateTime

**Responsibility**

* Store traffic information for a district.

---

### TrafficAPI

**Methods**

* getTrafficData()

**Responsibility**

* Retrieve traffic information from a data source.

---

### MapManager

**Methods**

* displayMap()

**Responsibility**

* Display map information and visualize congestion levels.

---

### User

**Methods**

* selectDistrict()

**Responsibility**

* Handle user interactions and district selection.

---

### MainApp

**Methods**

* run()

**Responsibility**

* Control overall program execution.

---

## UML Class Structure

```text
+------------+
|    User    |
+------------+
      |
      v
+------------+
|  MainApp   |
+------------+
   /      \
  v        v
+-----------+     +------------+
| TrafficAPI|     | MapManager |
+-----------+     +------------+
        |
        v
+--------------+
| TrafficData  |
+--------------+
```

---

## OOP Concepts Applied

### Encapsulation

Each class manages its own data and behavior.

### Abstraction

Complex traffic data handling is hidden behind dedicated methods.

### Modularity

Each class has a specific responsibility.

### Reusability

Classes can be extended and reused in future versions.

---

## Expected Outcomes

* A functional traffic visualization application.
* Easy district-based traffic monitoring.
* Clear demonstration of OOP principles.
* Improved understanding of software design and class interaction.

---

## Development Schedule

| Week   | Task                            |
| ------ | ------------------------------- |
| Week 1 | Project Planning & Class Design |
| Week 2 | Core Class Implementation       |
| Week 3 | UI Development & Integration    |
| Week 4 | Testing & Final Presentation    |

---

## Future Improvements

* Real-time traffic API integration
* Route recommendation system
* Traffic history analysis
* Mobile application support
* Traffic prediction using machine learning

---

## Technologies

* Python
* Object-Oriented Programming (OOP)
* Tkinter / GUI
* Git & GitHub


