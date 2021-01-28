# CPTV-Intercom

[!LAST COMMIT](https://img.shields.io/github/last-commit/P10Designs/CPTV-Intercom)

- [ ] SERVER
  - Server side that handles communication between users.
  * MUST HAVE:
    - Connector
    - Voice channels
  TODO:
  - [ ] Create express routes
  - [ ] Create socket.io server
  - [ ] Create socket.io connection
  - [ ] Create peerjs connections
  - [ ] Create admin side

- [ ] CLIENT
  * React Native
  
  - [ ] Overlay
  - [ ] Name handler 
  - [ ] Buttons
  - [ ] App


# HOW IT WORKS #

* Client Side
  - Firstly you introduce your name and code given by the admin
  - Secondly the controller screen shows up and you have full access to the app

* Server Side
  - Once server is initiated, admin has access to it´s panel
  - Here the admin can create users to connect to the app, and give them privileges or roles
  - After that the admin gives the code to the user and this one connects to the app.
  - The server then handles calls between users
