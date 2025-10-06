# DevOps Project

This project is a simple HTTP server that serves static files from a public directory. It is built using Node.js and can be deployed on platforms like Heroku.

## Project Structure

```
DevOps
├── src
│   ├── server.js        # Main server file
│   └── public
│       └── index.html   # Main HTML file served by the server
├── package.json         # NPM configuration file
└── README.md            # Project documentation
```

## Installation

1. Clone the repository:
   ```
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```
   cd DevOps
   ```
3. Install the dependencies:
   ```
   npm install
   ```

## Usage

To start the server locally, run:
```
npm start
```

The server will be running on `http://localhost:3000`.

## Deployment on Heroku

1. Make sure you have the Heroku CLI installed and you are logged in.
2. Create a new Heroku app:
   ```
   heroku create
   ```
3. Deploy the application:
   ```
   git push heroku main
   ```
4. Open the application in your browser:
   ```
   heroku open
   ```

## License

This project is licensed under the MIT License.