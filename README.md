# 5 Days of Learning Image Processing Challenge
<img width="840" alt="image" src="https://user-images.githubusercontent.com/74296174/212342319-2a470f36-be1b-4d19-9f2a-8bb32ab2f3e4.png">

| Books and Resources | Completed |
| ------------- | ------------- |
| “AIN430 Fundamentals of Image Processing”, Ali Seydi Keçeli  | |
| [Digital Image Processing](http://sdeuoc.ac.in/sites/default/files/sde_videos/Digital%20Image%20Processing%203rd%20ed.%20-%20R.%20Gonzalez%2C%20R.%20Woods-ilovepdf-compressed.pdf) |  |
| [OpenCV Documentation](https://docs.opencv.org/3.4/) |  |

| Exercise Name |File|
| ------------- | ------------- |
| Basic OpenCV Operations| [file](https://github.com/gokcenazakyol/basic-opencv-operations/tree/master)|


### Day 1 of 5 Days Image Processing Challenge 💫
- Digital image processing is the manipulation and analysis of digital images using techniques and algorithms. It focuses on two main tasks: improving the pictorial information for human interpretation and processing image data for storage, transmission, and representation for machine perception. The history of digital image processing can be traced back to the early 1920s, and it has been used in a variety of applications, such as image enhancement, object detection, compression, medical imaging, computer vision, and augmented reality. The key stages in digital image processing include image acquisition, enhancement, restoration, morphological processing, and segmentation. 
- I benefited from Digital Image Processing Book Chapter 1: Introduction. 
- You can find notes that I took for Digital Image Processing from [here](https://github.com/gokcenazakyol/basic-opencv-operations/tree/master).
--------------------------------------------------------------------------------------------
### Day 2 of 5 Days Image Processing Challenge 📈
- The human visual system allows humans to see and interpret the visual world. Brightness adaptation helps us see objects clearly in different lighting conditions, but at any one time we can only discriminate between a smaller number of different light levels than we can perceive. Digital images are composed of pixels, each storing a value. Quantization is the process of converting a continuous analog signal into a digital representation, and saturation and noise can limit the dynamic range of an imaging system. Spatial resolution refers to the smallest discernable detail in an image, and intensity level resolution refers to the number of levels used to represent an image, with a higher number resulting in more detail. The most common number of bits used to store each intensity level is 8.
- I benefited from Digital Image Processing Book Chapter 2: Digital Image Fundamentals, and [OpenCV Documentation](https://docs.opencv.org/3.4/d3/df2/tutorial_py_basic_ops.html). 
- You can find notes that I took for Fundamentals of Image Processing from [here](https://medium.com/@gokcenazakyol/what-are-fundamentals-of-image-processing-image-processing-2-39573d87b28c).
- You can access exercises for this part from [here](https://github.com/gokcenazakyol/basic-opencv-operations/tree/master).
<img width="271" alt="image" src="https://user-images.githubusercontent.com/74296174/212476289-0a75a7f2-85e3-4034-abf9-4e9ae7abf71c.png">

- Image enhancement is the process of making images more useful. Techniques can be divided into those that operate in the spatial domain and those that operate in the frequency domain. Basic spatial domain image enhancement operations can be reduced to the form g(x,y) = T[f(x,y)], where f(x,y) is the input image, g(x,y) is the processed image and T is some operator defined over some neighborhood of (x,y). Point processing techniques, such as negative images, thresholding and grey level transformations, manipulate the pixels of an image directly. Techniques include histogram equalization and matching adjust the distribution of grey levels in an image to improve contrast.
- I benefited from Digital Image Processing Book Chapter 3: Intensity Transformations and Spatial Filtering.
- You can find notes that I took for Image Enhancement from [here](https://medium.com/@gokcenazakyol/what-is-image-enhancement-image-processing-3-32a813087e0a).
---------------------------------------------------------------------------------------------

### Day 3 of 5 Days Image Processing Challenge 🎯
- Spatial filtering is a technique used to enhance or extract features from an image, such as edges or textures, and can be done using linear or nonlinear operations. Smoothing spatial filters are useful for removing noise from images and highlighting gross detail. Gaussian filters are a type of smoothing filter that remove high frequency components from an image. Correlation and convolution are closely related concepts in linear spatial filtering, with correlation being the process of moving a filter mask over an image and computing the sum of products at each position and convolution being similar, but with the filter rotated 180 degrees. Sharpening spatial filters are used to highlight fine details, remove blurring, and highlight edges in images. The first derivative measures the difference between subsequent values and the second derivative takes into account values before and after the current value. The second derivative is more useful for image enhancement because it gives a stronger response to fine details and has a simpler implementation. A commonly used sharpening filter is the Laplacian filter which highlights edges and other discontinuities. 
- I benefited from Digital Image Processing Book Chapter 3: Intensity Transformations and Spatial Filtering. I saw that there are many other details in this chapter, so after this challenge, I will go back and read again.
- You can find notes that I took for Spatial Filters from [here](https://medium.com/@gokcenazakyol/what-is-spatial-filtering-image-processing-4-2354215843a0).

