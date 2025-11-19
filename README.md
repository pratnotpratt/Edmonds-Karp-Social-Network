# Edmonds-Karp-Social-Network
This project demonstrates how the Edmonds–Karp algorithm (a BFS-based implementation of the Ford–Fulkerson method) can be applied to Social Network Analysis (SNA). Instead of traditional max-flow examples, we model a social network where edges represent influence strength between individuals.
The algorithm calculates:
- The **maximum influence flow** from one person to another
- **Bottleneck connections** in the network
- A **visual representation** of the influence network and capacities

This is a simple, clean, easy-to-understand implementation suitable for academic submissions, research learning, and GitHub portfolio projects.

---

## 🎯 Why Edmonds–Karp?
- Easy to understand  
- Perfect for teaching/learning max-flow  
- Useful in social networks, recommendation systems, and information spread analysis  
- Great for demonstrating graph algorithms with visualization  
- Clear step-by-step BFS-based approach

---

## 🧠 Algorithm Summary
Edmonds–Karp repeatedly:
1. Uses **BFS** to find the shortest augmenting path  
2. Identifies the **bottleneck capacity**  
3. Sends flow through the path  
4. Updates the **residual graph**  
5. Stops when no more augmenting paths exist  

**Time Complexity:**  
`O(V * E²)`

---

## 🌐 Social Network Context

In this project:
- **Nodes** = People  
- **Edges** = How strongly one person can influence another  
- **Capacity** = Amount of influence that can flow  

This allows us to answer questions like:
- “How much influence can person A spread to person F?”
- “Which nodes act as influence bottlenecks?”
- “How do relationships affect total influence spread?”

---

## 📁 Graph Used in the Example
