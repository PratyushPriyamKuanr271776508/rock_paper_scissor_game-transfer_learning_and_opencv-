<h1 align="center" style="color:#2c3e50;">🎮 Rock Paper Scissors using OpenCV</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Made%20with-Python%203.9-blue?logo=python&logoColor=white" alt="Python Badge">
  <img src="https://img.shields.io/badge/OpenCV-Enabled-success?logo=opencv" alt="OpenCV Badge">
  <img src="https://img.shields.io/badge/Deep%20Learning-TensorFlow-orange?logo=tensorflow" alt="TensorFlow Badge">
</p>

---

<p>This is an interactive <strong>Rock Paper Scissors</strong> game built using <strong>OpenCV</strong> and <strong>Python</strong>. 
The player shows their hand gesture (rock, paper, or scissors) in front of the webcam, and the model predicts it using a trained CNN. 
The computer then makes its own move randomly, and the winner of each round is displayed.</p>

---

<h2 style="color:#2c3e50;">📦 Requirements</h2>

<ul>
  <li>Python 3.8 or above</li>
  <li>OpenCV (<code>cv2</code>)</li>
  <li>TensorFlow / Keras (for model training and saving)</li>
  <li>NumPy</li>
  <li>Google Colab (if running online)</li>
</ul>

---

<h2 style="color:#2c3e50;">⚙️ Setup Instructions</h2>

<ol>
  <li>Clone the repository:
    <pre><code>git clone https://github.com/&lt;your-username&gt;/rock-paper-scissors-opencv.git</code></pre>
  </li>
  <li>Navigate to the project directory:
    <pre><code>cd rock-paper-scissors-opencv</code></pre>
  </li>
  <li>Install dependencies:
    <pre><code>pip install -r requirements.txt</code></pre>
  </li>
  <li>Run the game:
    <pre><code>python rps_game.py</code></pre>
  </li>
</ol>

---

<h2 style="color:#2c3e50;">🧠 Model Training & Saving</h2>

<p>The game uses a <strong>CNN (Convolutional Neural Network)</strong> model trained on hand gesture images to predict rock, paper, or scissors.</p>

<p>Once trained, you can save the model using:</p>
<pre><code>model.save('rps_model.h5')</code></pre>

<p>Later, load it using:</p>
<pre><code>import tensorflow as tf
model = tf.keras.models.load_model('rps_model.h5')</code></pre>

---

<h2 style="color:#2c3e50;">🎮 Gameplay</h2>

<ul>
  <li>Show your hand in front of the webcam (Rock, Paper, or Scissors).</li>
  <li>The model predicts your gesture from the bounding box area.</li>
  <li>The computer randomly selects its gesture.</li>
  <li>The winner for the round is displayed instantly.</li>
  <li>After 10 rounds, the final score determines the overall winner.</li>
</ul>

---

<h2 style="color:#2c3e50;">🏆 Scoring Rules</h2>

<ul>
  <li>Rock beats Scissors 🪨✂️</li>
  <li>Paper beats Rock 📄🪨</li>
  <li>Scissors beats Paper ✂️📄</li>
  <li>Same gesture results in a Draw 🤝</li>
</ul>

---

<h2 style="color:#2c3e50;">🚀 Future Enhancements</h2>

<ul>
  <li>🔹 Integrate <strong>Mediapipe</strong> for improved real-time hand recognition.</li>
  <li>🔹 Add background subtraction for better accuracy.</li>
  <li>🔹 Introduce difficulty levels (Easy, Medium, Hard).</li>
  <li>🔹 Use voice feedback to announce results.</li>
  <li>🔹 Create a GUI version with <strong>Streamlit</strong> or <strong>Tkinter</strong>.</li>
  <li>🔹 Track player stats and performance history.</li>
</ul>

---

<h2 style="color:#2c3e50;">📁 Folder Structure</h2>

<pre><code>rock-paper-scissors-opencv/
│
├── game_play.ipynb                     # Main game logic in Jupyter/Colab
├── Model_training.ipynb                # CNN model training and testing
├── rock_paper_scissors_model.keras     # Saved CNN model
└── README.md                           # Project documentation
</code></pre>

---

<h2 style="color:#2c3e50;">📷 Sample Output</h2>

<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/3/34/Rock-paper-scissors_%28paper%29.png" width="250" alt="Rock Paper Scissors Example">
  <img src="https://upload.wikimedia.org/wikipedia/commons/5/5f/Rock-paper-scissors_%28rock%29.png" width="250" alt="Rock Paper Scissors Example">
  <img src="https://upload.wikimedia.org/wikipedia/commons/2/2f/Rock-paper-scissors_%28scissors%29.png" width="250" alt="Rock Paper Scissors Example">
</p>

---

<h2 style="color:#2c3e50;">🧑‍💻 Author</h2>

<p><strong>Pratyush Priyam Kuanr</strong><br>
Senior Software Engineer | ML & AI Enthusiast<br>
<a href="https://github.com/PratyushPriyamKuanr271776508">🔗 GitHub Profile</a> |
<a href="https://www.linkedin.com/in/pratyush-priyam-kuanr-9650b6218">🔗 LinkedIn</a>
</p>

---

<h3 align="center">⭐ If you like this project, don’t forget to star the repo!</h3>