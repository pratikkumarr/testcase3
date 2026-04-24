## Test Case 3 — Node.js Application Setup & Git Integration


**Scenario:** You are setting up a new Node.js REST API from scratch and publishing it to GitHub.

### Tasks

1. Initialize a new Node.js project and install the required dependencies: `express` and `@types/express` (as a dev dependency).
2. Create an `index.js` file that starts an Express server on port `8080` with the following endpoint:
   - `GET /health` — returns HTTP status `200` with the JSON response `{ "status": "OK" }`.
3. Initialize a Git repository in the project folder.
4. Create an initial commit with all project files.
5. Create a GitHub repository named `nodejs-api` and push your code to it.

### Expected Outcome

- Project folder contains `package.json`, `node_modules/`, and `index.js`.
- Running the server locally and calling `GET /health` returns:
  ```json
  { "status": "OK" }
  ```
- GitHub repository `nodejs-api` is publicly visible with at least one commit containing all project files.

---
