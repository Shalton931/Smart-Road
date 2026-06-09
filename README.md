<div align="center">
  
  <img src="https://img.shields.io/badge/version-1.0.0-blue.svg" alt="Version">
  <img src="https://img.shields.io/badge/license-MIT-green.svg" alt="License">
  <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg" alt="PRs Welcome">
  <img src="https://img.shields.io/badge/TypeScript-007ACC?logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB" alt="React">
  <img src="https://img.shields.io/badge/Node.js-43853D?logo=node.js&logoColor=white" alt="Node.js">
  
  <h1>SmartRoad</h1>
  <h3>AI-Powered Pothole Detection & Municipal Maintenance System</h3>
  
  <p>
    <strong>Advanced Algorithms | Real-Time Processing | Intelligent Routing</strong>
  </p>
  
  <p>
    <a href="#demo">View Demo</a> •
    <a href="#features">Features</a> •
    <a href="#algorithms">Algorithms</a> •
    <a href="#quick-start">Quick Start</a> •
    <a href="#api">API</a> •
    <a href="#architecture">Architecture</a>
  </p>
</div>

---

##  Demo Screenshots

<div align="center">
  <table>
    <tr>
      <td><img src="https://via.placeholder.com/400x250?text=Citizen+Dashboard" alt="Citizen Dashboard"></td>
      <td><img src="https://via.placeholder.com/400x250?text=Municipality+Dashboard" alt="Municipality Dashboard"></td>
    </tr>
    <tr>
      <td><em>Citizen Report Submission</em></td>
      <td><em>Municipality Priority Queue</em></td>
    </tr>
    <tr>
      <td><img src="https://via.placeholder.com/400x250?text=Route+Optimization" alt="Route Optimization"></td>
      <td><img src="https://via.placeholder.com/400x250?text=Analytics+Dashboard" alt="Analytics Dashboard"></td>
    </tr>
    <tr>
      <td><em>Optimized Maintenance Routes</em></td>
      <td><em>Real-Time Analytics</em></td>
    </tr>
  </table>
</div>

---

##  Problem Statement

Municipalities worldwide face four critical challenges in road maintenance:

1. **Duplicate Reports** - Multiple citizens report the same pothole, wasting resources
2. **Subjective Prioritization** - Inconsistent severity assessment across inspectors
3. **Inefficient Routing** - Maintenance crews follow arbitrary routes, wasting fuel and time
4. **Limited Visualization** - Poor geographical context for decision-making

**SmartRoad solves these challenges using advanced algorithms and real-time processing.**

---

##  Features

###  Core Functionality

| Feature | Description | Technology |
|---------|-------------|------------|
| **Duplicate Detection** | Automatically identifies duplicate pothole reports | Perceptual Hashing + DCT |
| **Severity Classification** | ML-based severity assessment (Low → Critical) | K-Means Clustering |
| **Route Optimization** | Optimal path planning for maintenance crews | A* + Dijkstra + TSP |
| **Real-Time Maps** | Interactive visualization of pothole locations | Leaflet + OpenStreetMap |
| **Priority Queue** | Dynamic task scheduling based on severity | Binary Heap |
| **Spatial Indexing** | Fast nearby report queries | KD-Tree |

###  User Portals

**Citizen Portal**
-  Upload pothole images with location
-  Real-time duplicate detection
-  Interactive map of nearby potholes
-  Track report status
-  Mobile-responsive design

**Municipality Portal**
-  Real-time analytics dashboard
-  Priority-based task queue
-  Route optimization with turn-by-turn
-  Severity distribution charts
-  Status management (Pending → Completed)

###  Technical Features

-  **JWT Authentication** with role-based access
-  **WebSocket** real-time updates
-  **PostgreSQL** with Prisma ORM
-  **Docker** containerization
-  **Rate limiting** & security headers
-  **TypeScript** full type safety

---
