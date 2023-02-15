# 5 Days of Learning Image Processing Challenge
<img width="840" alt="image" src="https://user-images.githubusercontent.com/74296174/212342319-2a470f36-be1b-4d19-9f2a-8bb32ab2f3e4.png">

| Books and Resources | Completed |
| ------------- | ------------- |
| “AIN430 Fundamentals of Image Processing”, Ali Seydi Keçeli  | ✅ |
| [Digital Image Processing](http://sdeuoc.ac.in/sites/default/files/sde_videos/Digital%20Image%20Processing%203rd%20ed.%20-%20R.%20Gonzalez%2C%20R.%20Woods-ilovepdf-compressed.pdf) |  |
| [OpenCV Documentation](https://docs.opencv.org/3.4/) |  |


| Summaries for Chapters | Notes |
| ------------- | ------------- |
| 1. Digital Image Processing | [note](https://medium.com/@gokcenazakyol/1-what-is-digital-image-processing-image-processing-2da13b5dfa9c)|
| 2. Fundamentals of DIP | [note](https://medium.com/@gokcenazakyol/what-are-fundamentals-of-image-processing-image-processing-2-39573d87b28c)|
| 3. Image Enhancement| [note](https://medium.com/@gokcenazakyol/what-is-image-enhancement-image-processing-3-32a813087e0a)|
| 4. Spatial Filters| [note](https://medium.com/@gokcenazakyol/what-is-spatial-filtering-image-processing-4-2354215843a0)|
| 5. Frequency Domain and Fourier Transform | [note](https://medium.com/@gokcenazakyol/what-are-filtering-in-frequency-domain-and-fourier-transform-image-processing-5-6f4cace43c91)|
| 6. Sampling |[note](https://medium.com/@gokcenazakyol/what-is-sampling-image-processing-6-b54a0c217b79)|
| 7. Image Restoration | [note](https://medium.com/@gokcenazakyol/how-to-restore-images-image-processing-7-cabf1186fbc5)|
| 8. Image Pyramids and Edges |[note](https://medium.com/@gokcenazakyol/image-pyramids-and-edges-image-processing-8-20e8016f484a)|
| 9. Image Segmentation | [note](https://medium.com/@gokcenazakyol/what-is-image-segmentation-16d152c60257)|
| 10. Morphology |[note](https://medium.com/@gokcenazakyol/what-is-morphology-image-segmentation-10-c10dfdd24e41)|


| Exercise Names |Files|
| ------------- | ------------- |
| Basic OpenCV Operations| [file](https://github.com/gokcenazakyol/basic-opencv-operations/tree/master)|
| Image Enhancement | [file](https://github.com/gokcenazakyol/image-enhancement) |
| Spatial Filters | [file](https://github.com/gokcenazakyol/spatial-filters) |
| Fourier Transforms | [file](https://github.com/gokcenazakyol/fourier-transform) |


### Day 1 of 5 Days Image Processing Challenge 💫
- Digital image processing is the manipulation and analysis of digital images using techniques and algorithms. It focuses on two main tasks: improving the pictorial information for human interpretation and processing image data for storage, transmission, and representation for machine perception. The history of digital image processing can be traced back to the early 1920s, and it has been used in a variety of applications, such as image enhancement, object detection, compression, medical imaging, computer vision, and augmented reality. The key stages in digital image processing include image acquisition, enhancement, restoration, morphological processing, and segmentation. 
- I benefited from Digital Image Processing Book Chapter 1: Introduction. 
- You can find notes that I took for Digital Image Processing from [here](https://medium.com/@gokcenazakyol/1-what-is-digital-image-processing-image-processing-2da13b5dfa9c).
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
- You can access exercises for this part from [here](https://github.com/gokcenazakyol/spatial-filters).

---------------------------------------------------------------------------------------------

### Day 4 of 5 Days Image Processing Challenge 💥
- Fourier theory is any function that periodically repeats itself can be expressed as a sum of sines and cosines of different frequencies each multiplied by a different coefficient. The Fourier transform is a mathematical operation that transforms a signal from the time domain to the frequency domain. The Fourier transform can be applied to both 1-dimensional and 2-dimensional signals, such as audio and images. The inverse Fourier transform can be used to convert a signal back from the frequency domain to the spatial domain. The Discrete Fourier Transform (DFT) is used to analyze discrete signals, such as digital audio and images, and it can also be computed efficiently using the Fast Fourier Transform (FFT) algorithm. Fourier analysis can also be used in filtering an image in the frequency domain, by multiplying the DFT of an image by a filter function and then computing the inverse DFT of the result. The Convolution Theorem states that the Fourier transform of the convolution of two functions is the product of their Fourier transforms, and vice versa.
- I benefited from Digital Image Processing Book Chapter 4: Filtering in the Frequency Domain. This chapter also includes many details.
- You can find notes that I took for Fourier Transform from [here](https://medium.com/@gokcenazakyol/what-are-filtering-in-frequency-domain-and-fourier-transform-image-processing-5-6f4cace43c91). 
- Also, I reviewed the image enhancement notes and practiced with the help of OpenCV librariy. You can access exercises for this part from [here](https://github.com/gokcenazakyol/image-enhancement).

<img width="687" alt="image" src="https://user-images.githubusercontent.com/74296174/212735307-37c61144-04de-4f4e-a2bc-2dac6861e2a8.png">

---------------------------------------------------------------------------------------------

### Day 5 of 5 Days Image Processing Challenge ⚡️
- Sampling refers to the process of selecting a subset of pixels from an image to represent the entire image at a lower resolution. Reconstruction is making samples back into a continuous function. As a result of undersampling information can be lost or aliasing problem can be occured. Aliasing gives wrong appearance in the details of the low-resolution image that do not actually exist in the original high-resolution image. It can be reduced by smoothing the edges of the image before it is sampled to a lower resolution or sampling more often.
- You can find notes that I took for Sampling from [here](https://medium.com/@gokcenazakyol/what-is-sampling-image-processing-6-b54a0c217b79). 

- Image restoration is the process of removing degradation from an image, such as noise, blur, or distortion, in order to improve its overall quality. Noise in image processing refers to any unwanted or irregular variations in the intensity levels of pixels in an image. There are many different types of filters that can be used for noise removal, depending on the specific characteristics of the noise and the desired output signal. Lastly, image inpainting is the process of filling in missing or corrupted parts of an image using information from the surrounding pixels.
- You can find notes that I took for Image Restoration from [here](https://medium.com/@gokcenazakyol/how-to-restore-images-image-processing-7-cabf1186fbc5).

- Also, I reviewed the fourier transform notes and practiced with the help of OpenCV librariy. You can access exercises for this part from [here](https://github.com/gokcenazakyol/fourier-transform).


---------------------------------------------------------------------------------------------

### Bonus Part 👻

I have added summaries and exercises that I have created before to the table above.

Thank you very much for viewing this repository ☺️

