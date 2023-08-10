# Car Defect System Segmentation and Detection
This project focuses on developing a car defect system that performs segmentation and detection of car defects using the YOLOv8 Custom Training. We have prepared our own custom dataset by labeling car images with defects using the Roboflow tutorial. The system is implemented as a Streamlit application, which takes a car image as input and predicts the defects present in the image.

### Demo Video

## Demo Video

<a href="https://www.loom.com/share/cf63197a049a408a9c7acd8a77531968?sid=6604425b-3992-425e-8b56-18a47511f723">
  <img src="BUTTON_IMAGE_URL" alt="Watch the Loom Video" width="200"/>
</a>




### Custom Dataset Preparation
To train our model, we created a custom dataset consisting of car images with annotated defect labels. We used the Roboflow tutorial to label our dataset, which provided an efficient and accurate way to annotate car defects. The labeled dataset was then used for training the YOLOv8 model.

### YOLOv8 Object Segmentation & Detection
We utilized the YOLOv8 algorithm for object detection, which is a state-of-the-art deep learning model specifically designed for real-time object detection. YOLOv8 offers high accuracy and fast processing times, making it well-suited for our car defect system. By training the YOLOv8 model on our custom dataset, we enable it to recognize and localize various car defects with high precision.

### Streamlit Application
Our car defect system is implemented as a Streamlit application, which provides a user-friendly interface for users to interact with the model. The application allows users to upload an image of a car and initiates the defect detection process. The YOLOv8 model analyzes the image and predicts the presence and location of defects, providing an output that highlights the detected defects on the car image.

### Usage
To use the car defect system, follow these steps:

Install the required dependencies listed in the requirements.txt file.
Run the Streamlit application by executing the command streamlit run app.py in your terminal.
Access the application through your web browser by visiting the provided local URL.
Upload an image of a car that you want to analyze for defects.
Wait for the YOLOv8 model to process the image and generate predictions.
The application will display the input image with the detected defects highlighted.

Thank's If you want to support me then,
<p><a href="https://www.buymeacoffee.com/numankhan"> <img align="left" src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" height="50" width="210" alt="numankhan" /></a></p><br><br>
