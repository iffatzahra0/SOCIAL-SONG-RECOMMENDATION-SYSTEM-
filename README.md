🎵 BFSBEATS – A Social Song Recommendation System

BFSBEATS is a C++ Data Structures & Algorithms project that simulates a social music platform where users discover songs based on their friends’ listening behavior. The system leverages graph traversal and shortest-path algorithms to generate intelligent, personalized recommendations.

📌 Project Overview

Users are represented as nodes in a graph

Friendships act as bidirectional weighted edges (closeness-based)

Songs are recommended using:

BFS (Breadth-First Search) – proximity-based discovery

DFS (Depth-First Search) – deeper social exploration

Dijkstra’s Algorithm – genre similarity + friendship weight optimization

A global trending system ranks songs using likes and play counts

⚙️ Core Features
👥 User & Social Graph Management

Add users dynamically

Create bidirectional friendships with custom closeness weights

View friend lists and user preferences

🎶 Song Interaction System

Listen to songs (increments play count)

Like songs (higher recommendation weight)

Genre-aware song storage

Case-insensitive input handling

🔍 Recommendation Algorithms

BFS Recommendations

Suggests songs from nearby friends (hop-based)

Likes weighted more than listens

DFS Recommendations

Explores deeper friend connections

Useful for discovering niche preferences

Dijkstra-Based Recommendations

Uses friendship weights + genre similarity

Influence decreases with social distance

Most personalized and optimized approach

Trending Songs

Global ranking using priority queues

Based on total likes + plays

⏱ Performance Analysis

Execution time measured using std::chrono

Side-by-side comparison of BFS, DFS, and Dijkstra

Demonstrates real-world efficiency differences between algorithms

🧠 Data Structures Used

map, unordered_map

vector

queue, stack

priority_queue

Graph representations via adjacency lists

🚀 How to Run

Compile using a C++ compiler (C++11 or later):

g++ bfsbeats.cpp -o bfsbeats


Run:

./bfsbeats


Use the interactive menu to explore features

👩‍💻 Contributors

Iffat Zahra (501970)

Ayesha Ghafoor (522175)

Haram Chishti (503090)
