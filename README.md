<!DOCTYPE html>
<html lang="nl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Jesse van der Voort</title>
  
  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700&family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
  
  <style>
    /* General body styling */
    body {
      background-color: #0D0D0D;
      color: #00FFFF;
      font-family: 'Poppins', sans-serif;
      display: flex;
      flex-direction: row;
      min-height: 90vh;
      flex-wrap: wrap;
      position: relative;
    }

    /* Styling for the div box */
    div {
      background-color: #1A1A1A;
      width: 300px;
      border: 2px solid #00FFFF;
      padding: 50px;
      margin: 50px 20px 20px 20px;
      flex: 1;
      box-shadow: 0 0 15px #00FFFF;
      border-radius: 10px;
    }

    /* Header styling */
    header h1 {
      font-family: 'Orbitron', sans-serif;
      font-size: 28px;
      font-weight: 700;
      text-transform: uppercase;
      letter-spacing: 2px;
      color: #FFD700;
    }

    /* Project list styling */
    .project-list {
      background-color: #1A1A1A;
      width: 200px;
      border: 2px solid #00FFFF;
      padding: 20px;
      margin-top: 50px;
      margin-right: 20px;
      flex-shrink: 0;
      box-shadow: 0 0 15px #00FFFF;
      border-radius: 10px;
    }

    .project-list h2 {
      font-family: 'Orbitron', sans-serif;
      font-size: 22px;
      color: #FFD700;
    }

    .project-list a {
      color: #FF007F;
      text-decoration: none;
      font-size: 18px;
      transition: color 0.3s ease-in-out, text-shadow 0.3s;
    }

    .project-list a:hover {
      text-shadow: 0 0 8px #FF007F;
      color: #FFD700;
    }

    /* Contact button */
    .contact-button {
      position: absolute;
      top: 50px;
      right: 20px;
      padding: 10px 20px;
      background-color: #1A1A1A;
      color: #00FFFF;
      border: 2px solid #00FFFF;
      font-size: 18px;
      text-decoration: none;
      border-radius: 5px;
      cursor: pointer;
      transition: background 0.3s, box-shadow 0.3s;
      font-family: 'Orbitron', sans-serif;
    }

    .contact-button:hover {
      background-color: #00FFFF;
      color: #0D0D0D;
      box-shadow: 0 0 15px #00FFFF;
    }

    /* Footer styling */
    footer {
      width: 100%;
      text-align: center;
      background-color: #1A1A1A;
      padding: 10px 0;
      position: relative;
      margin-top: auto;
      font-size: 14px;
      color: #00FFFF;
      box-shadow: 0 0 10px #00FFFF;
      top: 60px;
    }
  </style>
</head>
<body>
  <div>
    <center>
      <header>
        <h1>Jesse van der Voort</h1>
      </header>
      <div>
        Mijn Naam is Jesse van der Voort en ik zit op het Vonk in Schagen.
        Ik zit momenteel in mijn eerste jaar van de opleiding Software Developer.
      </div>
    </center>
  </div>

  <div class="project-list">
    <h2>Mijn Projecten</h2>
    <ul>
      <li><a href="https://github.com/Jessew12/The-dice-website" target="_blank">Website (In progress)</a></li>
      <li><a href="C:\Users\User\Documents\Javascript\Opdracht Pokemon\Untitled-1.html" target="_blank">Pokédex</a></li>
      <li><a href="https://github.com/Jessew12/Mijn-lua-game" target="_blank">Een game</a></li>
    </ul>
    
    <h2>Programmeertalen</h2>
    <ul>
      <li>HTML & CSS</li>
      <li>JavaScript</li>
      <li>Python</li>
    </ul>
  </div>

  <a href="mailto:jesse.vandervoort@student.vonknh.nl" class="contact-button">Contact</a>

  <footer>
    <p>&copy; 2024. Alle rechten voorbehouden.</p>
  </footer>
</body>
</html>
