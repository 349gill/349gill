<!DOCTYPE html>
<html>
<head>
<style>
.container {
  width: 100%;
  max-width: 1200px;
  margin: 0 auto;
  padding: 20px;
}

.flex-wrapper {
  display: flex;
  gap: 32px;
  flex-wrap: wrap;
}

.content-section {
  flex: 1;
  min-width: 300px;
}

.stats-section {
  flex: 1;
  min-width: 300px;
  display: flex;
  justify-content: center;
  align-items: flex-start;
}

.content-section h1 {
  color: #ffffff;
  margin-bottom: 16px;
}

.content-section p {
  color: #c9d1d9;
  line-height: 1.5;
  margin-bottom: 16px;
}

.content-section a {
  color: #58a6ff;
  text-decoration: none;
}

.content-section a:hover {
  text-decoration: underline;
}

body {
  background-color: #0d1117;
  font-family: -apple-system,BlinkMacSystemFont,"Segoe UI",Helvetica,Arial,sans-serif,"Apple Color Emoji","Segoe UI Emoji";
}

h3 {
  color: #ffffff;
  margin-top: 24px;
  margin-bottom: 16px;
}

.repo-card {
  max-width: 100%;
  height: auto;
}

.stats-image {
  max-width: 80%;
  height: auto;
}

@media (max-width: 768px) {
  .flex-wrapper {
    flex-direction: column;
  }
  
  .content-section, .stats-section {
    width: 100%;
  }
  
  .stats-section {
    margin-top: 32px;
  }
  
  .stats-image {
    max-width: 100%;
  }
}
</style>
</head>
<body>
  <div class="container">
    <div class="flex-wrapper">
      <div class="content-section">
        <h1>Hello there!</h1>
        <p>
          I'm an undergraduate student at the University of Alberta. I'm highly interested in software applications and systems.
          Some of my other interests include: Automated theorem proving, Computer Graphics, and Computer Architecture.
        </p>
        <p>
          <a href="https://www.linkedin.com/in/harsh-gill/">Contact me</a>
        </p>
        <h3>Currently working on:</h3>
        <p>
          <a href="https://github.com/349gill/lane-detection">
            <img class="repo-card" src="https://github-readme-stats.vercel.app/api/pin/?username=349gill&repo=lane-detection&theme=dark" alt="Repo Card">
          </a>
        </p>
      </div>
      
      <div class="stats-section">
        <img class="stats-image" src="https://github-readme-stats.vercel.app/api/top-langs/?username=349gill&theme=dark&layout=donut-vertical" alt="Top Languages"/>
      </div>
    </div>
  </div>
</body>
</html>
