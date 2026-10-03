# Smart Traffic-Aware Navigation System (STANS)

A map guidance system that helps individuals and businesses navigate efficiently by calculating optimal routes based on traffic conditions, blockades, and distance.

## Project Overview

This system develops a map guidance platform utilizing **Kruskal's algorithm** to compute the minimum spanning tree of a weighted directed graph. Graph weights are determined by distance, traffic intensity, and blockades, providing users with optimal routes they wouldn't know about ahead of time.

## Features

- **Graph Visualization**: Interactive 2D and 3D graph visualization with traffic-aware coloring
- **Algorithm Comparison**: Side-by-side comparison of Kruskal's, Prim's, and Dijkstra's algorithms
- **Route Calculator**: Calculate optimal paths between nodes
- **Graph Builder**: Create custom graphs with nodes, edges, and traffic conditions
- **Graph Templates**: Quick-load common network topologies (Grid, Tree, Complete, Bipartite, Star)
- **Performance Benchmarking**: Measure and compare algorithm execution times
- **Graph Metrics**: Analyze degree distribution, clustering coefficient, and betweenness centrality
- **Interactive Tutorial**: Step-by-step guide to using the system
- **Import/Export**: Support for JSON and CSV file formats

## Technologies Used

- React + TypeScript
- Vite
- Tailwind CSS
- Three.js (3D Visualization)
- Framer Motion (Animations)
- Recharts (Data Visualization)

-![Alt](https://repobeats.axiom.co/api/embed/a30bbe6fff62957b3cce362eef11556425224647.svg "Repobeats analytics image")



## Demo
https://github.com/user-attachments/assets/316df9d7-7e5a-47f3-9cdd-c0bae09110ae


## Course Information

- **Course**: Data Structures and Algorithms
- **Class**: BSE-3(B)
- **University**: Bahria University, Karachi Campus
- **Course Instructor**: Engr. Majid Kalim
- **Lab Instructor**: Engr. Saniya Sarim

## Getting Started

### Prerequisites
- Docker Engine (v20.10 or higher)
- Node.js (v20 or higher) and npm (for local development without Docker)
- Git

---

### Running via Docker (Recommended)
To run the pre-built, production-ready container from Docker Hub:

1. Pull the official Docker image:
   ```bash
   docker pull bgari133/stans-app:latest
   ```

2. Run the container on port 80:
   ```bash
   docker run -d -p 80:80 --name stans-app --restart=always bgari133/stans-app:latest
   ```

3. Open your browser and navigate to `http://localhost` (or your server's IP address).

---

### Local Development
To run the application locally using Node.js:

1. Clone the repository:
   ```bash
   git clone https://github.com/Bgari133/STANS.git
   cd STANS
   ```

2. Install dependencies:
   ```bash
   npm ci
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

---

### Building the Image Locally
To build and execute the Docker image locally from source:

1. Build the Docker image:
   ```bash
   docker build -t stans-app:local .
   ```

2. Run the container:
   ```bash
   docker run -d -p 80:80 --name stans-app-local stans-app:local
   ```

---

## License

This project is developed as part of the Data Structures and Algorithms course at Bahria University.
