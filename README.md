# NodeJS, ReactJS, Socket.IO Application

A project for Chat Application using Node.js, Express, Mongoose, REST API, ReactJS, and Socket.IO. Has user signup/login, chat windows, user list for chatting with users, seperate chat windows for every user. Currently limited to one-to-one chats.

**Update**: Also features real time annotations on images.

## Live Demo

 - [Application](http://35.192.146.160/)
 - [API Docs](http://35.192.146.160:5000/v1/docs/)


## Sample user credentials (for the hosted application)
1. Admin user:
    - Username: sample@mail.com
    - Password: password1

2. Non admin user 1:
    - Username: sample2@mail.com
    - Password: password1

3. Non admin user 2:
    - Username: sample3@mail.com
    - Password: password1

**Note that admin users are preconfigured. You cant register for an admin account, so try the admin user mentioned above for testing purposes**


## Installation

 - Directions for installation and other information related to backend in [README](./backend/README.md) of `/backend`.
 - Directions for installation and other information related to frontend in [README](./frontend/README.md) of `/frontend`.


## Screenshots

1. Login page
![Login page](https://github.com/Vedant1202/react-nodejs-chat-app/blob/master/screenshots/login-page.png?raw=true)

2. Register page
![Register page](https://github.com/Vedant1202/react-nodejs-chat-app/blob/master/screenshots/register-page.png?raw=true)

3. Home page (default)
![Home page (default)](https://github.com/Vedant1202/react-nodejs-chat-app/blob/master/screenshots/home-blank.png?raw=true)

4. Home page (chat active)
![Home page (chat active)](https://github.com/Vedant1202/react-nodejs-chat-app/blob/master/screenshots/chat-open.png?raw=true)

5. Users list collapsed
![Users list collapsed](https://github.com/Vedant1202/react-nodejs-chat-app/blob/master/screenshots/chat-list-collapsed.png?raw=true)


## Flowcharts

1. Real time annotations with web sockets
![Real time annotations with web sockets](https://github.com/Vedant1202/react-nodejs-chat-app/blob/master/flowcharts/GSOC-21-real-time-pathology.png?raw=true)


## Contributing

Contributions are more than welcome! Please check out the [contributing guide](CONTRIBUTING.md).


## License

[MIT](LICENSE)