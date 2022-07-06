# IrisDuty
This repository contains all work done on Iris.
👇🏻👇🏻👇🏻👇🏻👇🏻👇🏻👇🏻👇🏻👇🏻👇🏻👇🏻👇🏻👇🏻👇🏻👇🏻👇🏻👇🏻👇🏻👇🏻👇🏻👇🏻👇🏻👇🏻👇🏻👇🏻👇🏻👇🏻👇🏻👇🏻👇🏻👇🏻
Find the edges of the circuit.tiff (any) image using the Prewitt and Canny
    methods:
 
        I = imread('circuit.tif');
        BW1 = edge(I,'prewitt');
        BW2 = edge(I,'canny');
        figure, imshow(BW1)
        figure, imshow(BW2)
.....................................................................................................
circuit.tiff

I = imread('circuit.tif');
>>  BW2 = edge(I,'canny');
>> imshow(BW2) //This function displays an edge detected picture of the original 2D picture.
>> imshow(I) //This function displays the original picture.
.....................................................................................................
Real-time commands to follow: 

Step1: Go to the folder where you've stored the picture(s)
Step2: Copy the path of the folder.
Step3: Paste the folder path on the path box of matlab. 
       All the contents of the folder will be displayed on left side of the command window (displayed).
---------------------------------------------------------------------------------------------------------
[text written after >> are the functions used]
>> ls
.                       Lena2.png               image_processing_one.m  
..                      etest.jpg               takeit.jpg              
000001.jpg              hdd.jpg                 

>> I=imread('Lena2.png');
>> BW = edge(I,'canny');
>> imshow(BW)
>> close all;
>> clear all;
..........................................................................................................

//Conversion of a 3D image to 2D image:
>> size(I)

ans =

   800   800     3 (example)

>> I1=I(:,:,1);
>> imshow(I1) //This function will display the 2D version of the 3D image.
>> BW = edge(I1,'canny');
>> imshow(BW) //This will show the edge detected picture of the 2D version of the original image(3D)

