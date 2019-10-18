
 # @author   Tristan Mclennan
 # This was a school project from CS 667: We never fully finished the docker deployment due to time constraints.
 # I'm looking to figure out what the bugs are, get it deployed, and then polish it and add functionality. 
 
Requirements for project:
- Express back end with get/post endpoints
- Mongodb for storage
- Websocket
- React + Redux with routes
- Microserver architecture, gateway must only server to route requests, break up microservices by topic, ie user services, comment services… can be done with express or NGNIX
- redis for shared data
- Backend components must be dockerized and running in Docker swarm mode
- Node components can use either docker or pm2 (cluster)
- Use at least 1 kafka message topic to broadcast real time updates (can get extra credit with this)
- Bonus points for an electron port with some native functionality.
- Hopefully reverse proxy with NGNIX
