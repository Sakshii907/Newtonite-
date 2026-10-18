# Newtonite Ops – Project Summary

Newtonite  is a web-based application that helps teams manage their daily operational tasks in one place. Instead of tracking work through emails, chats, and spreadsheets, users can create and manage work items such as payment issues, production problems, and approval requests.

Users can create tasks, set priorities, assign ownership, update statuses, add comments, and track the complete history of each task. The application provides a dashboard to identify urgent tasks, pending approvals, overdue work, and tasks that have not been updated for a long time. It also supports searching, filtering, and notifications.

The application has four user roles: Viewer, Member, Lead, and Admin. Each role has different permissions based on its responsibilities within a team. The server checks these permissions to ensure that users can access only the information and actions they are authorized to use.

A key feature of Newtonite Ops is its ability to handle multiple users working on the same task. It prevents two users from claiming the same task, detects conflicting edits, and safely handles repeated requests. It also maintains a reliable history of important activities and retries failed notifications.

**Technologies Used:**
- **Python and FastAPI:** Handle application logic and server requests.
- **PostgreSQL:** Stores task details, user information, history, and notifications.
- **HTML:** Provides the user interface.
- **Docker:** Runs the application and its required services in a consistent environment.
- **Pytest:** Tests important functions, permissions, and error-handling scenarios.

The application runs locally using Docker Desktop. Future improvements include real-time updates, email and Slack notifications, better search, and automated user-interface testing.

Overall, Newtonite Ops makes team operations more organized, secure, transparent, and reliable.
