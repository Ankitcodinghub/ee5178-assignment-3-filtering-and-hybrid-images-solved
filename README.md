# ee5178-assignment-3-filtering-and-hybrid-images-solved
**TO GET THIS SOLUTION VISIT:** [EE5178 Assignment 3-Filtering and Hybrid Images Solved](https://www.ankitcodinghub.com/product/ee5178-modern-computer-vision-programming-assignment-3-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;110008&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;EE5178 Assignment 3-Filtering and Hybrid Images Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (3 votes)    </div>
    </div>
&nbsp;

Note:

2. Submit a single zip file in the moodle named as PA2 Rollno.zip containing report and folders containing corresponding codes.

3. Read the problem fully to understand the whole procedure.

4. Comment your code generously.

5. Put titles to all of the plots that you will show. Also label the x-axis and y-axis.

6. Save your iPython notebook as an html file with all the plots and results and submit it along with the iPython notebook containing your code.

7. In case of any doubts, students are encouraged to use the forum in the course moodle page.

1 Filtering

In signal processing, filtering is a process of removing unwanted features or components from a signal. Most often, this means removing or suppressing some frequencies or frequency bands. Filtering operation can be linear, non-linear, space-variant or invariant.

Below, we will look at some operations that can be done on a signal. For the below operations, consider a discrete time, 1D signal X of length 16, where X = {x0,x1,x2,··· ,x15}. The output of the filtering process is a signal Y = {y0,y1,y2,··· ,y15}, the same length as X. Implement the following filtering operations on the signal X defined as xk = 3 + sin2πk/15 for k = {0,1,…,15} and 0 otherwise.

For the filters that are linear and space-invariant, verify that the convolutional implementation of the filter gives the same output as direct implementation.

a) yk = xk+1 − xk

b) yk = xk − X¯, where

c) yk = median({xl : l ∈ [k − 2 : k + 2]})

d) yk = xk+0.5 − xk−0.5 (Note: Linearly interpolate the neighboring samples to obtain signal values such as xk+0.5.)

e) yk = |xk+0.5 − xk−0.5|

f)

Tasks

1. Implement each of the filtering operations to obtain the desired output. Each of the outputs have to be the same size as the input signal.

2. For each operation, determine if these operations are linear and space-invariant.

3. Those operations that are linear and space-invariant, propose an equivalent convolution operation to implement the filtering process and also implement it.

4. For filters that are implemented via convolution, verify if the results are the same visually.

2 Filtering in Fourier Space

Filtering operations that are linear and space-invariant can be represented as a convolutional operation. Once, such a representation is obtained, we can use the Fourier property of convolutions to efficiently implement the filter in the Fourier domain.

Tasks

1. For those filters above that are linear and space-invariant, implement them in the Fourier domain.

2. Verify that the desired output from the Fourier implementation is the same as the spatial domain implementation. If there’s any difference, explain why.

3. If for any of the cases, the output from the spatial and Fourier domain implementations are different, then suggest the modification to make the outputs same. Implement the modification and re-verify if the results are the same.

3 Hybrid Images

We will write an image convolution function (image filtering) and use it to create hybrid images. The technique was invented by Oliva, Torralba, and Schyns in 2006, and published in a paper at SIGGRAPH. High frequency image content tends to dominate perception but, at a distance, only low frequency (smooth) content is perceived. By blending high and low frequency content, we can create a hybrid image that is perceived differently at different distances. A hybrid image is the sum of a low-pass filtered version of a first image and a high-pass filtered version of a second image. We must tune a free parameter for each image pair to control how much high frequency to remove from the first image and how much low frequency to leave in the second image. This is called the cut-off frequency. The paper suggests to use two cut-off frequencies, one tuned for each image, and you are free to try this too. Using a single cut-off frequency for both images should be sufficient. We will use a symmetric, zero-mean Gaussian filter for our filtering (low-pass and high-pass) operations. In our case, the cut-off frequency will represent the standard deviation of the Gaussian filter that will be used.

Process to generate a hybrid image:

(a) Implement a my filter.py function to implement the 2-D image filtering operation. Your function should:

– pad the input image with zeros before filtering.

– accept any arbitrary filter kernel with which to convolve the image. If the filter has even dimension, then raise an exception.

– Return a filtered image of the same spatial resolution as the input.

– Supports filtering of both grayscale and colour images.

(b) Implement a function to generate a Gaussian kernel of a given standard deviation. The standard deviation represents the cut-off frequency of the filter.

(c) Remove high frequencies from image1 by blurring image1 with the Gaussian filter.

(d) Remove low frequencies from image2 using a two-step process. First, remove high frequencies from image2 using the process described in (c). Then subtract the low-pass filtered image2 from the original image to leave only the high frequency components.

(e) Each of the filtered images can have image values that are smaller than 0.0 or larger than 1.0. In such cases the clip the values smaller than 0.0 to 0.0 and values larger than 1.0 to 1.0. For high pass filtered image add a constant value of 0.5 to the whole image before clipping the values to be between 0.0 and 1.0.

(f) Combine the two images to generate the hybrid image.

Once the hybrid images are successfully created, you can view it from different distances to perceive different images. A useful way to visualize this hybrid image is by progressively downsampling the image. By progressive downsampling, we remove a part of the frequency content of the signal. Which part of the frequency content is removed and why? How does this affect the visualization of the hybrid images at different resolutions?

Tasks

1. There are 7 different pairs of images in the data directory provided. For each pair, you have to generate 2 different hybrid images by considering the first image in the directory as image1 and image2 respectively. These pairs of images can be color, or grayscale and also of different resolutions. Your code should be able to handle all the different cases.

2. Use the function provided in the helpers.py file to visualize all the hybrid images at different resolutions.

3. Don’t forget to tune the cut-off frequency for each pair of hybrid images to get the most visually pleasing results.
