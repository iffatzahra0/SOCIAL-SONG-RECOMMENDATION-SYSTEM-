# 🎵 BFSBEATS – A Social Song Recommendation System

**BFSBEATS** is a **C++ Data Structures & Algorithms project** that simulates a social music recommendation platform.  
The system models users as nodes in a graph and friendships as weighted edges, using classic graph algorithms to recommend songs based on social proximity, preferences, and genre similarity.

---

## 📌 Project Overview

- Users are represented as **nodes**
- Friendships are **bidirectional weighted edges**
- Songs are recommended using:
  - **Breadth-First Search (BFS)**
  - **Depth-First Search (DFS)**
  - **Dijkstra’s Algorithm**
- A **global trending system** ranks songs based on popularity
- Algorithm execution time is measured for performance comparison

---

## ⚙️ Features

### 👥 User & Social Graph Management
- Add new users dynamically
- Create friendships with closeness weights
- Display friend lists and social connections
- Case-insensitive input handling with formatted output

---

### 🎶 Song Interaction System
- Listen to songs (increments play count)
- Like songs (higher recommendation influence)
- Genre-based song categorization
- User listening and liking history tracking

---

## 🔍 Recommendation Algorithms

### 1️⃣ BFS Recommendations
- Recommends songs from nearby friends (hop-based)
- Likes carry more weight than listens
- Best for discovering popular songs among close friends

### 2️⃣ DFS Recommendations
- Explores deeper friendship chains
- Useful for discovering niche or less obvious preferences

### 3️⃣ Dijkstra-Based Recommendations
- Uses friendship weights (closeness)
- Incorporates **genre similarity**
- Influence decreases with social distance
- Produces the most personalized recommendations

---

## 🔥 Global Trending Songs
- Uses a **priority queue**
- Ranks songs based on total likes + plays
- Shows top-N trending tracks across the platform

---

## ⏱ Performance Analysis

- Execution time measured using `std::chrono`
- BFS, DFS, and Dijkstra compared side-by-side
- Demonstrates real-world efficiency differences between algorithms

---

## 🧠 Data Structures Used

- `vector`
- `map`, `unordered_map`
- `queue`
- `stack`
- `priority_queue`
- Graphs implemented via adjacency lists

---

## 🚀 How to Run

- to run code use Microsoft Visual Studio.

## Group Partner
- [Ayesha Ghafoor](https://github.com/ayesha-a-ghafoor)
