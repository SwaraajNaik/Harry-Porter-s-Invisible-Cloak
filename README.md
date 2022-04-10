# Harry-Porter-s-Invisible-Cloak

Have you ever thought of making visible things invisible, just like the Harry Potter? Have 

you ever thought how does one supersede backgrounds and add effects in a movie? The cloak was 

magical and invisible in Harry Potter movie. As we know there is no magic and no invisible cloak

which exists in the world. It’s all about the graphics tricks. The concept of an invisibility cloak is 

a mixture of science, fantasy, and the collective imagination. This helps to create one’s own 

‘Invisibility Cloak. It will make use of Python and OpenCV module specifically targeting Image 

Processing and Image Segmentation to create a false sense of invisibility in the frame. It will 

explore how an object of a specific color or texture can be manipulated using the OpenCV library 

of python. To achieve this, initially we’ll be capturing and storing the backdrop frame. Thereafter 

we’ll be identifying the given-colored fabric by making use of the above-mentioned algorithms. 

Then we’ll segment out the given-colored fabric by generating a mask and then finally, we’ll 

generate the final augmented(magical) output to create Invisibility cloak. 


## *Methodology*

Steps:

1. Capture the background frame (it will take few second to read it). The main concept is interchanging the current frame picture element equivalent to 
  the cloth with the backdrop pixels, so we can obtain the magical effect of invisibility,  Thus it required to save the frame in the background.

2. Identify the chose colored cloth (cloak) by using the color detection.

3. Than use deep learning algorithm for the color and image segmentation algorithm.

4. The correct concept is to change the color-space of the picture from ‘R.G.B (Red.  Green. Blue) value to ‘H.S.V’ (Hue . Saturation . Value).
   Since, the “R.G.B values” are highly - ‘sensitive to Illumination. Thus ,the proper way,  is transforming the color space of our picture from R.G.B to H.S.V (Hue .Saturation 

   .Value). [“mask1 = mask1 + mask2”]

   Using this, we join the masks generated for both of the given color range.

5. Segmenting out the red colored fabric by generating a mask. We refine the mask & then it is further used for segmenting out the fabric from the frame.

6. Generate the final augmented(magical) output to create Invisibility cloak.

# Pre-requisite

-   Git-Hub account

-   Python 3

-   pip


# How-to-run

  - Step-1 Open the .py file in colab or jupyter notebook or pycharm
  - 
  - Step-2 Once open, run all the cells from the beginning.

  - Step-3 Finally run the **result** segment to see the results of both encoding the message in the audio file and extracting the message from the audio file.


## *Final output*



![Screenshot 2022-04-11 012626](https://user-images.githubusercontent.com/40821800/162637417-27873948-5570-4d94-a876-6105935248ec.png)

![Screenshot 2022-04-11 012723](https://user-images.githubusercontent.com/40821800/162637420-53b99b95-34cb-42d3-8adc-bae17931cc96.png)

![Screenshot 2022-04-11 012743](https://user-images.githubusercontent.com/40821800/162637423-0f0fe236-761f-4935-b286-045522be6cc8.png)



V. References

(Paper Implemented)


https://www.ijeat.org/wp-content/uploads/papers/v9i4/D7531049420.pdf
