# Static Website Hosting with Docker and Nginx 🚀

This project demonstrates how to host a simple static website using **Docker** and **Nginx**.

---

## 🛠 Prerequisites

- **Docker** must be installed on your computer.  
  Check out <a href="https://docs.docker.com/get-docker/" target="_blank">Docker Installation Guide</a> if needed.

---

## 📦 Building the Docker Image

<ol>
  <li>Navigate to the project folder in your terminal:
    <pre><code>cd /path/to/project-folder</code></pre>
  </li>
  <li>Run the following command to build the Docker image:
    <pre><code>docker build -t static-website .</code></pre>
    <p>This command uses the instructions in the <code>Dockerfile</code> to assemble the Docker image.</p>
  </li>
</ol>

---

## 🚀 Running the Website Locally

<ol>
  <li>Start a Docker container with the following command:
    <pre><code>docker run -d -p 8080:80 static-website</code></pre>
    <p>This maps port <code>8080</code> on your local machine to port <code>80</code> inside the container.</p>
  </li>
  <li>Open your browser and navigate to:
    <blockquote>
      <a href="http://localhost:8080" target="_blank">http://localhost:8080</a>
    </blockquote>
  </li>
</ol>

---

## 🌐 Making Your Website Public

By default, the website is only accessible on your local machine. To make it public:
<ul>
  <li>Deploy it to a cloud platform like <a href="https://aws.amazon.com/">AWS</a>, <a href="https://azure.microsoft.com/">Azure</a>, or <a href="https://cloud.google.com/">Google Cloud</a>.</li>
  <li>Or, share your local instance using tools like <a href="https://ngrok.com/">ngrok</a>.</li>
</ul>

<blockquote>
  <strong>⚠ Note:</strong> Running it locally means the website will only be live while your computer is on and the Docker container is running.
</blockquote>
