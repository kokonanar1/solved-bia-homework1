Download Link: https://assignmentchef.com/product/solved-bia-homework1
<br>



<ol>

 <li>Define the imaging instrument response function and the point spread function (PSF) and explain their relation to the resolution of an image. Why is it convenient to assume that PSF is spatially invariant?</li>

 <li>(a) We saw that a rectangular function</li>

</ol>

is one of the key building blocks in imaging systems and image reconstruction. What is the Fourier transform of it? Please show all the steps of your derivation <strong> </strong>and explain the physical meaning of the result

<ul>

 <li>What is the Fourier Transform of a triangular function?</li>

</ul>

Please show all the steps of your derivation<strong> </strong>and explain the physical meaning of the result . Can you use the convolution theorem to derive the FT of the triangular function? If YES, show how. If NO, show why

<ul>

 <li>Show that Fourier Transforms [both in (a) and (b)] preserve all available information (use Perceval’s theorem) .</li>

</ul>

<ol start="3">

 <li>You are provided with the jupyter notebook file and the .npz file with the original and distorted images of a sample of MDA231 human breast carcinoma cells [1].

  <ul>

   <li>Can you guess the shape of the 2D PSF of this aberrated microscope?</li>

   <li>Perfom two deconvolution algorithms to restore the image from the distorted one: Wiener filter <strong> </strong>and Wiener filter with regularization .</li>

   <li>Find ready-to-use deconvolution algorithms from python libraries (two or three is enough) and compare their performance to what you have coded yourself .</li>

   <li>Compare all the results quantitatively by plotting values of the metrics MAE, PSNR, SSIM. Which deconvolution algorithm proved to work best? .</li>

  </ul></li>

</ol>

[1] Cell Tracking Challenge. 3D+Time Datasets (<a href="http://celltrackingchallenge.net/3d-datasets/">http://celltrackingchallenge. </a><a href="http://celltrackingchallenge.net/3d-datasets/">net/3d-datasets/</a><a href="http://celltrackingchallenge.net/3d-datasets/">)</a>.