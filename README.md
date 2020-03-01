# SAR-Satellite-Image-Processing-and-Vessel-Detection
                       The methodology helps in detecting ships at sea using SAR data and estimating size of the detected ship invariant of size.It can be applicable to any resolution SAR data of same band.
                       Ships of invariant  size are detected by identifying the threshold using CA-CFAR for the given SAR image.”PIL” is used to process SAR image of any resolution of same band.
The Land-Water discrimination is done using the Morphological filtration which includes Low pass filtering and High pass filtering
Now the Binary image is obtained.Dilation and erosion method is used to accurately find out  the difference between land and water.
Now the given dataset is processed by the  Neural Networks and Deep Learning and the threshold is estimated based on the given dataset which is used to differentiate Islands and Ships.
Vector image of the identified Ship is obtained and perimeter and surface area of the Ship is evaluated.
1.TOOLS - CONDA (PYTHON) 2.ALGORITHM- CA- CFAR METHOD  3.LIBRARY - OPENCV ,PIL , NUMPY,MATPLOTLIB


  
  
 


