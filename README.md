<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Rising Up the Ghetto</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: white;
      margin: 0;
      padding: 0;
    }

    header {
      background-color: black;
      color: gold;
      text-align: center;
      padding: 30px 10px;
    }

    section {
      padding: 30px 10%;
    }

    .playlist {
      background-color: #f9f9f9;
      padding: 20px;
      border-radius: 10px;
      margin-bottom: 30px;
    }

    .song {
      margin-bottom: 25px;
      padding: 15px;
      border-bottom: 1px solid #ccc;
    }

    audio {
      width: 100%;
      margin-top: 10px;
    }

    .buttons {
      margin-top: 10px;
    }

    .buttons a {
      display: inline-block;
      background-color: gold;
      color: black;
      padding: 8px 15px;
      margin-right: 10px;
      border-radius: 5px;
      text-decoration: none;
    }

    .contact, .comments {
      background-color: #222;
      color: white;
      padding: 30px 10%;
      margin-top: 30px;
    }

    .contact a {
      color: gold;
    }

    textarea {
      width: 100%;
      height: 100px;
      margin-top: 10px;
      border-radius: 8px;
      padding: 10px;
    }

    button {
      margin-top: 10px;
      background-color: gold;
      color: black;
      padding: 10px 20px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }

    footer {
      text-align: center;
      background-color: #111;
      color: white;
      padding: 10px;
    }
  </style>
</head>
<body>

  <header>
    <h1>Rising Up the Ghetto</h1>
    <p>Welcome to this website, home of African cool music, dancehall, hip hop, local and afro. Here is were you listen and download letest music<br> lemme bwai ghetto boss</p>
  </header>

  <section class="playlist">
    <h2>Latest Track</h2>

    <div class="song">
      <strong><br>Artist: Lemme bwai<br>Song title: Yearoso Ndi Hero<br> Genre: Hip hop</strong> 
      <audio controls>
        <source src="yearoso ndi hero.mp3" type="audio/mp3">
        Your browser does not support the audio element.
      </audio>
      <div class="buttons">
        <a href="yearoso.mp3" download>Download</a>
        <a href="#">Share</a> <a href="#">like</a>
      </div>
    </div>

    <div class="song">
      <strong>More songs coming soon...</strong>
      <p>Stay tuned for more uploads! <br> nyimbo mwakathithi</p>
    </div>
  </section>

  <section class="comments">
    <h3>Leave a Comment</h3>
    <textarea placeholder="Write your comment here..."></textarea>
    <button onclick="alert('Thanks for your comment!')">Post Comment</button>
  </section>

  <section class="contact">
    <h3>Contact for Music Upload & Promotion</h3>
    <p><strong>Phone:</strong> 0990842635</p>
    <p><strong>Email:</strong> <a href="mailto:bandamalack968@gmail.com">bandamalack968@gmail.com</a></p>
  </section>

  <footer>
    &copy; 2025 Rising Up the Ghetto. All rights reserved. Leme bwai ghetto boss
  </footer>

</body>
</html>
