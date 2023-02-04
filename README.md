<img src="./docs/logo1.png" width="500" alt="landing page mobile">


A MERN Application built by Callum Rowstan and Mario Lisbona
<br>
<img src="./docs/icons8-github-30.png" height="20"> [Callum Rowstan](https://github.com/CallumRowston)
<br>
<img src="./docs/icons8-github-30.png" height="20"> [Mario Lisbona](https://github.com/MarioLisbona)

Traveller's Forum is online forum where users can share travel stories and information on their favorite parts of the world. its aim is to create a sense of community through shared experiences and a love for adventure and exploring new cultures. Guests can read stories from various parts of the world. Guests can register to become members to be able to contribute by posting their own stories, commenting on other member's travel stories and rate each story.

Traveller's Forum is deployed on Netlify and Railway. It was developed using the MERN stack.

#

## Links

🌏 Deployed Application: [https://travelersforum.netlify.app/](https://travellersforum.netlify.app/)

⚙️ Staging Environment: [https://travelersforum.netlify.app/](https://staging--travellersforum.netlify.app/)

💾 Server Repo: [https://github.com/CallumRowston/CA-T3A2-B-travelers-forum-server](https://github.com/CallumRowston/CA-T3A2-B-travelers-forum-server)

💻 Client Repo: [https://github.com/MarioLisbona/CA-T3A2-B-travelers-forum-client](https://github.com/MarioLisbona/CA-T3A2-B-travelers-forum-client)

## Installation

## API Endpoints

API Endpoint documentation can be found [here]()

## Server Libraries and Dependencies

### Server Libraries

`mongoose ^6.8.4"`- An object data modelling (ODM) library for use with MongoDB. Used to build schema and models that enforce structure at the application layer.

`express ^4.18.2` - A Node JS based minimal back end web framework for building REST APIs. Used to build routes to handle HTTP requests.

`dotenv ^16.0.3` - Used to load variables stored in `.env` files into `process.env`. Allows for environment configuration to be kept separate from the code and protect database credentials and JWT secret key.

`cors ^2.8.5"` - Provides middleware to ExpressJS to enable cross origin requests that are normally forbidden.

`validator ^13.7.0` - Library for validating and sanitising strings.

`express-validator ^6.14.3` - Set of ExpressJS middlewares that wrap `validator` and provide further validation and sanitizer functions. Used to validate data in incoming requests.

`jsonwebtoken ^9.0.0` - An open standard for sharing security information between client and server. Used for user authentication by issuing a JWT to the client upon successful login by digitally signing information using a secret key and cryptographic algorithm. This is validated by the server when the user attempts to access protected routes.

`bcrypt ^5.1.0` - A password hashing function used for securely storing passwords in the database.

### Server Development Dependencies

`jest ^29.4.1` - A JavaScript testing framework for writing tests and running automated tests.

`supertest ^6.3.3` - A Node.js library for testing APIs. Provides high level abstraction for testing.

## Client Libraries and Dependencies

### Client Libraries

`react: ^18.2.0` - React is a Javascript library that provides a declarative, efficient and flexible way to build user interfaces for an application. It allows developer to use multiple small, isolated pieces of code, called 'components' to create complex and interactive UI's.

`react-dom: ^18.2.0` - React-dom is a package that provides a Virtual DOM which is a copy of the actual DOM structure that is used to track changes that are made by the user. Those changes are eventually reflected in the browser's DOM structure. The package provides developed with methods to maniupalte the virual dom, inlcuding `.render()` and `.findDOMNode`

`react-router-dom: ^6.7.0` - React Router is used to create an SPA (Single Page Application). It provides a library that lets developers take advantage of client-side rendering routing. This means that different components can be rendered within the app for each URL without having to fetch a new page each time.

`@fortawesome/fontawesome-svg-core: ^6.2.1`

`fortawesome/free-solid-svg-icons: ^6.2.1`

`@fortawesome/react-fontawesome: ^0.2.0`

The font awesome libraries are used to add the icons for the juser registration form. The registration form has front-end input validation and the icons are used to inform the user if they have not entered valid input.

`moment: ^2.29.4` -  Moment is used to format the dates on each post when viewed as a full page. It is also used to provide information on the preview cards about how long ago each post was made.

### Client Development Dependencies

`vite": "^4.0.0` - Vite allows developers to setup and build a front-end development environment for React that contains a dev server. It also has the feature of a Hot Module Reload which updates the server with changes to the codebase.

`@testing-library/jest-dom: ^5.16.5`

`@testing-library/react: ^13.4.0`

`@testing-library/react-hooks: ^8.0.1`

`@testing-library/user-event: ^14.4.3`

`@types/react: ^18.0.26`

`@types/react-dom: ^18.0.9`

`@vitejs/plugin-react: ^3.0.0`

`jsdom: ^21.1.0`

`vitest: ^0.28.3`

These packages are used to run unit tests and integration tests on the application.
They need to be installed with the flag `--legacy-peer-deps` appended to CLI command.

## Application Screenshots

## Testing

Extensive testing has been carried out in both Chrome and Firefox running on Windows and MacOS and various devices and screen sizes. Automated testing has been developed using Vitest and Jest. Manual testing was carried out using Postman and running the application locally and via deployment.

Manual Testing During Development, Staging and Production: [Click Here](https://docs.google.com/spreadsheets/d/1ZN6NrLZgrfrI0-DRtoB7dR9KK781k1nl1RJyCdUfHI8/edit#gid=0)

Further Manual Testing for production app: [Click Here](docs/testing-production.md)

Postman Testing: [Click Here](docs/testing-postman.md)

Font-end testing: Automated testing to check that the correct structure and output is present on the PreviewCard component. Automated testing for conditional rendering of the username in the navbar is done in a second test. A third test checks that the links in the footer are displayed and that when they are clicked they route to the correct component. [Click Here](https://github.com/MarioLisbona/CA-T3A2-B-travelers-forum-client/tree/main/tests)