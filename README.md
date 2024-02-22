<p align="center">
  <b><font size="8">Raisin Class Prediction with Logistic Regression</font></b>
</p>

<p align="center">
  <img src="https://github.com/SuzanKiraz/Raisin-Class-Prediction-with-Logistic-Regression/assets/84402246/c6c5f381-d302-4ac7-98e5-7d3d24f84446" alt="Raisins">
</p>

In this project, I worked with Raisin Class data, explained in detail below. I used Logistic Regression method since this is a classification problem. Also, incorporated CV, GridsearchCV and ROC to obtain best results. I modeled data with full features and with dropping some features to check the effect of mullicollinearity. 

Data Set Information:

Images of Kecimen and Besni raisin varieties grown in Turkey were obtained with CVS. A total of 900 raisin grains were used, including 450 pieces from both varieties. These images were subjected to various stages of pre-processing and 7 morphological features were extracted. These features have been classified using three different artificial intelligence techniques.

Attribute Information:

- Area: Gives the number of pixels within the boundaries of the raisin.
- Perimeter: It measures the environment by calculating the distance between the boundaries of the raisin and the pixels around it.
- MajorAxisLength: Gives the length of the main axis, which is the longest line that can be drawn on the raisin.
- MinorAxisLength: Gives the length of the small axis, which is the shortest line that can be drawn on the raisin.
- Eccentricity: It gives a measure of the eccentricity of the ellipse, which has the same moments as raisins.
- ConvexArea: Gives the number of pixels of the smallest convex shell of the region formed by the raisin.
- Extent: Gives the ratio of the region formed by the raisin to the total pixels in the bounding box.
- Class: Kecimen and Besni raisin.


