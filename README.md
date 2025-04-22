<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>AbdoolData App</title>
  <link rel="icon" href="logo.png" type="image/png">
  <style>
    /* Global Styles */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f4;
    }

    header {
      background-color: #4CAF50;
      color: white;
      text-align: center;
      padding: 1em;
    }

    main {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 70vh;
    }

    form {
      background-color: white;
      padding: 2em;
      border-radius: 5px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    }

    input[type="email"],
    input[type="password"] {
      width: 100%;
      padding: 1em;
      margin: 0.5em 0;
      border: 1px solid #ccc;
      border-radius: 5px;
    }

    button {
      width: 100%;
      padding: 1em;
      background-color: #4CAF50;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }

    button:hover {
      background-color: #45a049;
    }

    footer {
      background-color: #4CAF50;
      color: white;
      text-align: center;
      padding: 1em;
    }
  </style>
</head>
<body>

  <header>
    <h1>Welcome to AbdoolData</h1>
  </header>

  <main>
    <form id="signup-form">
      <input type="email" id="email" placeholder="Email" required />
      <input type="password" id="password" placeholder="Password" required />
      <button type="submit">Sign Up</button>
    </form>
  </main>

  <footer>
    <p>© 2025 AbdoolData. All rights reserved.</p>
  </footer>

  <script>
    document.getElementById('signup-form').addEventListener('submit', function (e) {
      e.preventDefault(); // Prevent form submission
      
      const email = document.getElementById('email').value;
      const password = document.getElementById('password').value;

      // Here you can add the code for handling form submission
      console.log('Email:', email);
      console.log('Password:', password);
      
      // You can add a success message or redirect the user after successful submission
      alert('Registration successful!');
    });
  </script>
  
</body>
</html> 
