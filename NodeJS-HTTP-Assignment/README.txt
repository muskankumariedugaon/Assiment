Node.js HTTP Module Assignment (Questions 1-15)
================================================

Folder contains 15 separate JavaScript files:
- question1.js through question15.js
- Each file has the question number in a comment and its answer code.

How to run (Windows / VS Code):
1. Extract this ZIP file.
2. Open the extracted NodeJS-HTTP-Assignment folder in VS Code.
3. Open Terminal > New Terminal.
4. Run one file at a time, for example:
   node question1.js
5. Open http://localhost:5000 in your browser, or use Thunder Client/Postman.
6. Stop the server before running another file: press Ctrl + C in terminal.

Important:
- All files use port 5000, so run only one file at a time.
- Questions 11-15 use POST requests. In Thunder Client/Postman choose POST,
  enter http://localhost:5000/users, select Body > JSON, and send JSON.
- The arrays are stored in memory. Restarting the server resets the arrays.
- No Express installation is required; these examples use Node.js built-in http.
