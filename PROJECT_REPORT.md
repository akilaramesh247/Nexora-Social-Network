NEXORA – SOCIAL NETWORK SIMULATION SYSTEM
Data Structures Mini Project Report

Project Overview
Nexora is a single-page social-network simulation built with HTML, CSS, and JavaScript. It demonstrates common social-network features in a browser-based environment. Demo information is stored in browser localStorage.

Objectives
• Demonstrate social-network concepts and interactions.
• Represent relationships between users as a graph.
• Provide a simple interface for posts, friendships, communities, notifications, and analytics.
• Demonstrate a community-detection approach using label propagation.

Main Features
• Login, registration, and password-reset demo
• User profiles
• Friend requests and friends list
• Posts, likes, comments, and sharing
• Communities
• Notifications
• Analytics charts
• Social-network graph and community detection
• Admin dashboard
• Light and dark themes

Technology Stack
• HTML – page structure
• CSS – styling and responsive layout
• JavaScript – application behavior
• Chart.js – charts, loaded from a CDN
• localStorage – browser-side demo persistence

Data Structures
• Graph: users and friendship connections.
• Arrays/lists: collections of posts, comments, notifications, requests, and community data.
• Objects: structured records for profiles and content.
• localStorage: browser persistence for demo data.

Algorithm: Label Propagation (concept)
Initialize node labels; repeatedly update each node's label to the most frequent label among its neighbours. Stop after a set number of rounds or when labels no longer change. Group nodes by label.

Limitations
This is a simulation and not a production social network. Data is stored locally in the browser and is not synchronized between devices. Demo credentials are included for demonstration only. Do not use real or sensitive information.

How to Run
Open index.html in a modern browser, or use the GitHub Pages website published from the repository.

Demo Accounts
User: aarav | Password: demo123
Admin: admin | Password: admin123

Conclusion
Nexora demonstrates how data structures and algorithms can be applied to social-network features, including graph representation, collections of content, interaction workflows, and community grouping.
