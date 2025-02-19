<h1>Deep Learning based approach to detect violence</h1>
<h4>We develop a violence detection system using deep learning and Flask. The system processes video footage, identifies violent behavior, and sends an alert email. We created a unique dataset comprising 1000 videos, evenly split between violence and non-violence categories, providing a balanced basis for model training. Frames were extracted from each video, resized to standard dimensions, and normalized, forming the feature set for our models. We employed various models including VGG19, VGG16, MobileNet-v2+LSTM, ResNet-50, and CNN+LSTM. Our best performing model was CNN+LSTM with an accuracy of 98%, closely followed by MobileNet-V2+LSTM at 95%. We developed a Flask application as an interface for our system, enabling real-time violence detection and enhancing user interaction. Our system identifies violent incidents, sends alert emails with detected frames and also violence location, and significantly improves response times.<br><br>
Dataset: https://drive.google.com/drive/folders/1AaHynzBMNcE4vjLQroSZDIYF304BYRI?usp=drive_link
</h4>
<h3>Accuracy Analysis of Different models</h3>
<h5>The results are visualized in a bar chart, making it easy to compare the performance of the different models. Each bar represents a model, and the height of the bar corresponds to the accuracy of that model.</h5>
<div style="text-align:center;">
    <img src="https://github.com/Nirob-0812/Violence-Detection/assets/75689692/1fca968a-b7ab-46ef-a114-7d451a8f6c8a" alt="Image Preview" width="700" height="400">
</div>
<h3>Home page of our flask application</h3>
<h5>when we run our project then we can show this interface</h5>
<div style="text-align:center;">
    <img src="https://github.com/Nirob-0812/Violence-Detection/assets/75689692/53c78495-62de-49af-ab06-8f278a1ddc12" alt="Image Preview" width="700" height="400">
</div>




