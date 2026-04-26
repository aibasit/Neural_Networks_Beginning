<h1 align="center">Making of Neural Networks with TensorFlow</h1>

<p align="center">
  <b>A beginner-friendly deep learning project demonstrating how neural networks learn simple mathematical relationships using TensorFlow and Keras.</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python" />
  <img src="https://img.shields.io/badge/TensorFlow-Deep%20Learning-orange?style=for-the-badge&logo=tensorflow" />
  <img src="https://img.shields.io/badge/Keras-Neural%20Networks-red?style=for-the-badge&logo=keras" />
  <img src="https://img.shields.io/badge/Google%20Colab-Notebook-yellow?style=for-the-badge&logo=googlecolab" />
</p>

<hr>

<h2>📌 Project Overview</h2>

<p>
This repository contains two Jupyter/Google Colab notebooks focused on the fundamentals of building neural networks.
The project explains how a neural network learns a simple linear function:
</p>

<pre>
Y = 2X - 1
</pre>

<p>
The notebooks start from a basic single-layer neural network and gradually move toward multi-layer deep neural networks.
The main goal is to understand how models are defined, trained, evaluated, and manually interpreted through learned weights and biases.
</p>

<hr>

<h2>📂 Repository Files</h2>

<table>
  <tr>
    <th>File Name</th>
    <th>Description</th>
  </tr>
  <tr>
    <td><b>Lecture4_First_NeuralNetwork.ipynb</b></td>
    <td>
      Introduces a single-layer neural network using TensorFlow and Keras.
      It trains the model on sample data, observes predictions, visualizes results, and compares actual vs predicted values.
    </td>
  </tr>
  <tr>
    <td><b>2_Multi_layer_Neural_Network_(DNN).ipynb</b></td>
    <td>
      Builds a multi-layer neural network with dense layers.
      It explores how deeper networks learn the same function and how weights and biases contribute to the final prediction.
    </td>
  </tr>
</table>

<hr>

<h2>🧠 Concepts Covered</h2>

<ul>
  <li>Single-layer neural network</li>
  <li>Multi-layer neural network / Deep Neural Network</li>
  <li>Dense layers in Keras</li>
  <li>Feed-forward neural networks</li>
  <li>Model compilation using optimizer and loss function</li>
  <li>Stochastic Gradient Descent optimizer</li>
  <li>Mean Squared Error loss</li>
  <li>Training using epochs</li>
  <li>Prediction on unseen data</li>
  <li>Weights and bias interpretation</li>
  <li>Manual computation of neural network output</li>
  <li>Visualization of actual and predicted values</li>
</ul>

<hr>

<h2>🛠️ Technologies Used</h2>

<ul>
  <li>Python</li>
  <li>TensorFlow</li>
  <li>Keras</li>
  <li>NumPy</li>
  <li>Matplotlib</li>
  <li>Google Colab / Jupyter Notebook</li>
</ul>

<hr>

<h2>⚙️ How the Model Works</h2>

<p>
The model is trained on a small dataset where each input value <b>X</b> follows the relationship:
</p>

<pre>
Y = 2X - 1
</pre>

<p>
For example:
</p>

<table>
  <tr>
    <th>X</th>
    <th>Y</th>
  </tr>
  <tr>
    <td>-1</td>
    <td>-3</td>
  </tr>
  <tr>
    <td>0</td>
    <td>-1</td>
  </tr>
  <tr>
    <td>1</td>
    <td>1</td>
  </tr>
  <tr>
    <td>2</td>
    <td>3</td>
  </tr>
  <tr>
    <td>3</td>
    <td>5</td>
  </tr>
  <tr>
    <td>4</td>
    <td>7</td>
  </tr>
</table>

<p>
After training, the neural network learns this pattern and predicts the output for new input values.
For example, when <b>X = 10</b>, the expected output is approximately:
</p>

<pre>
Y = 19
</pre>

<hr>

<h2>📘 Notebook 1: First Neural Network</h2>

<p>
The first notebook explains the most basic neural network structure using one dense layer with one neuron.
It demonstrates how a simple neural network can learn a mathematical function from data.
</p>

<h3>Main Steps:</h3>

<ul>
  <li>Import TensorFlow, Keras, NumPy, and Matplotlib</li>
  <li>Define a single dense layer</li>
  <li>Compile the model using SGD and Mean Squared Error</li>
  <li>Train the model for 500 epochs</li>
  <li>View learned weights and bias</li>
  <li>Predict output for new input values</li>
  <li>Visualize actual and predicted results</li>
</ul>

<hr>

<h2>📗 Notebook 2: Multi-layer Neural Network</h2>

<p>
The second notebook extends the concept by building a deeper neural network with multiple dense layers.
It shows how a two-layer neural network can learn the same function and produce predictions close to the expected output.
</p>

<h3>Model Architecture:</h3>

<ul>
  <li>First dense layer with 2 neurons</li>
  <li>Second/output dense layer with 1 neuron</li>
</ul>

<p>
The notebook also explains how to manually calculate the final output using learned weights and biases,
which helps in understanding what happens inside a neural network.
</p>

<hr>

<h2>🧪 Additional Exercises</h2>

<p>
The notebooks also include additional exercises to strengthen understanding of neural networks, including:
</p>

<ul>
  <li>Training a neural network with two input features</li>
  <li>Learning the function <b>Y = 2X1 - X2 + 2</b></li>
  <li>Building a deeper neural network with more hidden layers</li>
  <li>Comparing model error with respect to training iterations</li>
  <li>Changing the learning rate and observing its effect on error</li>
  <li>Comparing errors across different neural network architectures</li>
</ul>

<hr>

<h2>📊 Key Learning Outcomes</h2>

<ul>
  <li>Understand how neural networks learn from data</li>
  <li>Learn how weights and biases are updated during training</li>
  <li>Understand the role of optimizer and loss function</li>
  <li>Compare single-layer and multi-layer neural networks</li>
  <li>Use TensorFlow and Keras to build beginner-level deep learning models</li>
  <li>Visualize predictions and training behavior</li>
</ul>

<hr>

<h2>🚀 How to Run This Project</h2>

<ol>
  <li>Clone this repository:</li>
</ol>

<pre>
git clone https://github.com/your-username/your-repository-name.git
</pre>

<ol start="2">
  <li>Open the notebooks in Google Colab or Jupyter Notebook.</li>
  <li>Install required libraries if needed:</li>
</ol>

<pre>
pip install tensorflow numpy matplotlib
</pre>

<ol start="4">
  <li>Run each cell step by step.</li>
  <li>Observe the model training, predictions, weights, and visualizations.</li>
</ol>

<hr>

<h2>📈 Expected Result</h2>

<p>
After training, the neural network should learn the relationship between input and output values.
For example:
</p>

<pre>
Input: 10
Predicted Output: Approximately 19
</pre>

<p>
This shows that the model has successfully learned the function:
</p>

<pre>
Y = 2X - 1
</pre>

<hr>

<h2>💡 Why This Project is Important</h2>

<p>
This project is a strong starting point for anyone learning deep learning.
Instead of directly jumping into complex datasets, it explains the foundation of neural networks using simple numerical data.
This makes it easier to understand how neural networks actually learn patterns.
</p>

<hr>

<h2>📌 Future Improvements</h2>

<ul>
  <li>Add loss curves for better training visualization</li>
  <li>Compare different optimizers such as Adam, RMSprop, and SGD</li>
  <li>Experiment with different learning rates</li>
  <li>Add more hidden layers and compare performance</li>
  <li>Apply the same concepts to real-world datasets</li>
</ul>

<hr>

<h2>🙋‍♂️ Author</h2>

<p>
<b>Abdul Basit</b><br>
AI Engineer | Deep Learning | Computer Vision | Neural Networks
</p>

<p>
GitHub: <a href="https://github.com/aibasit">github.com/aibasit</a>
</p>

<hr>

<h2>⭐ Support</h2>

<p>
If you found this project helpful, consider giving it a star ⭐ on GitHub.
</p>
