<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>School Bookshop</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f2f2f2;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #007bff;
      color: white;
      padding: 20;
      text-align: center;
    }
    #book-list {
      display: flex;
      flex-wrap: wrap;
      gap: 20;
      padding: 20;
    }
    .book-card {
      background: white;
      padding: 15;
      border-radius: 10;
      box-shadow: 0 2 5 rgba(0,0,0,0.1);
      width: 200;
    }
    .form-container {
      max-width: 300;
      margin: 50 auto;
      padding: 20;
      background: white;
      border-radius: 8;
      box-shadow: 0 2 5 rgba(0,0,0,0.1);
    }
    input, button {
      width: 100%;
      padding: 10;
      margin-top: 10;
    }
    .hidden { display: none; }
  </style>
</head>
<body>
  <header>
    <h1>School Bookshop</h1>
    <div>
      <button onclick="showSection('home')">Home</button>
      <button onclick="showSection('login')">Login</button>
      <button onclick="showSection('register')">Register</button>
    </div>
  </header>

  <main>
    <!-- Home Section -->
    <section id="home-section">
      <div id="book-list"></div>
    </section>

    <!-- Login Section -->
    <section id="login-section" class="hidden">
      <div class="form-container">
        <h2>Login</h2>
        <form id="loginForm">
          <input type="text" id="login-username" placeholder="Username" required>
          <input type="password" id="login-password" placeholder="Password" required>
          <button type="submit">Login</button>
        </form>
      </div>
    </section>

    <!-- Register Section -->
    <section id="register-section" class="hidden">
      <div class="form-container">
        <h2>Register</h2>
        <form id="registerForm">
          <input type="text" id="register-username" placeholder="Username" required>
          <input type="password" id="register-password" placeholder="Password" required>
          <button type="submit">Register</button>
        </form>
      </div>
    </section>
  </main>

  <footer>
    <p style="text-align: center">&copy; 2025 School Bookshop</p>
  </footer>

  <script>
    const books = [
      { title: "Maths SS1", author: "Mr. John", price: "₦1500" },
      { title: "English Literature", author: "Mrs. Adams", price: "₦1300" },
      { title: "Physics Basics", author: "Dr. Okoro", price: "₦1800" },
      { title: "Chemistry 101", author: "Miss Jane", price: "₦1600" }
    ];

    const bookList = document.getElementById("book-list");
    books.forEach(book => {
      const card = document.createElement("div");
      card.className = "book-card";
      card.innerHTML = 
        <h3>${book.title}</h3>
        <p><strong>Author:</strong> ${book.author}</p>
        <p><strong>Price:</strong> ${book.price}</p>
        <button>Get Book</button>
      ;
      bookList.appendChild(card);
    });

    function showSection(section) {
      document.getElementById('home-section').classList.add('hidden');
      document.getElementById('login-section').classList.add('hidden');
      document.getElementById('register-section').classList.add('hidden');
      document.getElementById(section + '-section').classList.remove('hidden');
    }

    document.getElementById("loginForm").addEventListener("submit", async (e) => {
      e.preventDefault();
      const username = document.getElementById("login-username").value;
      const password = document.getElementById("login-password").value;

      const res = await fetch("http://localhost:5000/api/auth/login", {
        method: "POST",
        headers: { "Content-Type": "application/json" },
        body: JSON.stringify({ username, password })
      });

const data = await res.json();
      if (res.ok) {
        localStorage.setItem("token", data.token);
        alert("Login successful");
        showSection('home');
      } else {
        alert(data.msg);
      }
    });

    document.getElementById("registerForm").addEventListener("submit", async (e) => {
      e.preventDefault();
      const username = document.getElementById("register-username").value;
      const password = document.getElementById("register-password").value;

      const res = await fetch("http://localhost:5000/api/auth/register", {
        method: "POST",
        headers: { "Content-Type": "application/json" },
        body: JSON.stringify({ username, password })
      });

      const data = await res.json();
      if (res.ok) {
        alert("Registration successful");
        showSection('login');
      } else {
        alert(data.msg);
      }