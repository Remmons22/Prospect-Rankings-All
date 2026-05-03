# Prospect-Rankings-All
Remmons Prospect Ranking
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>My First Website</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #0f172a;
      color: #e2e8f0;
      text-align: center;
    }
    header {
      padding: 60px 20px;
      background: #1e293b;
    }
    h1 {
      margin: 0;
      font-size: 2.5rem;
    }
    p {
      color: #94a3b8;
    }
    button {
      margin-top: 20px;
      padding: 12px 20px;
      border: none;
      background: #38bdf8;
      color: #0f172a;
      font-size: 1rem;
      cursor: pointer;
      border-radius: 8px;
    }
    button:hover {
      background: #0ea5e9;
    }
    section {
      padding: 40px 20px;
    }
  </style>
</head>
<body>

  <header>
    <h1>Welcome to My Site</h1>
    <p>Built with GitHub Pages 🚀</p>
    <button onclick="showMessage()">Click Me</button>
  </header>

  <section>
    <h2>About</h2>
    <p>This is my first website hosted for free with no ads.</p>
  </section>

  <script>
    function showMessage() {
      alert("Your site is working 🎉");
    }
  </script>

</body>
</html>
