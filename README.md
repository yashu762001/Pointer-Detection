<h1> POINTER DETECTION

<h2> Team : All Stars </h2>
<h2> Yash Mathur </h2>
<h2> Shreyas Jadhav </h2>
<h2> Hritik Bohra </h2>

<p> The Project Involves Predicting Whether there is a pointer in a video clip from BasketBall Game. </p>

<p> Our Go to Strategy : </p>

<p> The First Model we tried was a CNN(Convolutional Nueral Network). Basically from Every Video we collected 25 65x65x3 images.Then we Passed our image into a
11 Layer Network involving 4 Convolution Layers, 3 MaxPooling Layers and Remaining Dense Layers. </p>

<p> On Training This Model we got a 57.26% Accuracy on the Validation Data Set. Since Accuracy is pretty bad so we discarded this model and rather tried a better model
</p>

  <p> Our CNN Model was : </p>
<img src="https://user-images.githubusercontent.com/67051799/148288341-df54ac1d-bf22-49a8-8d1c-3b70051f050c.png" />
  
<p> The Next Model we tried was CNN + LSTM Model. CNN Takes care of learning The Spatial Features and The LSTM Network takes care of Sequence Based Learning </p>

  <p> This Model gave a 78.04 % Accuracy On the Validation Data Set. </p>
 
  <p> Since This model worked fine so we considered it for testing the Public Test Data. </p>

  <p> Accuracy On The Public Test Data 77.47%. </p>
 
  <p> CNN + LSTM Model looked something like this : </p>
    
  <img src = "https://user-images.githubusercontent.com/67051799/148290038-8d33c95b-44a5-4bd5-8362-b6ea582b1970.png" />
  <img src = "https://user-images.githubusercontent.com/67051799/148290102-a08a89c0-00f2-407c-81b0-4911e80241a7.png" />
  
  <h3> Training Losses and Accuracy Versus Number of Epochs </h3>
  
  <img src = "https://user-images.githubusercontent.com/67051799/148290468-9a155854-c385-4d00-8a62-eb5556f71432.jpg" />
  <img src = "https://user-images.githubusercontent.com/67051799/148290597-e9b0b780-4e67-4de6-94fc-58bffaa7aa03.jpg" />
  
  <h3> Model Classification Report On The Public Test Data </h3>
  
  <img src = "https://user-images.githubusercontent.com/67051799/148290788-ddae7eac-b6cc-4209-8ea5-faac53479e73.png" />
  
  <h3> ROC Curve for Model Based On Predictions Made on The Public Test Data : </h3>
  <img src = "https://user-images.githubusercontent.com/67051799/148291065-5da6da68-f016-4c93-b397-42b51c1a42c6.png" />
