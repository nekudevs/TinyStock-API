# TinyStock-API
Backend Software Challenge


How to set up the server and run sample HTTP requests for this solution, follow these instructions:

Step 1: Install Node.js and npm

Make sure you have Node.js installed on your machine. You can download it from the official website: https://nodejs.org/en/download/
npm (Node Package Manager) is bundled with Node.js, so you should have npm installed automatically.
Step 2: Create a new directory for this project

Open your terminal or command prompt and navigate to the directory where you want to access this project.
In your terminal or command prompt, navigate to your project directory.

Step 4: Running the server
Run the following command to start the server:

`node .`

You should see a message indicating that the server is listening on a specific port (in this case, port 8080).

You can now send sample HTTP requests to the server using a tool like insomnia or a web browser.
Open your preferred tool and send the following requests:

`GET http://localhost:8080/tickers`

`GET http://localhost:8080/tickers/{ticker}/history`

Where {ticker} is the symbol of said ticker ie. `GET http://localhost:8080/tickers/AAPL/history`
