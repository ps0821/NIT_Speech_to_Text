<h1 style="font-size: 3em; font-weight: bold;">🗣️ Speech-to-Text Converter</h1>

<h1><b>Overview</b></h1>

The Speech-to-Text Converter is a machine learning project designed to accurately convert spoken language into written text using advanced deep learning techniques. This project leverages powerful speech recognition models to achieve high accuracy in transcription, making it suitable for applications in accessibility tools, automated transcription services, and more.

<h1><b>Table of Contents</b></h1>
<br>
📖 Introduction<br>
✨ Features<br>
💻 Tech Stack<br>
🚀 Setup<br>
🔧 Usage<br>
🤝 Contributing<br>
📜 License<br>

<h1><b>Introduction</b></h1>

The development of Speech-to-Text (STT) technology is transforming human-machine interaction by enabling natural communication. This project aims to create a robust STT system that accurately transcribes speech in real-time, addressing challenges related to accents, noise, and variations in speech patterns.

<h1><b>Features</b></h1>
<b>High Accuracy:</b> Utilizes deep learning methods to achieve superior transcription accuracy across different languages.<br>
<b>Real-Time Transcription:</b> Converts spoken language to text instantly, enabling interactive applications.<br>
<b>Robust Error Handling:</b> Effectively manages errors during speech recognition to ensure smooth operation.<br>
<b>User-Friendly Interface:</b> Simple GUI allows users to select audio files easily for conversion.<br>

<h1><b>Tech Stack</b></h1>

Programming Language: Python<br>
Libraries:<br>
- TensorFlow<br>
- Keras<br>
- NumPy<br>
- Matplotlib<br>
- Tkinter<br>
Dataset: Various audio datasets for training and testing speech recognition models.<br>

<h1><b>Setup</b></h1>

<b>Prerequisites:</b><br>
Python 3.x<br>
<br>
<b>Installation:</b><br>
Clone the Repository:<br>
<pre><code>git clone https://github.com/ps0821/Speech-to-Text-Converter.git
cd Speech-to-Text-Converter</code></pre>

Create a Virtual Environment:<br>
<pre><code>python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`</code></pre>

Install Dependencies:<br> 
Create a `requirements.txt` file with the following contents:<br>
<pre><code>tensorflow
keras
numpy
matplotlib
tkinter
SpeechRecognition</code></pre>

Then run:<br>
<pre><code>pip install -r requirements.txt</code></pre>

<h1><b>Usage</b></h1>
<b>Training the Model:</b> Run the Jupyter Notebook (`Speech_to_Text_Conversion.ipynb`) to train the model on the audio dataset.<br>
<b>Testing the Model:</b> Use the GUI to select an audio file and convert it to text.<br>
<b>Visualizing Results:</b> Analyze the model's performance and view the converted text in the output.<br>

<h1><b>Execution Screenshots</b></h1>
![image](https://github.com/user-attachments/assets/aea9bb8b-4507-475c-b4fe-5dc1af54ab42)




<h1><b>Contributing</b></h1>
Contributions are welcome! Please follow these steps:<br>
- Fork the repository.<br>
- Create a new branch (git checkout -b feature/your-feature-name).<br>
- Commit your changes (git commit -m 'Add some feature').<br>
- Push to the branch (git push origin feature/your-feature-name).<br>
- Open a pull request.<br>

<h1><b>License</b></h1>
This project is licensed under the MIT License. See the LICENSE file for details.<br>
