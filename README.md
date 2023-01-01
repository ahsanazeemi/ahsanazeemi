<html>
  <head>
    <style>
      /* Add some style to the page */
      body {
        font-family: 'Arial', sans-serif;
        color: #333;
      }
      h1 {
        font-size: 2em;
        text-align: center;
      }
      p {
        line-height: 1.5;
        margin-bottom: 1.5em;
      }
      .card {
        box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
        transition: 0.3s;
        width: 300px;
        margin: 0 auto;
        border-radius: 5px;
      }
      .card:hover {
        box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2);
      }
      .container {
        padding: 2em;
      }
      .container img {
        width: 100%;
        border-radius: 50%;
      }
      .container h1 {
        font-size: 1.5em;
        margin-bottom: 0.5em;
      }
      .container p {
        font-size: 0.9em;
        margin-bottom: 1em;
      }
      .container .btn {
        display: inline-block;
        background-color: #333;
        color: #fff;
        border: none;
        border-radius: 5px;
        padding: 0.5em 1em;
        text-decoration: none;
      }
      .container .btn:hover {
        background-color: #777;
      }
    </style>
  </head>
  <body>
    <div class="card">
      <div class="container">
        <!-- Add a profile image -->
        <img src="https://via.placeholder.com/150" alt="Profile Image">
        <!-- Your name and a short bio -->
        <h1>John Doe</h1>
        <p>Full-Stack Developer</p>
        <!-- Add links to your social media profiles -->
        <p>
          <a href="#" class="btn">GitHub</a>
          <a href="#" class="btn">LinkedIn</a>
          <a href="#" class="btn">Twitter</a>
        </p>
      </div>
    </div>
  </body>
</html>
