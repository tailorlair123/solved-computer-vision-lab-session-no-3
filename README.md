Download Link: https://assignmentchef.com/product/solved-computer-vision-lab-session-no-3
<br>



<strong> </strong>




<h1>Edge detection and Hough Transform</h1>




The following items are the steps that you have to do in this lab session:




<ol>

 <li>Write a MATLAB function that implements the Laplacian of Gaussian Operator:</li>

</ol>

o sample and display the Laplacian of Gaussian filter with different spatial supports and standard deviations (e.g. <em>sd</em>=1 and <em>sd</em>=3.5).




<ul>

 <li>Convolve the test image <em>jpg</em> with the previous LoG filters   and display the results.</li>

</ul>




<ul>

 <li>Test the edge detection algorithm based on LoG with the image <em>jpg</em> by varying the standard deviation of the kernel and the threshold (e.g. 0 and a significant value).</li>

</ul>

o First, to detect zerocrossings and display it. To detect zerocrossings:

<ul>

 <li>scan along each row, record an edge point at the location of the zerocrossing; § then, do the same for each column.</li>

</ul>

o Then to apply a threshold on the slope of the zerocrossings and to display it.

<ul>

 <li>Compare your results with the ones obtained by using the MATLAB function <em>edge(‘log’,…)</em>.</li>

</ul>




<ol start="2">

 <li>Detect straight lines in the test images (<em>jpg</em> and <em>highway2.jpg</em>). Suggestions: (i) you can use and modify the M-file we used during the lecture; (ii) for <em>highway1.jpg </em>to set 4 peaks in <em>houghpeaks()</em>;for <em>highway2.jpg </em>to set 5 peaks and <em>‘NHoodSize’</em>, [21 21] in <em>houghpeaks()</em>.</li>

</ol>










<strong>Notes: </strong>

<ul>

 <li>You have to write a report that describes your work and the obtained results (please include the figures). In the report you must indicate all the surnames of the participants (not other names, e.g. the teachers).</li>

 <li>About the code:

  <ul>

   <li>You have to use relative paths. o You have to write and use functions.</li>

   <li>You have to provide us a main script to test your code.</li>

  </ul></li>

 <li>The code must be uploaded as M-files. All the files (M-files, images, and report) have to be compressed in a single file named “surnames_labxx.zip/tgz” (all the surnames of the participants have to be indicated), and then the compressed file has to be uploaded.</li>

</ul>