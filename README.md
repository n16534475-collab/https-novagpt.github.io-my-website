
[HTML DEVLOPMENT COASE.HTML](https://github.com/user-attachments/files/25890923/HTML.DEVLOPMENT.COASE.HTML)
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>HTML Course Website</title>
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    html, body {
      height: 100%;
    }

    body {
      font-family: Arial, sans-serif;
      background-color: #f9f9f9;
      display: flex;
      flex-direction: column;
      min-height: 100vh;
    }

    .marquee-container {
      background-color: #222;
      color: #ffd700;
      font-weight: bold;
      font-size: 16px;
    }

    marquee {
      padding: 8px 0;
    }

    header {
      display: flex;
      align-items: center;
      border: 2px solid #000;
      padding: 10px;
      gap: 10px;
      flex-wrap: wrap;
      background-color: #1a1a1a;
      color: white;
    }

    header img {
      width: 100px;
      height: 100px;
      object-fit: contain;
    }

    header h1 {
      font-size: 1.5em;
      margin: 0;
    }

    nav {
      background-color: #333;
      color: white;
      padding: 10px 20px;
      display: flex;
      align-items: center;
      justify-content: space-between;
      flex-wrap: wrap;
    }

    .nav-buttons {
      display: flex;
      gap: 10px;
    }

    .nav-buttons button {
      background-color: #4CAF50;
      border: none;
      color: white;
      padding: 8px 16px;
      font-size: 14px;
      border-radius: 40px;
      cursor: pointer;
    }

    .nav-buttons button:hover {
      background-color: #45a049;
    }

    main {
      flex: 1;
      display: flex;
    }

    .column.left {
      width: 20%;
      background-color: #e6e6e6;
      padding: 20px;
    }

    .column.left button {
      display: block;
      width: 100%;
      margin-bottom: 10px;
      padding: 10px;
      background-color: #007BFF;
      color: white;
      border: none;
      border-radius: 4px;
      font-size: 14px;
      cursor: pointer;
    }

    .column.left button:hover {
      background-color: #0056b3;
    }

    .column.right {
      width: 80%;
      background-color: #fff;
      padding: 20px;
    }

    footer {
      background-color: #1a1a1a;
      color: white;
      text-align: center;
      padding: 15px;
    }

    h2 {
      color: #333;
      margin-bottom: 10px;
    }

    p {
      margin-bottom: 16px;
    }

    table {
      width: 100%;
      border-collapse: collapse;
      margin-top: 20px;
    }

    th, td {
      border: 1px solid #ccc;
      padding: 12px;
      text-align: left;
    }

    th {
      background-color: #3498db;
      color: white;
    }

    tr:hover {
      background-color: #eaf2f8;
    }

    #infoBox {
      margin-top: 20px;
      padding: 10px;
      background-color: #dff9fb;
      border: 1px solid #7ed6df;
      display: none;
    }

    details > summary {
      padding: 4px;
      width: 200px;
      background-color: white;
      border: none;
      box-shadow: 1px 1px 2px #bbbbbb;
      cursor: pointer;
      margin-top: 20px;
    }

    details > ul {
      background-color: white;
      padding: 10px;
      margin: 0;
      box-shadow: 1px 1px 2px blue;
    }
  </style>
</head>
<body>

  <!-- TOP MARQUEE AREA -->
  <div class="marquee-container">
    <marquee behavior="scroll" direction="left">🔥 New HTML batches every Monday! Join now and start building websites!</marquee>
    <marquee behavior="scroll" direction="right">💻 Learn HTML, CSS, and Web Design — Beginner-friendly course with practice material!</marquee>
  </div>

  <!-- HEADER SECTION -->
  <header>
    <img src="C:\Users\muznuz\OneDrive\Attachments\Pictures\Screenshots\Screenshot 2025-06-22 171453.png" alt="Notepad">
    <img src="C:\Users\muznuz\OneDrive\Attachments\Pictures\Screenshots\Screenshot 2025-10-07 104957.png" alt="HTML">
    <img src="C:\Users\muznuz\OneDrive\Attachments\Pictures\Screenshots\Screenshot 2025-10-07 105022.png" alt="CSS">
    <img src="C:\Users\muznuz\OneDrive\Attachments\Pictures\Screenshots\Screenshot 2025-10-07 105132.png" alt="JavaScript">
    <h1>Learn HTML - Complete Beginner Course</h1>
  </header>

  <!-- NAVIGATION BAR -->
  <nav>
    <div class="nav-buttons">
      <a href="html.html"><button>HTML</button></a>
      <a href="curriculum.html"><button>Curriculum</button></a>
      <a href="test.html"><button>Exam</button></a>
	  <a href="model papper.html"><button>Coding Challenges</button></a>
    </div>
  </nav>

  <!-- MAIN CONTENT -->
  <main>
    <div class="column left">
      <a href="chapter wise question .html"><button>Chapter Wise Question</button></a>
      <a href="trialfor note pad.html"><button>Trial for Notepad</button></a>
      <a href="html lecture.html"><button>Lecture</button></a>
	  <a href="https://6aecddbb-5b79-44a9-8938-f16b1df3b88b-00-3svp8eg0frev2.picard.replit.dev/c/5.com"><button>Chatbot</button></a>
    </div>

    <div class="column right">
      <h2 id="Internet">What is Internet?</h2>
      <p>Internet is a global computer network which allows people across the world to access information and exchange thoughts and ideas.</p>

      <h2 id="WebBrowser">What is Web Browser?</h2>
      <p>A page containing text, images and other information accessible through the internet is called a web page. A group of related web pages is called a website. A web browser is a software application that enables a user to display and interact with web pages and websites.</p>

      <h2 id="webparts">Parts of a Web Page</h2>
      <table>
        <thead>
          <tr>
            <th>Part</th>
            <th>Purpose</th>
          </tr>
        </thead>
        <tbody>
          <tr><td>URL (Uniform Resource Locator)</td><td>It is the address of the web page. Each page has its own URL.</td></tr>
          <tr><td>HTTP (Hyper Text Transfer Protocol)</td><td>It explains how communication should occur.</td></tr>
          <tr><td>Menu Bar</td><td>Allows tasks such as save, cut, copy, paste, bookmark etc.</td></tr>
          <tr><td>Search</td><td>Allows you to search for any information on the internet.</td></tr>
          <tr><td>Most Visited</td><td>Frequently visited web pages are listed here.</td></tr>
          <tr><td>History</td><td>Stores list of visited web pages and information.</td></tr>
          <tr><td>Settings</td><td>Used to change controls and set up the program.</td></tr>
        </tbody>
      </table>

      <div id="infoBox"></div>

      <h2 id="WebPageTypes">What are the major types of Web Pages?</h2>

      <details>
        <summary>Static Web Page</summary>
        <ul>
          <li>Information in a static web page is pre-loaded and remains constant unless the author updates it.</li>
          <li>The user can interact with the website by clicking on links and accessing fixed content.</li>
          <li>There is no scope for real-time interaction between the user and the website.</li>
        </ul>
      </details>

      <details>
        <summary>Dynamic Web Page</summary>
        <ul>
          <li>In a dynamic web page, content changes based on user interaction or server-side logic.</li>
          <li>Information displayed is not static and can vary depending on user input or other factors.</li>
        </ul>
      </details>
    </div>
  </main>

  <footer>
    <p>© 2025 Learn HTML Course. All rights reserved.</p>
  </footer>

</body>
</html>
<script>
  // Simple HTML Quiz Game
  const chapters = {
    internet: {
      title: "Internet Chapter Game",
      questions: [
        {
          q: "What does Internet stand for?",
          options: ["Inter Network", "Internal Network", "International Network", "Internet Network"],
          correct: 0
        },
        {
          q: "Who invented the Internet?",
          options: ["Tim Berners-Lee", "Vint Cerf", "Steve Jobs", "Bill Gates"],
          correct: 1
        }
      ]
    },
    browser: {
      title: "Web Browser Chapter Game",
      questions: [
        {
          q: "What is a Web Browser?",
          options: ["A search engine", "Software to display web pages", "A programming language", "A server"],
          correct: 1
        },
        {
          q: "Which is NOT a web browser?",
          options: ["Chrome", "Firefox", "HTML", "Safari"],
          correct: 2
        }
      ]
    },
    webpage: {
      title: "Web Page Chapter Game",
      questions: [
        {
          q: "What does URL stand for?",
          options: ["Uniform Resource Locator", "Universal Resource Link", "Uniform Retrieve Location", "Universal Remote Link"],
          correct: 0
        },
        {
          q: "What does HTTP stand for?",
          options: ["Hyper Text Transfer Protocol", "High Transfer Text Protocol", "Hyper Test Transfer Protocol", "Home Text Transfer Protocol"],
          correct: 0
        }
      ]
    }
  };

  function startGame(chapter) {
    let score = 0;
    const chapterData = chapters[chapter];
    
    chapterData.questions.forEach((q, i) => {
      const answer = prompt(`${i + 1}. ${q.q}\n\n${q.options.map((o, idx) => `${idx + 1}. ${o}`).join('\n')}\n\nEnter answer (1-${q.options.length}):`);
      if (parseInt(answer) - 1 === q.correct) score++;
    });
    
    alert(`${chapterData.title}\n\nYour Score: ${score}/${chapterData.questions.length}`);
  }

  document.addEventListener('DOMContentLoaded', function() {
    const rightColumn = document.querySelector('.column.right');
    const gameSection = document.createElement('div');
    gameSection.style.marginTop = '30px';
    gameSection.style.padding = '20px';
    gameSection.style.backgroundColor = '#f0f8ff';
    gameSection.style.borderRadius = '8px';
    gameSection.innerHTML = `
      
    
</script>
