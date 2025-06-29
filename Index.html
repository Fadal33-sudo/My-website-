<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Random Joke Generator</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f9f9f9;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 100vh;
      margin: 0;
    }
    h1 {
      margin-bottom: 24px;
      color: #333;
    }
    #joke {
      background: #fff;
      padding: 24px 32px;
      border-radius: 8px;
      box-shadow: 0 2px 12px #00000010;
      min-height: 80px;
      min-width: 280px;
      text-align: center;
      font-size: 1.2em;
      margin-bottom: 24px;
      transition: background 0.3s;
    }
    button {
      background: #007bff;
      color: #fff;
      border: none;
      padding: 14px 28px;
      border-radius: 5px;
      font-size: 1em;
      cursor: pointer;
      font-weight: bold;
      transition: background 0.2s;
    }
    button:hover {
      background: #0056b3;
    }
    .footer {
      margin-top: 40px;
      color: #aaa;
      font-size: 0.9em;
    }
  </style>
</head>
<body>
  <h1>Random Joke Generator</h1>
  <div id="joke">Click "Get Joke" to see a random joke!</div>
  <button onclick="getJoke()">Get Joke</button>
  <div class="footer">
    Powered by <a href="https://jokeapi.dev/" target="_blank">JokeAPI</a>
  </div>
  <script>
    async function getJoke() {
      const jokeDiv = document.getElementById('joke');
      jokeDiv.textContent = 'Loading...';
      try {
        const response = await fetch('https://v2.jokeapi.dev/joke/Any');
        const data = await response.json();
        if (data.type === 'single') {
          jokeDiv.textContent = data.joke;
        } else if (data.type === 'twopart') {
          jokeDiv.textContent = data.setup + '\n\n' + data.delivery;
        } else {
          jokeDiv.textContent = 'No joke found!';
        }
      } catch (error) {
        jokeDiv.textContent = 'Failed to fetch joke. Please try again.';
      }
    }
  </script>
</body>
</html>
