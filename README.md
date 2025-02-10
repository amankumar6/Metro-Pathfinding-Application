# Metro-Pathfinding-Application(Java)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)  ## Overview

This Java application provides a route planning tool for the Hyderabad Metro, allowing users to find the shortest paths (based on distance or travel time) between stations. It utilizes Dijkstra's algorithm to efficiently calculate optimal routes and considers interchanges between different metro lines.

## Features

*   **Shortest Path Calculation:** Finds the shortest path between any two stations in the Hyderabad Metro network.
*   **Distance and Time-Based Routing:**  Calculates routes based on either distance or estimated travel time.
*   **Interchange Handling:**  Considers interchanges between metro lines and incorporates them into route calculations.
*   **User-Friendly Interface:**  (Describe your UI - command-line, GUI, etc.)  Example: "Provides a simple command-line interface for inputting source and destination stations."
*   **(Optional) Map Integration:** (If you have it) "Integrates with [Map Library Name] to display the metro network and calculated routes visually."
*   **(Optional) Real-World Data:** (If you have it) "Uses real-world data for distances and travel times, sourced from [Source of Data]."

## Technologies Used

*   Java
*   Dijkstra's Algorithm
*   Data Structures: HashMaps, Priority Queues/Heaps
*   (Optional) [JSON Library Name]: For parsing metro data (if applicable)
*   (Optional) [GUI Library Name]: For the graphical user interface (if applicable)
*   (Optional) [Map Library Name]: For map integration (if applicable)

## Getting Started

1.  **Prerequisites:**
    *   Java JDK 8 or higher installed.
    *   (Optional) [Build Tool Name] (Maven or Gradle) installed.

2.  **Clone the Repository:**
    ```bash
    git clone git@github.com:amankumar6/Metro-Pathfinding-Application.git
    ```

3.  **Run the Application:**
    ```bash
    java Main  Graph_M
    ```

## Usage

1.  (Describe how to use your application.  Provide examples of input and output.)
    Example:
    ```
    Enter source station: Paradise
    Enter destination station: MG Road
    Shortest path: Paradise -> Secunderabad -> Ameerpet -> MG Road
    Distance: 12.5 km
    Time: 20 minutes
    ```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.