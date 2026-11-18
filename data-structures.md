# Data Structures Used in Nexora

Nexora is a browser-based social network simulation. The following data structures describe the kinds of structures represented by the application's features. This is a project-level explanation of the visible functionality; the browser implementation uses JavaScript objects and localStorage.

## 1. Graph
- **Purpose:** Represent users and their friendship connections.
- **Representation:** Users are vertices (nodes); friendships are edges.
- **Use:** The social-network graph view and community-detection demonstration.

## 2. Lists / Arrays
- **Purpose:** Store collections such as posts, comments, notifications, friend requests, and community members.
- **Use:** Display, iterate, filter, and update these collections.

## 3. Objects / Records
- **Purpose:** Represent a user profile, post, comment, or notification with multiple fields.
- **Use:** Keep related values together, such as a profile's username and details or a post's content and interaction counts.

## 4. Queue-like ordering
- **Purpose:** Pending friend requests and notifications can be viewed in arrival order.
- **Note:** This is a conceptual queue-like use; the application does not necessarily implement a dedicated queue class.

## 5. Persistent browser storage
- **Purpose:** localStorage keeps demo data between browser sessions on the same device/browser.
- **Limitation:** localStorage is not a server database and does not synchronize between different users or devices.
