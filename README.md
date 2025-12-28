
<h1>Reqres API Automation Testing</h1>

<p>
  This repository contains automated API test cases for the public REST API
  <strong>https://reqres.in/</strong>.<br>
  The automation is implemented using <strong>Postman</strong> with JavaScript-based
  test scripts to validate API responses, status codes, and data integrity.
</p>

<hr>

<h2>📌 Objective</h2>
<p>To automate and validate the following API scenarios on <strong>Reqres</strong>:</p>
<ul>
  <li>Create a user and validate the HTTP response</li>
  <li>Fetch and validate user details</li>
  <li>Update an existing user and verify updated data</li>
</ul>

<hr>

<h2>🛠 Tools &amp; Technologies Used</h2>
<ul>
  <li><strong>Postman</strong></li>
  <li><strong>JavaScript</strong> (Postman Test Scripts)</li>
  <li><strong>REST APIs</strong></li>
  <li><strong>Git &amp; GitHub</strong></li>
</ul>

<hr>

<h2>📂 Repository Contents</h2>
<ul>
  <li>
    <code>reqres API automation.postman_collection.json</code><br>
    → Postman collection containing all automated API test cases
  </li>
</ul>

<hr>

<h2>🧪 Test Scenarios Covered</h2>

<h3>1️⃣ Create User (POST)</h3>
<ul>
  <li><strong>Endpoint:</strong> <code>/api/users</code></li>
  <li><strong>Validations:</strong>
    <ul>
      <li>HTTP status code is <strong>201</strong></li>
      <li>User ID is generated successfully</li>
      <li>User ID is stored as a <strong>collection variable</strong> for reuse</li>
    </ul>
  </li>
</ul>

<h3>2️⃣ Get Created User Details (GET)</h3>
<ul>
  <li><strong>Endpoint:</strong> <code>/api/users/2</code></li>
  <li><strong>Validations:</strong>
    <ul>
      <li>HTTP status code is <strong>200</strong></li>
      <li>User data exists in the response</li>
      <li>User ID validation</li>
    </ul>
  </li>
</ul>

<h3>3️⃣ Update User (PUT)</h3>
<ul>
  <li><strong>Endpoint:</strong> <code>/api/users/2</code></li>
  <li><strong>Validations:</strong>
    <ul>
      <li>HTTP status code is <strong>200</strong></li>
      <li>User name updated successfully</li>
      <li>Job title updated successfully</li>
    </ul>
  </li>
</ul>

<hr>

<h2>🔄 Variable Handling</h2>
<ul>
  <li>
    <strong>Collection Variable Used:</strong><br>
    <code>userId</code> → Stores the user ID generated during user creation
  </li>
</ul>

<hr>

<h2>▶️ How to Run the Tests</h2>
<ol>
  <li>Install <strong>Postman</strong></li>
  <li>Import the collection file:
    <pre><code>reqres API automation.postman_collection.json</code></pre>
  </li>
  <li>Open the collection in Postman</li>
  <li>Run requests individually or use <strong>Collection Runner</strong></li>
  <li>View test results in the <strong>Tests</strong> tab</li>
</ol>

<hr>

<h2>✅ Expected Outcome</h2>
<ul>
  <li>All API requests execute successfully</li>
  <li>Status codes and response bodies are validated</li>
  <li>User creation, retrieval, and update flows work as expected</li>
</ul>

<hr>

<h2>👤 Author</h2>
<p>
  <strong>Nachiket Agrawal</strong><br>
  QA Automation Intern Candidate<br>
  GitHub:
  <a href="https://github.com/nachiketagrawal2310" target="_blank">
    https://github.com/nachiketagrawal2310
  </a>
</p>

<hr>

<h2>📎 Notes</h2>
<ul>
  <li>This project is created as part of a <strong>QA Automation Intern case study</strong></li>
  <li>APIs used are public and for testing/demo purposes only</li>
</ul>

</body>
</html>
