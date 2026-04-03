<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Harschel JavaScript Project</title>
</head>

<body style="font-family: Arial, sans-serif; line-height:1.6; padding:20px;">

<h1>🚀 Harschel JavaScript Project (CRUD App using JSON Server)</h1>

<p>
This project is a <b>Vanilla JavaScript CRUD Application</b> that uses 
<b>JSON Server</b> to simulate a backend REST API.
It demonstrates how frontend applications interact with APIs using Fetch API.
</p>

<hr>

<h2>Demo </h2><img width="1887" height="1036" alt="Screenshot 2026-04-03 190159" src="https://github.com/user-attachments/assets/d109ca3a-afce-47c4-9a40-fdfdaeb09de8" />
<img width="1900" height="1026" alt="Screenshot 2026-04-03 190235" src="https://github.com/user-attachments/assets/27029b13-eaaf-421c-9d4f-1b5929931712" />
</h2>

<img width="1900" height="1031" alt="Screenshot 2026-04-03 190221" src="https://github.com/user-attachments/assets/1cba1e75-23e2-45aa-9dd9-ae7142143e7c" />







<h2>📌 Features</h2>

<ul>
<li>✅ Add new data (Create)</li>
<li>✅ Display stored data (Read)</li>
<li>✅ Update existing records (Update)</li>
<li>✅ Delete records (Delete)</li>
<li>✅ Uses JSON Server as Fake REST API</li>
<li>✅ API integration using Fetch</li>
<li>✅ Beginner-friendly project structure</li>
</ul>

<hr>

<h2>🛠️ Technologies Used</h2>

<ul>
<li>HTML5</li>
<li>CSS3</li>
<li>JavaScript (ES6)</li>
<li>JSON Server</li>
<li>Fetch API</li>
</ul>

<hr>

<h2>📂 Project Structure</h2>

<pre>
Harschel-JavaScriptProject
│
├── index.html
├── style.css
├── script.js
├── db.json
└── README.html
</pre>

<hr>

<h2>⚙️ How to Run This Project Locally</h2>

<h3>Step 1 — Clone Repository</h3>

<pre>
git clone https://github.com/CodeWithSoumya18/Harschel-JavaScriptProject.git
</pre>

<h3>Step 2 — Open Project Folder</h3>

<pre>
cd Harschel-JavaScriptProject
</pre>

<hr>

<h2>📦 Install JSON Server</h2>

<p>Install globally:</p>

<pre>
npm install -g json-server
</pre>

<p>OR install locally (recommended):</p>

<pre>
npm install json-server
</pre>

<hr>

<h2>▶️ Start JSON Server</h2>

<pre>
json-server --watch db.json --port 3000
</pre>

<p>Server runs at:</p>

<pre>
http://localhost:3000
</pre>

<hr>

<h2>🌐 How to Open Project in Browser</h2>

<h3>Method 1 — Direct Open</h3>

<p>Double click:</p>

<pre>
index.html
</pre>

<h3>Method 2 — Using VS Code Live Server (Recommended)</h3>

<ol>
<li>Open project in VS Code</li>
<li>Install Live Server extension</li>
<li>Right click index.html</li>
<li>Click "Open with Live Server"</li>
</ol>

<p>Project runs at:</p>

<pre>
http://127.0.0.1:5500
</pre>

<hr>

<h2>📡 Generated REST APIs</h2>

<p>Example endpoints created automatically from db.json:</p>

<pre>
GET     http://localhost:3000/users
GET     http://localhost:3000/users/1
POST    http://localhost:3000/users
PUT     http://localhost:3000/users/1
PATCH   http://localhost:3000/users/1
DELETE  http://localhost:3000/users/1
</pre>

<hr>

<h2>📡 JavaScript Fetch API Examples</h2>

<h3>Fetch Data</h3>

<pre>
fetch("http://localhost:3000/users")
.then(res => res.json())
.then(data => console.log(data))
</pre>

<h3>Add Data</h3>

<pre>
fetch("http://localhost:3000/users", {
method: "POST",
headers: {
"Content-Type": "application/json"
},
body: JSON.stringify({
name: "Soumyashree"
})
})
</pre>

<h3>Update Data</h3>

<pre>
fetch("http://localhost:3000/users/1", {
method: "PATCH",
headers: {
"Content-Type": "application/json"
},
body: JSON.stringify({
name: "Updated Name"
})
})
</pre>

<h3>Delete Data</h3>

<pre>
fetch("http://localhost:3000/users/1", {
method: "DELETE"
})
</pre>

<hr>

<h2>📊 Example db.json Structure</h2>

<pre>
{
"users": [
{
"id": 1,
"name": "Soumyashree"
}
]
}
</pre>

<hr>

<h2>🎯 Learning Outcomes</h2>

<ul>
<li>✔ CRUD operations using JavaScript</li>
<li>✔ REST API fundamentals</li>
<li>✔ JSON Server usage</li>
<li>✔ Fetch API integration</li>
<li>✔ Frontend–backend communication basics</li>
</ul>

<hr>

<h2>🚀 Future Improvements</h2>

<ul>
<li>Add search functionality</li>
<li>Add filtering system</li>
<li>Add pagination</li>
<li>Add form validation</li>
<li>Deploy project online (Netlify / GitHub Pages)</li>
<li>Replace JSON Server with Node.js + Express backend</li>
</ul>

<hr>

<h2>👩‍💻 Author</h2>

<p><b>Soumyashree Nayak</b></p>

<p>
GitHub:
<br>
https://github.com/CodeWithSoumya18
</p>

</body>
</html>
