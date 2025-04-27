# me6406-homework-4-solved
**TO GET THIS SOLUTION VISIT:** [ME6406 Homework 4 Solved](https://www.ankitcodinghub.com/product/me6406-solved-4/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;122918&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;ME6406 Homework 4 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
1. Pose Estimation [1]

Figure 1(a) shows a calibration block with one circular Unit:cm 10 pocket on its top face, where the object coordinate system 10 XoYoZo is defined at one of its lower corners, and the axes

are aligned with the three orthogonal edges of the block (Fig 10

1b). An image (similar to Fig. 1b) of the component is captured by a camera at an unknown position/orientation;

Fig 1(a) Fig 1(b)

f [cm] dx’ [cm] dy’ [cm] Cx [pixel] Cy [pixel] Ncx Ncy Ncz

0.79 6 10 −4 6 10 −4   − − −

Note: The line equation au+bv+c=0 in [1] is defined on the 2D image plane, where (u, v) are the physical coordinates measured from the center of the image plane; hence, when you obtain the coefficients associated with pixel coordinates, be sure to perform appropriate conversions so that the ‘a’, ‘b’ and ‘c’ have consistent (physical) units.

b. Estimate the object pose using the circle/ellipse correspondence, the line correspondence (Results of Part 1a), and the orthogonal constraint. Use the normal vector [Ncx Ncy Ncz]T in the camera coordinates given above for the circle/ellipse correspondence. Determine the values of [R] and T.

Suggested functions: hough.m, houghpeaks.m, houghlines.m. Nonimal value of Tz is 120 cm

2. Artifical Neural Network (ANN) based on back-propagation (BP) learning

Figure 2(b) Test data Perform the following steps to demonstrate your understanding:

a. Clearly define your neural network structure (the number of inputs, outputs, and hidden layers/nodes). Provide a schematic of your chosen ANN structure.

b. Derive the weight update rule assuming a uni-polar sigmoid function for each processing element.

c. Write a Matlab program (NN_train.m) to train the two data sets in Figure 2(a). Plot the converge curve (mean squared error vs. number of epoch) to validate your ANN algorithm. Save the final trained weights in a file (NN_weights.mat) and include it with the submission of your solutions.

d. Write a Matlab program (NN_test.m) to test the three data in Figure 2(b) by reading the weights (NN_weights.mat). Your solutions should show the output values and results. Hint: The range of the activation element, sigma function, is 0~1. The output values (0, 1) correspond to the two patterns ( and

); the closer the value to two ends means closer to the corresponding patterns whereas an intermediate value represents none of both.

3. Color

I. Artificial Color Contrast (ACC): Consider two color samples [225, 88, 96], [149, 135, 134] respectively representing target and noise in Fig 3, which are to be spatially separated in color space using DoG as discussed in class so that classification can be more easily performed:

h x yi( , ) =Gc  f x yj( , )−Gs  fk (x y, )

where f j (x y, ) with (j=1, 2, 3) corresponds to RGB component

images respectively; and fk(x y, )are some linear combinations of

RGB component images to be designed. Fig 3. Chicken

a. Derive the following equations with fk(x y, ) equal to + −(R G) and + + −(R G B):

h x y1( , ) = DoG +R Gs G ha(x y, ) = DoG +R Gs  −[B G] h2(x y, ) = DoG G +Gs [2G − R] hb(x y, ) = DoG G +Gs  −[B R]

h x y3( , ) = DoG +B Gs  − −[B (R G)] hc(x y, ) = DoG +B Gs [2B − +(R G)]

b. Perform the ACC transformation (σc=1, σs=10) on sample color patterns (100×100 each) with the following combinations: 1-2-3, 1-2-c, 1-b-3, 1-b-c, a-2-3, a-2-c, a-b-3, a-b-c.

II. Color-based Image Segmentation: Color is important information. Same objects commonly have their domain color. L-a-b color system is the color-opponent space with the L lightness dimension and a-b coloropponent dimensions. The color-based image segmentation can be performed by applying the clustering method on the points in a-b domain with the post process. Follow the steps to segment the target of the RGB image ‘Chicken.jpg’.

Step 1. Transfer pixels from RGB to Lab color system.

Step 2. Apply k-means clustering on data in a-b domain with cluster number (k=3).

Step 3. Erode the segment image to filter out small fragments.

III. Principle component analysis (PCA): Use the RGB image ‘Chicken.jpg’ for the following. a. Determine the covariance matrix of data.

b. Derive the components (eigenvectors) with eigenvalues arranged in a descending order.

c. Obtain the maximum and minimum values of three component matrices. Show these three matrices (images) with linear mapping from the minimum and maximum values to the range of (0-255).

Reference:

[1] Qiang Ji, Mauro Costa, Robert Haralick, and Linda Shapiro, “An Integrated Linear Technique for Pose Estimation from Different Features,” International Journal of Pattern Recognition and Artificial Intelligence, Vol. 13, No. 5, 1999

[2] Simpson, P. (1992). Foundations of neural networks, Chapter 1 in Artificial Neural Networks, Lau, C. &amp; Sanchez-Sinencio, E. (Eds.), pp. 2-13, IEEE Press, New York, NY.

Other handouts posted in Canvas: 00_ANN2.pdf and 00_ANN03-Example.pdf
