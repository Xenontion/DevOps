# My Node.js Project

This project is a simple Node.js application that serves a static HTML page. It demonstrates how to set up an HTTP server using Node.js and serve files from a public directory.

## Project Structure

```
my-nodejs-project
├── src
│   ├── server.js        # Entry point of the Node.js application
│   └── public
│       └── index.html   # Simple HTML page served by the application
├── package.json         # npm configuration file
└── README.md            # Documentation for the project
```

## Setup Instructions

1. **Clone the repository:**
   ```
   git clone <repository-url>
   cd my-nodejs-project
   ```

2. **Install dependencies:**
   ```
   npm install
   ```

3. **Run the server:**
   ```
   node src/server.js
   ```

4. **Access the application:**
   Open your browser and navigate to `http://localhost:3000` to view the test page.

## Usage

This application serves a static HTML page located in the `src/public` directory. You can modify the `index.html` file to change the content displayed in the browser.

## License

This project is licensed under the MIT License.