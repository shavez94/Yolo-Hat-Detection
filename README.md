<h1>Real-Time Hat Detection</h1>

<h2>Team Members</h2>
<ul>
  <li>Shavez Ahmad Azmi - 100938606</li>
  <li>Rehan Ahmed - 100889797</li>
  <li>Aman Deep Gangwar - 100935748</li>
  <li>Kandarp Joshi - 100943058</li>
</ul>

<h2>Project Objective</h2>
<p>The objective of this project is to implement a real-time hat detection system using object detection techniques. The goal is to demonstrate the ability to build a complete end-to-end machine learning model, from data collection to making real-time predictions.</p>

<h2>Project Overview</h2>
<p>This project involves the following key steps:</p>
<ol>
  <li><strong>Dataset Creation:</strong> A custom dataset is created by capturing images through a webcam using a Python script. This ensures that the dataset is tailored to the specific problem at hand.</li>
  <li><strong>Data Labeling:</strong> The collected images are labeled using the LabelImg API, which provides bounding boxes around the objects of interest (in this case, the hats).</li>
  <li><strong>Model Selection and Transfer Learning:</strong> Instead of building an object detection model from scratch, the TensorFlow Object Detection API is used, and the concept of transfer learning is applied to leverage pre-trained models.</li>
  <li><strong>Real-Time Prediction:</strong> The trained model is used to make real-time predictions on live video feeds from the webcam, demonstrating the practical application of the developed system.</li>
</ol>
