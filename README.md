## Image Classification using Resnet50 and Web API Deployment

### Overview
ML models have significantly streamlined the interoperability of applications across different languages. When a frontend developer seeks to incorporate ML Model into a web application, they only need to obtain the URL Endpoint from which the API is being served. This straightforward process enhances the accessibility and utilization of machine learning capabilities in web development.
The Goal is to create an API for Machine Learning Model so that it can be called and integrated with other applications.

## Resnet50 to API using Flask and Google Colab.
A Pre-trained Resnet50 model from Torchvision is converted to API using Flask in Google Colab. (The same can be done with our custom traimed Models as well)
An input image is passed to the model to predict and the top 5 predictions with their accuracies are posted on the webpage.

>Click on the `Input Image` button to view the imput image passed
>Click on the `Predicted Outputs` button to view the Top5 predictions with labels and score.

### The Home Page:
<img width="1440" alt="Screenshot 2024-01-09 at 11 48 05 PM" src="https://github.com/lahari21/Machine-Learning-Model-to-API/assets/62760117/521963df-dcdd-4254-af02-828ca3202b68">

### The Input Image Page:
<img width="1440" alt="Screenshot 2024-01-09 at 11 01 53 PM" src="https://github.com/lahari21/Machine-Learning-Model-to-API/assets/62760117/4a75899a-9df0-4c7b-bf3d-b013d5664cb1">

### The Predictions Page:
<img width="1440" alt="Screenshot 2024-01-09 at 11 47 51 PM" src="https://github.com/lahari21/Machine-Learning-Model-to-API/assets/62760117/137bf552-31b1-4e54-bcfd-880b3fe844d9">


