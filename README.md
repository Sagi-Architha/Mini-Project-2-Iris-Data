<h1 align="center">🌸 Iris Species Classification Web Application</h1>

<p align="center">
  <b>Python 3.8+</b> | <b>Flask</b> | <b>Scikit-learn</b> | <b>Deployed on Render</b>
</p>

<hr>

<h2>📌 Project Overview</h2>
<p>
This is a <b>Flask-based web application</b> that classifies Iris flower species using 
<b>K-Nearest Neighbors (KNN)</b> and <b>Gaussian Naive Bayes</b> machine learning algorithms.
The application provides an interactive dashboard where users can input flower measurements 
and receive real-time predictions along with model performance metrics.
</p>

<hr>

<h2>✨ Features</h2>

<h3>1️⃣ Interactive Prediction Interface</h3>
<ul>
<li>Input fields for:
  <ul>
    <li>Sepal Length (cm)</li>
    <li>Sepal Width (cm)</li>
    <li>Petal Length (cm)</li>
    <li>Petal Width (cm)</li>
  </ul>
</li>
<li>Toggle between KNN and Naive Bayes models</li>
<li>Real-time prediction (Setosa, Versicolor, Virginica)</li>
</ul>

<h3>2️⃣ Model Performance Dashboard</h3>
<ul>
<li>Accuracy Score</li>
<li>Classification Report (Precision, Recall, F1-score)</li>
<li>Confusion Matrix</li>
<li>Training & Testing metrics</li>
</ul>

<h3>3️⃣ Modern UI Design</h3>
<ul>
<li>Glass-morphism UI</li>
<li>Responsive (Mobile + Desktop)</li>
<li>Smooth animations</li>
<li>Interactive buttons</li>
</ul>

<hr>

<h2>🏗 Architecture</h2>

<h3>Frontend</h3>
<ul>
<li>HTML / CSS / JavaScript</li>
<li>Bootstrap 5</li>
<li>Custom Glass Morphism Styling</li>
</ul>

<h3>Backend</h3>
<ul>
<li>Flask Framework</li>
<li>Pickle (Model Loading)</li>
<li>JSON (Metrics Storage)</li>
<li>Jinja2 Templates</li>
</ul>

<hr>

<h2>🤖 Machine Learning Models</h2>

<ul>
<li><b>KNN Classifier</b> (k=3)</li>
<li><b>Gaussian Naive Bayes</b></li>
<li>Dataset: Iris Dataset (150 samples, 4 features)</li>
</ul>

<hr>

<h2>📊 Dataset Information</h2>

<table border="1" cellpadding="8">
<tr>
<th>Feature</th>
<th>Description</th>
<th>Range</th>
</tr>
<tr>
<td>Sepal Length</td>
<td>Length of sepal (cm)</td>
<td>4.3 - 7.9</td>
</tr>
<tr>
<td>Sepal Width</td>
<td>Width of sepal (cm)</td>
<td>2.0 - 4.4</td>
</tr>
<tr>
<td>Petal Length</td>
<td>Length of petal (cm)</td>
<td>1.0 - 6.9</td>
</tr>
<tr>
<td>Petal Width</td>
<td>Width of petal (cm)</td>
<td>0.1 - 2.5</td>
</tr>
</table>

<h3>Target Classes</h3>

<table border="1" cellpadding="8">
<tr>
<th>Class</th>
<th>Label</th>
<th>Samples</th>
</tr>
<tr>
<td>Iris Setosa</td>
<td>0</td>
<td>50</td>
</tr>
<tr>
<td>Iris Versicolor</td>
<td>1</td>
<td>50</td>
</tr>
<tr>
<td>Iris Virginica</td>
<td>2</td>
<td>50</td>
</tr>
</table>

<hr>

<h2>📈 Model Performance</h2>

<h3>KNN</h3>
<ul>
<li>Training Accuracy: 95%</li>
<li>Testing Accuracy: 100%</li>
</ul>

<h3>Naive Bayes</h3>
<ul>
<li>Training Accuracy: 95%</li>
<li>Testing Accuracy: 100%</li>
</ul>

<hr>

<h2>📁 File Structure</h2>

<pre>
iris-classifier/
│
├── app.py
├── requirements.txt
├── Procfile
├── templates/
│   └── index.html
├── KNN.pkl
├── Navis.pkl
├── train_knn.json
├── test_knn.json
├── train_Navia.json
└── test_Navia.json
</pre>

<hr>

<h2>🚀 Deployment on Render</h2>

<h3>1️⃣ requirements.txt</h3>

<pre>
Flask==3.1.2
scikit-learn==1.8.0
numpy==2.4.2
gunicorn==25.0.2
pandas==3.0.0
joblib==1.5.3
</pre>

<h3>2️⃣ Procfile</h3>

<pre>
web: gunicorn app:app
</pre>

<hr>

<h2>💻 Local Development</h2>

<pre>
git clone https://github.com/yourusername/iris-classifier.git
cd iris-classifier
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python app.py
</pre>

Open in browser:
<pre>http://127.0.0.1:5000/</pre>

<hr>

<h2>⚙ How It Works</h2>

<p>
User Input → Flask Route → Model Loading → Prediction → 
Species Mapping → Metrics Loading → Template Rendering → Display
</p>

<hr>

<h2>🔐 Security Considerations</h2>
<ul>
<li>Input validation</li>
<li>No sensitive data stored</li>
<li>Safe JSON parsing</li>
<li>Error handling implemented</li>
</ul>

<hr>

<h2>📱 Mobile Responsiveness</h2>
<ul>
<li>Desktop: Two-column layout</li>
<li>Tablet: Stacked layout</li>
<li>Mobile: Full-width inputs</li>
</ul>

<hr>

<h2>🎓 Educational Value</h2>
<ul>
<li>Machine Learning Implementation</li>
<li>Flask + ML Integration</li>
<li>Model Evaluation Metrics</li>
<li>Cloud Deployment (Render)</li>
</ul>

<hr>

<h2>🔮 Future Enhancements</h2>
<ul>
<li>Add Decision Tree, SVM, Random Forest</li>
<li>Data Visualization Charts</li>
<li>CSV Batch Prediction</li>
<li>Model Retraining Feature</li>
<li>REST API Endpoints</li>
</ul>

<hr>

<h2>📬 Contact</h2>
<p>
📧 sagiarchitharao@gmail.com  
</p>

<h2>🔗 Repository</h2>
<p>
GitHub: 
<a href="https://github.com/Sagi-Architha/Mini-Project-2-Iris-Data/tree/main">
Mini-Project-2-Iris-Data
</a>
</p>

<hr>

<h3 align="center">⭐ If you like this project, give it a star!</h3>
