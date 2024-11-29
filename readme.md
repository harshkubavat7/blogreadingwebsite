<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>README - Blog Reading Website</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      background-color: #f4f4f4;
      margin: 0;
      padding: 20px;
    }
    h1, h2, h3 {
      color: #333;
    }
    p, ul, code, pre {
      color: #555;
    }
    pre {
      background: #eee;
      padding: 10px;
      border-radius: 5px;
      overflow-x: auto;
    }
    ul {
      list-style: disc inside;
      margin: 10px 0;
    }
    a {
      color: #007bff;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }
    .container {
      max-width: 800px;
      margin: auto;
      background: #fff;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>README for Blog Reading Website</h1>

    <h2>Project Overview</h2>
    <p>The <strong>Blog Reading Website</strong> is a platform for users to browse, read, and engage with blog posts. It includes features like user authentication, personalized content, and commenting.</p>

    <h2>Features</h2>
    <ul>
      <li><strong>User Authentication</strong>: Sign up, login, and password recovery.</li>
      <li><strong>Blog Management</strong>: Browse blogs by category, read full posts, and comment.</li>
      <li><strong>Personalization</strong>: Bookmark blogs, get personalized recommendations.</li>
      <li><strong>Admin Features</strong>: Manage blogs and users, moderate comments.</li>
    </ul>

    <h2>Tech Stack</h2>
    <ul>
      <li><strong>Frontend</strong>: React.js</li>
      <li><strong>Backend</strong>: Node.js with Express</li>
      <li><strong>Database</strong>: MongoDB</li>
      <li><strong>Authentication</strong>: JWT (JSON Web Tokens)</li>
    </ul>

    <h2>Installation Guide</h2>
    <ol>
      <li><strong>Clone the Repository</strong>:
        <pre><code>git clone https://github.com/your-repo/blog-reading-website.git
cd blog-reading-website</code></pre>
      </li>
      <li><strong>Install Dependencies</strong>:
        <pre><code>cd frontend
npm install

cd backend
npm install</code></pre>
      </li>
      <li><strong>Set Environment Variables</strong>:
        <pre><code>PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret</code></pre>
      </li>
      <li><strong>Run the Application</strong>:
        <pre><code># Start Backend
cd backend
npm start

# Start Frontend
cd frontend
npm start</code></pre>
      </li>
      <li><strong>Access the Website</strong>: Open <a href="http://localhost:3000" target="_blank">http://localhost:3000</a> in your browser.</li>
    </ol>

    <h2>Folder Structure</h2>
    <pre><code>blog-reading-website/
├── frontend/              # Frontend React application
├── backend/               # Backend Express application
├── .env                   # Environment variables
├── README.md              # Project documentation
└── package.json           # Project metadata</code></pre>

    <h2>Contributing</h2>
    <ol>
      <li>Fork the repository.</li>
      <li>Create a new branch:
        <pre><code>git checkout -b feature/your-feature</code></pre>
      </li>
      <li>Commit your changes:
        <pre><code>git commit -m "Add your feature"</code></pre>
      </li>
      <li>Push to the branch:
        <pre><code>git push origin feature/your-feature</code></pre>
      </li>
      <li>Open a pull request.</li>
    </ol>

    <h2>License</h2>
    <p>This project is licensed under the MIT License. See the <a href="LICENSE">LICENSE</a> file for details.</p>

    <h2>Contact</h2>
    <p>For any issues or questions:</p>
    <ul>
      <li><strong>Email</strong>: <a href="mailto:support@blogreadingwebsite.com">support@blogreadingwebsite.com</a></li>
      <li><strong>GitHub</strong>: <a href="https://github.com/your-repo" target="_blank">https://github.com/your-repo</a></li>
    </ul>
  </div>
</body>
</html>
