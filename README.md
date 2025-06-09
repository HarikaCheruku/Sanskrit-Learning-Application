<a href="https://sanskrit-learning.onrender.com/" target="_blank">Sanskrit Learning Application 🔗</a>
<h1>Sanskrit Learning Application</h1>

<h2>Overview</h2>
<p>The Sanskrit Learning Application is an interactive platform inspired by Duolingo, designed to make learning Sanskrit engaging and accessible. It provides a comprehensive suite of tools for users to master Sanskrit through structured lessons, quizzes, cultural insights, and community interaction. The application leverages modern web technologies to deliver a seamless learning experience, complete with gamification, audio pronunciation, and a bookstore for additional resources.</p>

<h2>Features</h2>
<ul>
  <li><strong>User Management:</strong> Handles user registration, secure login with session management, profile updates, and password resets. Tracks learning progress and history.</li>
  <li><strong>Lesson Viewer:</strong> Offers interactive lessons with explanations, examples, and exercises. Features SVG-based Sanskrit word representations and audio playback for pronunciation.</li>
  <li><strong>Quiz and Exercises:</strong> Includes multiple-choice quizzes and tasks with instant feedback. Integrates scores with progress tracking for a personalized experience.</li>
  <li><strong>Gamification System:</strong> Awards badges and points for lesson completions and high quiz scores. Tracks daily streaks to encourage consistent learning.</li>
  <li><strong>Cultural Insights Section:</strong> Provides interactive Sanskrit stories, mythological texts, and cultural readings with related quizzes to explore Sanskrit’s historical and literary influence.</li>
  <li><strong>Navigation System:</strong> Offers a user-friendly sidebar menu for seamless access to Home, Lessons, Quizzes, Progress, Chatbox, and Profile sections.</li>
  <li><strong>Admin Dashboard:</strong> Enables administrators to manage users, content, and platform performance, with tools to update lessons, quizzes, and track engagement.</li>
  <li><strong>Chatbox:</strong> Facilitates peer-to-peer interaction, allowing users to send messages, ask queries, and discuss topics in a group setting.</li>
  <li><strong>Bookstore:</strong> Curates a selection of Sanskrit-related books, redirecting users to external platforms like Amazon or Flipkart for purchases.</li>
</ul>

<h2>Tech Stack</h2>
<ul>
  <li><strong>Operating System:</strong> Windows</li>
  <li><strong>IDE:</strong> Visual Studio Code (VS Code)</li>
  <li><strong>Frontend Technologies:</strong> ReactJS, Tailwind CSS</li>
  <li><strong>Backend:</strong> Node.js, Express.js</li>
  <li><strong>Database:</strong> NeonDB</li>
  <li><strong>Version Control:</strong> GitHub</li>
</ul>


<h2>Installation</h2>
<p>Fork this repository: Click the Fork button located in the top-right corner of the GitHub page.</p>
<p>Clone the repository:</p>
<pre><code>git clone https://github.com/<your-username>/Sanskrit-Learning.git
cd Sanskrit-Learning
</code></pre>
<p>Create .env file:</p>
<p>Inside the root directory, create a .env file and set:</p>
<pre><code>NEONDB_CONNECTION_STRING=<your_neondb_connection_string>
PORT=3000
</code></pre>
<p>Install dependencies:</p>
npm install
</code></pre>
<pre><code>
npm run dev
</code></pre>
<p>Access the application:</p>
<p>Visit <a href="http://localhost:5173">http://localhost:5173</a> to access the Sanskrit Learning Application.</p>

<h2>Usage</h2>
<p>After starting the frontend and backend servers, navigate to <a href="http://localhost:5173">http://localhost:5173</a>. Register or log in to access lessons, quizzes, cultural content, and the chatbox. Use the sidebar to navigate between sections and track your progress.</p>

<h2>Future Improvements</h2>
<ul>
  <li>Add advanced pronunciation tools with AI-driven feedback for accurate Sanskrit speech.</li>
  <li>Expand the bookstore with in-platform previews of Sanskrit texts.</li>
  <li>Integrate real-time collaboration for group-based learning activities.</li>
</ul>

<h2>Contributing</h2>
<p>If you want to contribute to this project, feel free to open issues or submit pull requests. Make sure to follow the contribution guidelines.</p>
