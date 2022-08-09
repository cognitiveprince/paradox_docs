# Paradox
## Content
<p align="justify">This document details what you will experience with Paradox. It will cover everything you need to know before getting started with Paradox; from the interface, to the features.</p>

## Introduction
<p align="justify">Paradox is a first of its kind software.  Paradox lets you use the more diagram-like, dataflow inspired structure to represent data processing-centric functionality. It is the next generation programming tool for everyone. Paradox is easily accessible and easy to use. It works in a diagram-like, data flow inspired structure to represent data processing-centric functionality. It uses nodes which runs codes and Paradox provides a simple framework to create them and an editor to use them.The Use cases range almost through the whole Python domain, from IoT, over machine learning, generative engineering, Raspberry Pi, web APIs, and much more. Anyone with basic Python programming language understanding can use Paradox with ease.</p>

## Background

<p align="justify">In computing, a process is the instance of a computer program that is being executed by one or many threads. It contains the program code and its activity. Depending on the operating system (OS), a process may be made up of multiple threads of execution instructions concurrentl. In Paradox the input-process-output concept is utilized on top of dataflow programming.</p>

<p align="justify">In programming we have sequential flow and data flow methods that helps determine the flow of the program. In sequential flow the function are performed in steps, an action must be triggered for the program to start; it is the traditional way of doing pragramming. In dataflow programming application are represented as a set of nodes (also called blocks) with input and/or output ports in them. It introduces a new programming paradigm that internally represents application as a directed graph, similarly to a dataflow diagram. Below we have the examples of sequential flow and dataflow progamming that can be done in Paradox.</p>
<!---->

![sequential flow programming](images/sequential-flow.jpg) Sequential Flow

![Data-flow Programming](images/data-flow-eg.jpg) Data Flow


<p align="justify">
The key benefit of Dataflow programming is that, in dataflow, more than one instruction can be executed at once. Thus, if several instructions be- come fire able at the same time, they can be executed in parallel. This simple principle provides the potential for massive parallel execution at the instruction level.</p>

<p align="justify">
DFP(Data Flow Programming) has enabled many visual programming languages that provide a more user-friendly interface so that even non-technical users can write programs. Such languages are also suited for rapid prototyping.</p>

<p align="justify">Paradox utilizes dataflow programming in Json formating so it is easy to use and mostly errorfree.</p>

## Features of Paradox
1. ### [Create clear and pretty flows](#Create-clear-and-pretty-flows)

1. ### [Built-In Interpreter](#Built-In-Interpreter)
1. ### [Python3 by default](#Python3-by-default)
1. ### [Source Code Access](#Source-Code-Access)
1. ### [Stylus support](#Stylus-support)
1. ### [Work fast with parallel computing](#work-fast-with-parallel-computing)
1. ### [Multiple Themes](#Multiple-Themes)
1. ### [Multiple Modes](#Multiple-Modes)
1. ### [Multiple Extension](#Multiple-Extension)

### 1. Create clear and pretty flows
<p align="justify">Visual Scripting is a huge part of Paradox. Paradox uses blocks and nodes that help in creating clear and pretty flow. It makes it easy to follow, easy to script for rookie programmer and experienced programmers alike.</p>

![Feature](images/feature-1.jpg)
### 2. Built-In Interpreter 
<p align="justify">Paradox uses the built-in REPL through which you can have access to the backend session and you can use its whole API as well as access your nodes. Any modifications like creating/renaming/deleting new scripts, will reactively be processed by the frontend automatically, so you can really do everything from the console. terminal ss</p>

### 3. Python3 by default
<p align="justify">Paradox has almost every python inbuilt functions integrated in it, which you can access instantly with right click of your mouse.</p>

### 4. Source Code Access
<p align="justify">In Paradox you can access the Source code implementation of the nodes you use inside the editor. You can view and overide the source code as you and the result of the change change can be viewed in real time. </p>

![Source code access](images/source-code.jpg)

### 5. Stylus support
<p align="justify">Paradox supports stylus, you can write notes into your flows by hand using a stylus pen. One effective use of this feature is that it supports clarity and adds a whole new dimension to your visual flows.</p>

### 6. Work fast with parallel computing
<p align="justify">Your work feels satisfying when your work get seem less and fast. Through simple GUI and tools to work with for developer, Programming would be more easier , simpler to code, understand and build an incredible product.</p>

### 7. Multiple Themes
<p align="justify">There are many themes available in paradox, you can change them to which ever you like. Paradox consists of multiple themes that you can work with, themes like toy, tron, ghost, blender, simple, ueli, pure dark, colorful dark, industrial, pure light and colorful light.</p>

![toy](images/toy.jpg)

![tron](images/tron.jpg)

![ghost](images/ghost.jpg)

![blender](images/blender.jpg)

![simple](images/simple.jpg)

![ueli](images/ueli.jpg)

![pure dark](images/pure-dark.jpg)

![colourful dark](images/colourful-dark.jpg)

![industrial](images/industrial.jpg)

![pure light](images/pure-light.jpg)

![colorful light](images/colourful-light.jpg)

### 8. Multiple Modes
<p align="justify">Paradox consists of two modes that you can work with, data-flow and exec-flow. Data-flow is the default mode. Anyone who want to use Paradox in any mode they like is able to do so. description data flow parallel computing exec-flow sequential computing</p>

### 9. Multiple Extension
<p align="justify">Paradox has multiple extensions for you to use, like nodes, numpy, openCV, Pandas, scikit_learn. These extension provides blocks to complete you're overal code.</p>

## Block
<p align="justify">Paradox contains every Python feature in the form of blocks. These blocks are appear by right clicking the mouse. The name of each blocks can be changed and customized as you want.</p>

### Inbuilt Block
1. val
   <p align="justify">This block allows you to input the value in your program.</p>

   ![value](images/val-and-result-block.jpg)
1. set var
    <p align="justify">This block allows you to set variables, return values from other blocks, self-contained values.</p>

    ![set var](images/set-var.jpg)
1. set vars passive
    <p align="justify">This block allows you to set constant variables meaning the values do not change.</p>
1. get var
    <p align="justify">This blocks gives the value that has been assigned to the variable.</p>

    ![get var](images/get-var.jpg)
 1. result
    <p align="justify">This block allows you to view the output that you get from you program.</p>

    ![result](images/val-and-result-block.jpg)

 1. Code
    <p align="justify">This block provides you space where you can code normaly and get the result in the terminal at the bottom of the screen and assign the input and output of a variable.</p>
 
### System Block
 1. And
    <p align="justify">This block is Python's and operator which allows you to construct compound Boolean expressions that you can use to decide the course of action of your programs. It returns True if both statements are true</p>

    ![and](images/and.jpg)
 1. IF ELSE
    <p align="justify">This block allows you to work with an if else condition where the statement executes only if the test condition is True</p>

    ![if else](images/if-else.jpg)
 1. Button
    <p align="justify">Button block is used to trigger an action.</p>

    ![button](images/for-button.jpg)
 1. CheckPoint
    <p align="justify">Checkpoint block is used to connect multiple branch and flows withing the program.</p>

    ![checkpoint](images/checkpoint.jpg)

 1. Clock
    <p align="justify">This block helps to set the number of iteration and the delay in result, it consists of a button which needs to be clicked in order to trigger the action.</p>

    ![clock](images/clock.jpg)

 ![checkpoint](images/checkpoint.jpg)
 1. Conjugate
    <p align="justify">Conjugate block helps the user to conjugate any matrix. </p>

    ![conjugate](images/conjugate.jpg)
 1. Determinant
    <p align="justify">Determinant helps to compute the detrminant of a matrix.</p>

    ![determinant](images/determinant.jpg)
 1. Do while
    <p align="justify">The do while block helps ceates do while loop where the condition is checked after executing the statement so the code is run atleat one time.</p>

    ![do while](images/do-while.jpg)
 1. Dot Product
    <p align="justify">The Dot Product block returns a dot product of two matrixes. </p>

    ![dot product](images/dot-product.jpg)
 1. Eval
    <p align="justify">This block allows you to evaluate arbitrary Python expressions from a string-based or compiled-code-based input.</p>
 1. For
    <p align="justify">This block helps create for loop for iterating over a sequence. For loop executes a block of code until the expression returns false</p>

    ![for](images/for-button.jpg)
 1. For Each
    <p align="justify">This block allows you to create a for each loop. It helps in creating control flow statement for traversing items in a collection.</p>
 1. herm
    <p align="justify">This block allows you to compute the hermatian matrix.</p>

    ![herm](images/herm.jpg)
 1. ID Matrix
    <p align="justify">This block allows you to create an identity matrix.</p>
 1. Imag 
    <p align="justify">This block allows you to extract the imaginary part of the matrixes</p>

 1. Inner
    <p align="justify">This block allows you too calculate the inner product of two matrixes.</p>

    ![inner](images/inner.jpg)
 1. Inverse
    <p align="justify">This block helps you to find inverse of matrix</p>

    ![inverse](images/inverse.jpg)
 1. Kron
    <p align="justify">This block allows you to compute the product of two arrays.</p>
 1. link IN
    <p align="justify">This block broadcast the value, the code from this block needs to be pasted in the link OUT block for them to be connected and once connected you will be able to broadcast the value.</p>

    ![link in](images/link-in.jpg)
 1. link OUT
    <p align="justify">This block listens the value broadcasted by the link IN block. You need to copy the link from link in and paste it here for the values to be linked together and you will be able to listen to the bradcasted value.</p>

    ![link out](images/link-out.png)
 1. log
    <p align="justify">This block returns the natural logarithm of a number, or the logarithm of number to base.</p>

    ![log](images/log.jpg)
 1. Matrix
    <p align="justify">This block allows you to create matrixes.</p>

    ![matrix](images/matrix%20mult%20show%20matrix.jpg)
 1. Mult
    <p align="justify">This block allows you to multiply matrixes.</p>

    ![matrix](images/matrix%20mult%20show%20matrix.jpg)
 1. nand
    <p align="justify">The 'NAND' gate is a combination of 'AND' gate followed by 'NOT' gate. helps to create boolean expression</p>

    ![nand](images/nand.jpg)
 1. nor
    <p align="justify">The NOR gate (negated OR) gives an output of 1 if both inputs are 0,it gives 0 otherwise. </p>

    ![nor](images/nor.jpg)
 1. not
    <p align="justify">The 'not' is a Logical operator in Python that will return True if the expression is False. </p>

    ![not](images/not.jpg)
 1. Null
    <p align="justify">This block creates null matrix.</p>
 1. Ones
    <p align="justify">This block returns a new array of given shape and data type, where the element's value is set to 1. </p>
 1. or
    <p align="justify">This block helps create boolean expression that returns True if one of the statements is true</p>

    ![or](images/or.jpg)
 1. Outer
    <p align="justify">This block allows you to calculate the inner product of two matrixes</p>

    ![outer](images/outer.jpg)
 1. Power
    <p align="justify">This block allows you to assign power to matrix.</p>

 1. Print
      <p align="justify">This block prints the specified message to the screen, or other standard output device.</p>

      ![print](images/print.jpg)

 1. Rand
    <p align="justify">This block creates a matrix with random values from 0 to 1. </p>
 1. Real
    <p align="justify">This block allows you to extract the real part of the matrix.</p>

 1. show matrix
    <p align="justify">This block displays the matrix.</p>

    ![show matrix](images/matrix%20mult%20show%20matrix.jpg)
 1. slider
     <p align="justify">This block allows you to produce dynamic a value with the help of a sliding indicator.</p>

     ![slider](images/slider1.jpg)

     ![slider](images/slide2.jpg)

 1. Solve
    <p align="justify">This block allows you to solve the mathematical equations easily, it returns the value according to the inputs datatype. </p>

    ![solve](images/solve.jpg)
 1. Sqrt
    <p align="justify">This block is an inbuilt function in Python programming language that returns the square root of any number.</p>

    ![sqrt](images/sqrt.jpg)
 1. store
    <p align="justify">This block allows you to sequentially store all the data provided at input in an array. A copy of the input is provided at the output.</p>

    ![store](images/store.jpg)
 1. transpose
    <p align="justify">This function permutes or reserves the dimension of the given array and returns the modified array. </p>

 1. while
    <p align="justify">This block helps set while loop where you can execute a set of statements as long as a condition is true.</p>

    ![while](images/while.jpg)
1. xnor
    <p align="justify">The XNOR gate (negated XOR) gives an output of 1 both inputs are same and 0 if both are different.</p>

    ![xnor](images/xnor.jpg)
 1. xor
    <p align="justify">This block returns 1 if one of the bits is 1 and the other is 0 else returns false.</p>

    ![xor](images/xor.jpg)

 ## Built-in Terminal
<p align="justify">Paradox has built-in terminal where you can code, enter commands and achieve outputs the same time. This terminal can be access by pulling the second tab at the bottom of your screen. The built-in terminal works the same as Python, here you can execute th ecode. </p>

![built-in terminal](images/for-button.jpg)

![built-in terminal](images/built-in-terminal.jpg)

![built-in terminal](images/built-in-terminal-output.jpg)

 ## Variable
 <p align="justify">At the right side of the Paradox UI there is a variable panel where you can initialize variables and also set the values.</p>

 ![variables](images/variables.jpg)

 ## Log
 <p align="justify">Log is the section at the bottom of Paradox, you can get to this interface by pullig the bottom tab upward; this consists of global and error sections. Global shows the variables in the script if assigned and errors as the name suggests shows the error but with paradox errors are very unlikely to happen.</p>

 ## Source Code
 <p align="justify">Paradox uses diagramatic scripting but you can also view the source for the script in each of the node and blocks, these source code are editable. You can make what ever changes you wish to make with-in the blocks. If the change is made in any particular block that change doesnot effect other blocks.You can change the functionality of the block by overiding the code.</p>

 ![source code](images/source-code.jpg)

 ## Macro 
 <p align="justify">A macro is a compile-time function that transforms a part of the program to allow functionality that cannot be expressed cleanly in normal library code. Paradox includes a macro option where you can create your custom functions/blocks. Input and output are indexed according to list,You can add parameters, inputs, outputs. 
 </p>

 ![macro](images/macro1.jpg)
 ![macro](images/macro2.jpg)
 ## Extention
 ### OpenCV
 <p align="justify">OpenCV (Open Source Computer Vision Library) is an open source computer vision and machine learning software library. OpenCV was built to provide a common infrastructure for computer vision applications and to accelerate the use of machine perception in the commercial products. Paradox has implemented OpenCV which can be used to edit and customize images as you desire. </p>

  1. Read Image
      <p align="justify">This block alows you too read image you want to display.</p>

      ![read image](images/read-display-image.png)
  1. Display image
      <p align="justify">This block allows you to display the image, you have to connect this block with the read image block. this block take the path of the image as a parameter.</p>

      ![display image](images/read-display-image.png)
  1. Adjust brightness
      <p align="juastify">This block allows you to adjust the brightness of the image as you want.by giving parameters as alpha and beta</p>

      ![adjust brigthness](images/adjust-brightness.png)
  1. Blur
      <p align="justify">This block allows you to blur the image. size, saturation of blur</p>

      ![blur](images/blur.jpg)
  1. Resize
      <p align="justify">This block allows you to change the size of the image.</p>

      ![resize](images/resize.png)
  1. Scale
      <p align="justify">This block allows you to scale the image; you can resize the details of the image. this block take the width and height of the image as the parameter.</p>

      ![scale](images/scale.jpg)
  1. Save image
      <p align="justify">This block allows you to save the image that you have made all the changes to. you have to give file name and extenssion of the image.</p>

      ![save image](images/save-image.png)
  1. Put text
      <p align="justify">This block allows you to put your desired text over the image.</p>

      1[put text](images/put-text.jpg)
  1. Histogram
      <p align="justify">This block allows you to plot a graph by taking color properties of the image.</p>
  1. Filter 2D
      <p align="justify">This block filters out the rgb value of the image. It is used to change the pixel intensity value of an image based on the surrounding pixel intensity values.</p>

      ![filter 2D](images/filter-2D.png)
  1. Convert colour
      <p align="justify">This block converts the colours of the picture from one color space to another. The most common color spaces that is used by image editors are RBG and CMYK.</p>

      ![convert color](images/convert-color.png)
  1. Rectangle
      <p align="justify">This block highlights specific size, colour, orientation of image.</p>
  1. Threshold mask
      <p align="justify">This block masks the image. It allows us to separate the foreground (i.e., the objects that we are interested in) from the background of the image.</p>
  1. Circle
      <p align="justify">This block highlights specific size, colour, orientation of image. </p>
      
      ![circle](images/circle.png)
  1. Threshold otsu
      <p align="justify"> This block uses Otsu algorithm to choose the optimal threshold value. The Otsu algorithm automatically calculates the optimal threshold to separate the two peaks by maximizing the variance between the two types of pixels .</p>

      ![threshold otsu](images/threshold-otsu.png)
  1. Bilatral filter
      <p align="justify">This block allows you to remoe the noise from the image and helps smooth out the image.</p>

      ![bilateral filter](images/Bilateral-filter.png)
  1. Threshold trunc
      <p align="justify">When pixel intensity becomes greater than threshold value it will be truncated to threshold. After this the pixel values should be set to the value which will be same as threshold value and other values will be the same.</p>

      ![threshold trunc](images/threshold-trunc.png)
  1. Haris corner detection 
      <p align="justify">The corners of an image are basically identified as the regions in which there are variations in large intensity of the gradient in all possible dimensions and directions. this block uses haris corner detection method to extract the corners from the input image and to extract features from the input image.   </p>
  1. Threshold adaptive mean
      <p align="justify"> The threshold value is the mean of the neighbourhood area minus the constant C</p>

      ![threshold adaptive mean](images/threshold-adaptive-mean.png)
  1. Image blend   
      <p>This block helps you to combine multiple images togerther.</p>
  1. Threshold to zero
      <p align="justify">This block converts all pixels having values less than threshold, the pixel intensity for these is set to zero.</p>

      ![threshold to zero](images/threshold-to-zero.png)
  1. Threshold triangle
      <p align="justify">This block uses Triangle algorithm to choose the optimal threshold value. The triangle algorithm checks the shape of the histogram.</p>

      ![threshold triangle](images/theshold-triangle.png)
  1. Threshold binary inv
      <p align="justify">In this case the intensity of pixels will be the inverse of THRESH_BINARY. That is 0 when pixel value is less than threshold else it will be white.</p>

      ![threshold binary inv](images/threshold-binary-inv.png)
  1. Closing
      <p align="justify">This block allows you to close small holes inside the foreground objects, or small black points on the object.</p>
  1. Dilate
      <p align="Justify">This block allows you to increase the white region in the image. </p>
  1. Arrowed liked
      <p align="Justify">This block helps you add an arrow in the image. You can input where to place the arrow, the color of the arrow and the thickness as well.</p>

      ![arowed line](images/arrowed-liked.jpg)
  1. Canny
      <p align="Justify">This block allows you to reduce noise in the image, find intensity gradient of the image.</p>

      ![canny](images/canny.jpg)
  1. Erode
      <p align="Justify">>This block allows you to erode away the boundaries of foreground object, the thickness or size of the foreground object decreases. </p
  1. Blank img
      <p align="Justify">This block allows you to create a blank image.</p>

      ![blank img](images/blank-img.jpg)
  1. Crop
      <p align="Justify">This block allows you to crop the image.</p>

      ![crop](images/crop.jpg)
  1. Line
      <p align="Justify">This block allows you to place a line in the image. You can input where to place the arrow, the color of the arrow and the thickness as well.</p>

      ![line](images/line.jpg)
  1. Translate
      <p align="Justify">This block allows you to shift the image along the x and y axis. You can input the x axis and y axis value where you what to shift the image.</p>

      ![translate](images/translate.jpg)
  1. Webcam Feed
      <p align="Justify">This block allows you to access your webcam and captures the image/video from your webcam.</p>
  1. Blur median
      <p align="Justify">This block allows you to blur the image using the median filter. The median filter run through each element of the signal (in this case the image) and replace each pixel with the median of its neighboring pixels</p>

      ![blur median](images/blur-median.jpg)
  1. Threshold Adaptive Gaussian
      <p align="Justify">This block </p>

      ![threshold adaptive gaussian](images/threshold-adaptive-gaussian.jpg)
  1. GreyScl Circle Detection
      <p align="Justify">This block allows you to detect circles in the image.</p>

      ![greyscl circle detction](images/greyscl-cirlce-detection.jpg)
  1. Gaussian Blur
      <p align="Justify">This block uses gaussian filter and smoothes out the image.</p>
  1. Bitwise op
      <p align="Justify">This block allows you to use the bitwise operators AND, OR, NOT and XOR,  and extract any part of the image.</p>
  1. Fourier
      <p align="Justify">this block allows you to analyze the frequency charachteristics of various filters.</p>
  1. Merge 
      <p align="Justify">This block allows you to merge the bgr values of the image that were seperated by the split color block.</p>

      ![merge](images/merge.jpg)
  1. Rotate
      <p align="Justify">This block allows you to rotate the image. You can input thee angle that you want to rotate the image in.</p>

      ![rotate](images/rotate.jpg)
  1. Split Color
      <p align="Justify">This block allows you to split the image into different channels, it takes the rgb values of the image and seperates them.</p>

      ![slpit color](images/split-color.jpg)
  1. Flip
      <p align="Justify">This block helps you to flip the image across its x-axis or y-axis.</p>

 ### Scikit learn
 <p align="justify">Scikit-learn is a free software machine learning library for the Python programming language. In general, the learning problem considers a set of n samples of data and then tries to predict properties of unknown data.</p>

 1. Logistic Model
      <p align="justify">Logistic regression classifies binary and multiclass values and helps in predicting the results. This block takes data in the form of csv file, ... and give predictiona as result.</p>

      ![logistic model](images/logistic-model.jpg)
 1. Regression Model
      <p align="justify">Regression model predicts numerical value prediction linear equation. This block takes data in the form of csv file, ... and give predictiona as result.</p>

      ![Regression-model](images/regression-model.jpg)
 1. Choose Data
      <p align="justify">This block allows you to choose data, this includes a drop down menu where you can find built in data that are available in Paradox as well as choose different that of your choice.</p>

      ![choose data](images/regression-model.jpg)
 1. Read CSV
      <p align="justify">This block allows you to read the CSV files.</p>
 1. Predict
      <p align="justify">This block helps you predict the result from the data,trend model, input data that has been provided. </p>
 1. Read Folder
      <p align="justify">This block allows you to read the folder that you want to predict.</p>
 
 