# ALPR
##Automatic License Plate Recognition and Color Detection

###DETECT LICENSE PLATE<br/>
1.Read image using opencv and resize using imutils<br/>
2.Convert to gray scale and reduce noise using bilateral filter<br/>
3.Use **Canny Edge Detection** Algorithm <br/>
4.Find and draaw contours<br/>
5.Mask the license plate<br/>

###READ LICNESE PLATE<br/>
1.Read charcters using easyocr<br/>
2.Get string from the result<br/>

###DETECT COLOR OF LICENSE PLATE<br/>
1.Get ndarray from opencv<br/>
2.Iterate over the array and store BGR values seperately<br/>
3.Find the range of values<br/>
4.Determine the dominant color<br/>
