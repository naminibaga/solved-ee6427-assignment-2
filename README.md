Download Link: https://assignmentchef.com/product/solved-ee6427-assignment-2
<br>
(1) Calculate two-dimensional transform of figure 1 by using row-column decomposition method with the basis function in figure 2, please show all the intermediate steps to obtain the final result.

10 10 10 10 10 10 10 10

10 10 10 10 10 10 10 10

⎛ ⎞ 20 20 20 20 20 20 20 20

⎜                                                                ⎟

⎜20 20 20 20 20 20 20 20⎟

⎜40 40 40 40 40 40 40 40⎟

⎜40 40 40 40 40 40 40 40⎟ 10 10 10 10 10 10 10 10

⎝10 10 10 10 10 10 10 10⎠

<h1>Figure 1</h1>




<h1>Figure 2</h1>

if the quantization matrix on page 6 of the lecture note “JPEG” is used, calculate the quantization output.  What is the one-dimensional output after zig-zag scanning?

<ul>

 <li>Define a character string using YOUR FULL NAME as appearing in Matriculation Card (all in capital letters and remove all spaces in your name) and follow by “VIDEOSIGNALP”.</li>

</ul>

Use arithmetic coding method in the lecture note “compression fundamental” to encode the first 8 letters of the character string. Show the steps of the divisions of the interval during arithmetic encoding the character string, and show the codeword produced by the encoding procedure.

For example, “CHA TAI” should encode “CHATAIVI”. You need to use YOUR FULL NAME as appearing in Matriculation Card (all in capital letters and remove all spaces in your name). And assign the interval (range) in alphabetical order. E.g. “A” should be assigned as the first letter in the interval. (please refer to the example in the lecture note). (Zero mark will be given if you don’t follow the rule.)

<ul>

 <li>Define a character string using YOUR FULL NAME as appearing in Matriculation Card (all in capital letters and remove all spaces in your name) and follow by “VIDEOSIGNALP”. Please remove all spaces in the string and let “A”=1, “B”=2, …, “Y”=25, “Z”=26 as an input to fill up the following 4×4 matrix. (Zero mark will be given if you don’t follow the rule.)</li>

</ul>

For example : If YOUR FULL NAME as appearing in Matriculation Card, e.g. “CHA TAI”, the 16 letters are “CHATAIVIDEOSIGNA” the corresponding numbers for the first 16 letters are “ 3  8  1  20  1  9  22  9  4  5  15  19  9  7  14  1”




<table width="180">

 <tbody>

  <tr>

   <td width="42">3</td>

   <td width="48">8</td>

   <td width="48">1</td>

   <td width="42">20</td>

  </tr>

  <tr>

   <td width="42">1</td>

   <td width="48">9</td>

   <td width="48">22</td>

   <td width="42">9</td>

  </tr>

  <tr>

   <td width="42">4</td>

   <td width="48">5</td>

   <td width="48">15</td>

   <td width="42">19</td>

  </tr>

  <tr>

   <td width="42">9</td>

   <td width="48">7</td>

   <td width="48">14</td>

   <td width="42">1</td>

  </tr>

 </tbody>

</table>




Let the 4×4 matrix (obtained from above) be a two-level discrete wavelet transform decomposition result. Applying the EZW coding scheme to the wavelet coefficients and show the encoding result. Note that four symbols in dominant pass for EZW are T (zerotree root), Z (isolated zero), P (positive) and N (negative) respectively.




(20 marks)




<ul>

 <li>Plot the rate distoration curve by changing the parameters at an H.263 encoder. To do this question, you need to <strong><u>explore the option of the tmn software by yourself.</u></strong>

  <ul>

   <li>Use the “football_cif.yuv” (can be obtained from ntulearn site) sequence of first 150 frames.</li>

   <li>Use tmn.exe (Unzip from h263.zip. It is a DOS program which requires to execute on command prompt) to generate the result.</li>

   <li>Perform experiments with different quantization parameters, try at least 20 different QPs to obtain meaning results.</li>

  </ul></li>

</ul>

Discuss your results based on the reconstructed video quality and the MSE obtained.

You may need to write a program to calculate the overall PSNR and MSE, where <em>x</em><em><sub>i</sub></em> are the original pixels and <em>x</em>ˆ<em><sub>i</sub></em> are the reconstructed pixels obtained from tmndec. Please show all the steps to obtain the results.

Plot the PSNR-Y against various bitrate as shown in figure 3.




Figure 3




Plot the MSE-Y against various bitrate as shown in figure 4.

Figure 4




Fix the bitrate to different values (at least 5 different bitrates), plot the MSE-Y against frame number as shown in the following figure 5.




Figure 5 Please comment on your results.