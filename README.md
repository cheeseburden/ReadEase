<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">

</head>
<body>

  <h1>📖 ReadEase – Assistive Reader for Dyslexia</h1>

  <p>
    <strong>ReadEase</strong> is an accessibility-focused application that supports users with dyslexia by offering AI-powered tools to simplify and improve reading experiences.
  </p>

  <hr>

  <h2>🚀 Features</h2>
  <ul>
    <li><strong>🔊 Text-to-Speech:</strong> Converts text into audio to aid comprehension.</li>
    <li><strong>🖼️ OCR:</strong> Extracts text from images and PDFs.</li>
    <li><strong>✍️ Phonetic Spell Correction:</strong> Suggests improved word spellings based on phonetics.</li>
    <li><strong>🧠 Dyslexia-Friendly Font Conversion:</strong> Changes fonts and layout to improve readability.</li>
    <li><strong>📂 File Upload Support:</strong> Supports image and PDF uploads.</li>
    <li><strong>🗣️ Voice Interaction:</strong> Enables voice-based interaction for hands-free use.</li>
    <li><strong>📄 Downloadable PDFs:</strong> Users can download converted documents for offline reading.</li>
  </ul>

  <hr>

  <h2>🛠️ Tech Stack</h2>
  <ul>
    <li><strong>Backend:</strong> FastAPI (Python)</li>
    <li><strong>OCR:</strong> Tesseract / EasyOCR</li>
    <li><strong>Text-to-Speech:</strong> pyttsx3 / gTTS</li>
    <li><strong>Spell Correction:</strong> SymSpell / Hunspell / Phonetic algorithms</li>
    <li><strong>Containerization:</strong> Docker</li>
  </ul>

  <hr>

  <h2>🐳 Docker Deployment</h2>
  <pre>
    docker build -t readease-app .
    docker run -p 8000:8000 readease-app
  </pre>
  <p>Then go to <code>http://localhost:8000</code> in your browser.</p>

  <hr>

  <h2>📁 Project Structure</h2>
  <pre>
📁 ReadEase/
├── 📁 app/                 - Core application logic
├── 📄 Dockerfile           - Docker setup
├── 📄 requirements.txt     - Python dependencies
├── 📄 README.md            - This file
  </pre>

  <hr>

  <h2>✨ Future Enhancements</h2>
  <ul>
    <li>Real-time OCR using webcam input</li>
    <li>Support for .docx and .txt files</li>
    <li>Adjustable font size and contrast for readability</li>
    <li>Mobile-ready Progressive Web App (PWA)</li>
  </ul>

  <hr>

  <h2>👥 Contributors</h2>
  <ul>
    <li><a href="https://github.com/cheeseburden" target="_blank">Vishruth</a></li>
    <li><a href="https://github.com/Yashaswini-N-05" target="_blank">Yashaswini</a></li>
    <li>nishanth-sarvam</li>
    <li>Vageesh</li>
  </ul>


  <h2>💡 Why ReadEase?</h2>
  <p>
    Accessibility should be universal. ReadEase bridges the digital gap for users with dyslexia by simplifying reading through assistive technologies—because everyone deserves to read with ease.
  </p>

</body>
</html>
