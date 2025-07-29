<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>MindX Booster</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>🧠 MindX Booster</h1>
    <p>Boost your brainpower, mood, and focus every day!</p>
  </header>  <main>
    <section class="features">
      <div class="card">
        <h2>Mood Tracker</h2>
        <p>Track your emotions and identify patterns.</p>
        <button onclick="showMessage('Mood Tracker coming soon!')">Open</button>
      </div><div class="card">
    <h2>Daily Brain Fact</h2>
    <p>Learn something new about your brain daily.</p>
    <button onclick="showFact()">Show Fact</button>
  </div>

  <div class="card">
    <h2>Water Reminder</h2>
    <p>Stay hydrated with regular voice prompts.</p>
    <button onclick="showMessage('Reminder set every 2 hours.')">Activate</button>
  </div>

  <div class="card">
    <h2>Daily Notes</h2>
    <p>Write your daily goals, thoughts, and tasks.</p>
    <textarea placeholder="Type your notes here..."></textarea>
    <button onclick="showMessage('Note saved!')">Save Note</button>
  </div>

  <div class="card">
    <h2>Mini Games</h2>
    <p>Challenge your brain with quick games.</p>
    <button onclick="showMessage('Coming in next update!')">Play</button>
  </div>

  <div class="card">
    <h2>Voice Assistant</h2>
    <p>Ask anything, get a reply like a smart friend.</p>
    <button onclick="startVoiceAssistant()">Talk</button>
  </div>
</section>

  </main>  <footer>
    <p>&copy; 2025 MindX Booster | All Rights Reserved</p>
  </footer>  <script src="script.js"></script></body>
</html>
