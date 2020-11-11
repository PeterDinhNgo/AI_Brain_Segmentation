# AI Brain Segmentation
##### Author: Peter Dinh Ngo
Magnetic Resonance imaging is widely used by medical professionals for the visualisation of anatomical structures and the detection of pathological lesions. Brain tissue intensity is the core feature being analysed when performing MRI's on the brain.  
To segment and classify typically homogenous and noisy brain MRI's into the three specific tissue types: White Matter, Gray Matter and Cerebrospinal fluid, a deep auto-encoder based upon the UNet architecture[1] proposed by Brox et. al in 2015 was used.
These segmentations have practical applications such as surgical planning, lesion detection and anomaly detection. 

  
### UNET Architecture [1]

---

![alt-text](https://lmb.informatik.uni-freiburg.de/people/ronneber/u-net/u-net-architecture.png)
  
### Results

---

#### Guide: Red = Cerebrospinal fluid, Green = Gray Matter and Blue = White Matter
![alt-text](https://storage.googleapis.com/dl-visuals-peter-ngo/Final%20Results.png)
  
  
### References

---

[1]   Ronneberger O., Fischer P., Brox T. (2015) U-Net: Convolutional Networks for Biomedical Image Segmentation. In: Navab N., Hornegger J., Wells W., Frangi A. (eds) Medical Image Computing and Computer-Assisted Intervention – MICCAI 2015. MICCAI 2015. Lecture Notes in Computer Science, vol 9351. Springer, Cham. https://doi.org/10.1007/978-3-319-24574-4_28  
