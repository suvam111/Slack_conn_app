# Slack_connect_app
Slack Connect - Message Scheduler
A full-stack TypeScript application that enables users to connect their Slack workspace, send messages immediately, and schedule messages for future delivery with automatic token refresh and reliable message scheduling.
Features
Core Functionality:-
🔐 Secure OAuth 2.0 Integration: Connect Slack workspaces with proper authorization flow

🔄 Automatic Token Refresh: Seamless token rotation without user re-authentication

💬 Immediate Messaging: Send messages instantly to any accessible Slack channel

⏰ Message Scheduling: Schedule messages for precise future delivery

📋 Schedule Management: View, edit, and cancel scheduled messages

🔄 Reliable Delivery: Automatic retries with exponential backoff for failed messages


Technical Features:-
TypeScript: Full type safety across frontend and backend

Real-time Updates: Live status tracking for scheduled messages

Responsive Design: Works seamlessly on desktop and mobile

Error Handling: Comprehensive error boundaries and user feedback

Security: JWT authentication, CORS protection, rate limiting

Performance: Optimized database queries and efficient scheduling

Technology Stack:-
Frontend:
React 18 with TypeScript

Vite for fast development and optimized builds

React Router for client-side routing

Axios for API communication

React Hook Form for form management

Date-fns for date manipulation

Lucide React for icons

Tailwind CSS for styling (or CSS modules)

Backend:
Node.js with Express.js

TypeScript for type safety

SQLite for
