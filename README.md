# Colour-Quantity-Detector

<h2>Purpose of this Project</h2>
<p>The main purpose of the ‘Color Quantity Detector’ is the find the color which is most dominant in the assigned image. This works on KNN clustering Algorithm. 
</p>

<h2>Flow of Code</h2>
<ul>
<li>Importing all the necessary libraries like numpy, matplotlib, sklearn etc.</li>
<li>Assigning the number of clusters. The number of clusters will be number of “Most Prominent Color” the code will get. During the development it was observed that cluster values till 50 are considered as perform able and values above 50 are absurd. </li>
<li>Then the image is resized to make color more interpretable by the system. </li>
<li>Then applying KNN algorithm to the image and then fetching the result and converting them into values of Percentages. </li>
<li>Then an image gradient is formed with all the most prominent colours and its percentage values. </li>
<li>Post getting the gradient for all the prominent color values we then add that image gradient on the original image with displaying the most dominant color </li>
<li>An Output image file is also generated in the File Directory for View and Download of the output image. </li>
</ul>


<h2>Input Image 👇</h2>


<h2>Output Image 👇</h2>

<h2>Conclusion</h2>
<p>
For Testing we have run the same code on 2 different image files to test it for multiple input images. 
Hence we can conclude that the code runs with giving out the most prominent color in an image and also generating an output image which is of more importance as it helps user display the original image and also the most prominent colours used in the image. 
</p>
