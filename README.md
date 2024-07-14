# Vocabulary-Quiz
# Requirements:
# Node with version above 16.x
# Programming languages in use including: NodeJS/TypeScript and Socket.io to update realtime-statistics. 
# DB: Postgres

# Setting up
# At commandline console run:
- Enable you have installed Posgres DB and Create a DB named Challenging
- run "git clone [repo](https://github.com/JackyTaan/Vocabulary-Quiz.git)" to get source code.

# Run Back-End APIs: 
- Modify file .env ( config DB Connection )
- run "npx prisma migrate dev" to generate DB Schema from script
- run "npm install" to update packages related
- run "npm run dev" to start API with port 3000

# Run Web Application:
- run "cd src/my-app" to move into folder of web application"
- run "npm install" to update packages related
- move back to root folder
- run "npm run my-app:start" to start Client Web with port 3001

# Follow this guide to experience the Quiz App"
- Refer to: https://github.com/JackyTaan/Vocabulary-Quiz/blob/main/Real-Time%20Vocabulary%20Quiz%20Coding%20Challenge.pdf

