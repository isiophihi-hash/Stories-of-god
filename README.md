# Stories-of-god
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Bible Website</title>
  <!-- Google Font -->
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&family=Roboto&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Roboto', sans-serif;
      background-color: #fff8f0;
      color: #333;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #d84315;
      color: #fff;
      padding: 25px;
      text-align: center;
      font-family: 'Playfair Display', serif;
    }
    nav {
      background-color: #ff5722;
      padding: 12px;
      text-align: center;
    }
    nav a {
      color: white;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
      font-size: 16px;
    }
    nav a:hover {
      text-decoration: underline;
    }
    main {
      padding: 25px;
      max-width: 1000px;
      margin: auto;
    }
    .tab {
      display: none;
    }
    .tab.active {
      display: block;
    }
    .tab-buttons {
      text-align: center;
      margin-bottom: 25px;
    }
    .tab-buttons button {
      background-color: #ff7043;
      color: white;
      border: none;
      padding: 12px 25px;
      margin: 0 8px;
      cursor: pointer;
      font-size: 16px;
      border-radius: 8px;
      font-family: 'Playfair Display', serif;
      transition: 0.3s;
    }
    .tab-buttons button:hover {
      background-color: #d84315;
    }
    .story, .verse {
      background-color: #fff3e0;
      padding: 20px;
      margin-bottom: 20px;
      border-left: 6px solid #d84315;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.05);
    }
    .story img {
      max-width: 100%;
      border-radius: 10px;
      margin-bottom: 15px;
    }
    .story h3 {
      font-family: 'Playfair Display', serif;
      margin-top: 0;
      color: #bf360c;
    }
    footer {
      text-align: center;
      padding: 15px;
      background-color: #d84315;
      color: white;
      font-family: 'Playfair Display', serif;
    }
  </style>
</head>
<body>
  <header>
    <h1>My Bible</h1>
    <p>Explore Stories of God and Read the Bible</p>
  </header>

  <nav>
    <a href="#">Home</a>
    <a href="#">About</a>
  </nav>

  <main>
    <div class="tab-buttons">
      <button onclick="showTab('stories')">Stories of God</button>
      <button onclick="showTab('reading')">Read the Bible</button>
    </div>

    <div id="stories" class="tab active">
      <div class="story">
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a7/Creation_Michelangelo.jpg/640px-Creation_Michelangelo.jpg" alt="Creation Story">
        <h3>Creation Story</h3>
        <p>In the beginning, God created the heavens and the earth. The earth was formless and empty, and darkness was over the surface of the deep. God said, "Let there be light," and there was light. He separated the light from the darkness and called the light "day" and the darkness "night."</p>
        <p>Over six days, God created all living things, the sun, moon, stars, and everything on earth. On the seventh day, He rested and blessed it as holy. This story shows God's power and care for creation.</p>
      </div>

      <div class="story">
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/4e/Noah%27s_Ark.jpg/640px-Noah%27s_Ark.jpg" alt="Noah's Ark">
        <h3>Noah's Ark</h3>
        <p>God saw that the world was full of wickedness, so He decided to send a great flood to cleanse it. He chose Noah, a righteous man, to build an ark to save his family and two of every animal species.</p>
        <p>Noah obeyed God's command and worked diligently to construct the ark. When the flood came, he and his family, along with the animals, were safe inside. After the waters receded, God promised never to flood the earth again, symbolized by the rainbow.</p>
        <p>This story teaches obedience, faith, and God's mercy.</p>
      </div>

      <div class="story">
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/1e/Moses_Red_Sea.jpg/640px-Moses_Red_Sea.jpg" alt="Moses and the Red Sea">
        <h3>Moses and the Red Sea</h3>
        <p>The Israelites were enslaved in Egypt, and God sent Moses to lead them to freedom. Pharaoh refused to let them go, so God sent plagues to convince him.</p>
        <p>When the Israelites reached the Red Sea, Pharaoh's army chased them. God performed a miracle by parting the sea, allowing the Israelites to cross safely. Once they were safe, the waters returned, saving them from the Egyptians.</p>
        <p>This story reminds us of God's protection and the importance of faith in Him.</p>
      </div>

      <div class="story">
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/3a/David_and_Goliath.jpg/640px-David_and_Goliath.jpg" alt="David and Goliath">
        <h3>David and Goliath</h3>
        <p>Goliath, a giant warrior, challenged the Israelites, and everyone was afraid to fight him. David, a young shepherd, trusted in God and accepted the challenge.</p>
        <p>With a sling and a single stone, David struck Goliath on the forehead, defeating him. His faith and courage inspired the Israelites, showing that God gives strength to those who trust Him.</p>
        <p>This story teaches bravery, trust in God, and that size or strength doesn't matter when God is on your side.</p>
      </div>
    </div>

    <div id="reading" class="tab">
      <div class="verse">
        <strong>John 3:16</strong> - For God so loved the world that He gave His only Son, that whoever believes in Him should not perish but have eternal life.
      </div>
      <div class="verse">
        <strong>Psalm 23:1</strong> - The Lord is my shepherd; I shall not want.
      </div>
      <div class="verse">
        <strong>Proverbs 3:5-6</strong> - Trust in the Lord with all your heart, and do not lean on your own understanding. In all your ways acknowledge Him, and He will make straight your paths.
      </div>
      <div class="verse">
        <strong>Genesis 1:1-2</strong> - In the beginning, God created the heavens and the earth. The earth was formless and empty, and darkness covered the deep waters.
      </div>
    </div>
  </main>

  <footer>
    &copy; 2025 My Bible Website
  </footer>

  <script>
    function showTab(tabId) {
      const tabs = document.querySelectorAll('.tab');
      tabs.forEach(tab => tab.classList.remove('active'));
      document.getElementById(tabId).classList.add('active');
    }
  </script>
</body>
</html>
