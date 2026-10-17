# DirectChat-Backend-Files

Step-By-Step:

Run it on your server

1. Extract the ZIP on your server.
   
3. Install Node.js 20 or newer and PostgreSQL, or use Docker Compose.
   
5. Copy .env.example to .env.

6. Set your database connection, allowed Wix frontend origin, and authentication verification settings.
   
8. Install and start the service:
   
npm install

npm run dev

For production, use npm start behind an HTTPS reverse proxy.

What is included?

- Member authentication verification
- 
- Direct conversations and conversation membership checks
- 
- Persistent message storage in PostgreSQL
- 
- REST API for conversation lists and message history
- 
- Socket.IO for real-time message delivery
- 
- Docker configuration for deployment
