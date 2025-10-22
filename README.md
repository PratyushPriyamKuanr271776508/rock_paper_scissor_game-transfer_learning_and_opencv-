<!DOCTYPE html>

<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Rock Paper Scissors - OpenCV Project</title>
  <style>
    body { font-family: Arial, sans-serif; line-height: 1.6; background-color: #f8f9fa; color: #333; margin: 20px; }
    h1, h2, h3 { color: #2c3e50; }
    code, pre { background: #f1f1f1; padding: 4px 8px; border-radius: 4px; }
    .section { margin-bottom: 20px; }
    ul { margin-left: 20px; }
    a { color: #2980b9; }
  </style>
</head>
<body>
  <h1>🎮 Rock Paper Scissors using OpenCV</h1>
  <p>This is an interactive <strong>Rock Paper Scissors</strong> game built using <strong>OpenCV</strong> and <strong>Python</strong>. The player shows their hand gesture (rock, paper, or scissors) in front of the webcam, and the model predicts it. The computer then makes its move, and the winner is decided.</p>

  <div class="section">
    <h2>📦 Requirements</h2>
    <ul>
      <li>Python 3.8 or above</li>
      <li>OpenCV (<code>cv2</code>)</li>
      <li>TensorFlow / Keras (for model training and saving)</li>
      <li>NumPy</li>
      <li>Google Colab (if running online)</li>
    </ul>
  </div>

  <div class="section">
    <h2>⚙️ Setup Instructions</h2>
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
  </div>

  <div class="section">
    <h2>🧠 Model Training & Saving</h2>
    <p>The game uses a CNN (Convolutional Neural Network) model to predict hand gestures. Once trained, you can save the model as:</p>
    <pre><code>model.save('rps_model.h5')</code></pre>
    <p>Later, load it using:</p>
    <pre><code>model = tf.keras.models.load_model('rps_model.h5')</code></pre>
  </div>

  <div class="section">
    <h2>🎮 Gameplay</h2>
    <ul>
      <li>Show your hand in front of the webcam (Rock, Paper, or Scissors).</li>
      <li>The model will predict your gesture.</li>
      <li>The computer randomly selects its gesture.</li>
      <li>The winner of each round is displayed on screen.</li>
      <li>Final score is shown after the game ends.</li>
    </ul>
  </div>

  <div class="section">
    <h2>🚀 Future Enhancements</h2>
    <ul>
      <li>Add real-time gesture recognition using Mediapipe for better accuracy.</li>
      <li>Include background removal to detect gestures more effectively.</li>
      <li>Implement difficulty levels (Easy, Medium, Hard).</li>
      <li>Use voice feedback to announce game results.</li>
      <li>Create a Streamlit or Tkinter GUI version.</li>
      <li>Save player statistics for future sessions.</li>
    </ul>
  </div>

  <div class="section">
    <h2>📁 Folder Structure</h2>
    <pre><code>rock-paper-scissors-opencv/
│
├── game_play.ipynb               # Main game logic
├── Model_training.ipynb      # Notebook for model training
  </div>

  <div class="section">
    <h2>🧑‍💻 Author</h2>
    <p><strong>Pratyush Priyam Kuanr</strong><br>
    Senior Software Engineer | ML & AI Enthusiast<br>
    <a href="https://github.com/&lt;your-username&gt;">GitHub Profile</a></p>
  </div>
</body>
</html>
