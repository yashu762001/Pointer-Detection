<h1> POINTER DETECTION

<h2> Team : </h2>
<h2> Yash Mathur </h2>
<h2> Shreyas Jadhav </h2>
<h2> Hritik Bohra </h2>

<p> The Project Involves Predicting Whether there is a pointer in a video clip from BasketBall Game. </p>

<p> Our Go to Strategy : </p>

<p> The First Model we tried was a CNN(Convolutional Nueral Network). Basically from Every Video we collected 25 65x65x3 images.Then we Passed our image into a
11 Layer Network involving 4 Convolution Layers, 3 MaxPooling Layers and Remaining Dense Layers. </p>

<p> On Training This Model we got a 57.26% Accuracy on the Validation Data Set. Since Accuracy is pretty bad so we discarded this model and rather tried a better model
</p>

<p> Our CNN Model was : 
<img src="https://user-images.githubusercontent.com/67051799/148288341-df54ac1d-bf22-49a8-8d1c-3b70051f050c.png" />
  
<p> The Next Model we tried was CNN + LSTM Model. CNN Takes care of learning The Spatial Features and The LSTM Network takes care of Sequence Based Learning </p>

  <p> This Model gave a 78.04 % Accuracy On the Validation Data Set. </p>
 
  <p> Since This model worked fine so we considered it for testing the Public Test Data. </p>

  <p> Accuracy On The Public Test Data 77.47%. </p>
 
  <p> CNN + LSTM Model looked something like this : </p>
    
      <img src = "https://user-images.githubusercontent.com/67051799/148290038-8d33c95b-44a5-4bd5-8362-b6ea582b1970.png" />
      <img src = "https://user-images.githubusercontent.com/67051799/148290102-a08a89c0-00f2-407c-81b0-4911e80241a7.png" />
