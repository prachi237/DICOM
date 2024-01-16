# Convert a DICOM Image Into JPG/PNG

## As we know in computer vision, we deal with medical images, and almost all the databases that are available in this case contains the DICOM images. (The Dicom image contains the pixels info, patient info, etc.)

## In this code, I work on visualising the image and to save it in JPG/PNG so that it can be opened in any software/ program we want to. This is a very basic program tho.

## For this I have used libraries like Pydicom (library special for the Dicom images), Pillow(which I prefer to use for displaying and saving the JPG/PNG image), Numpy (to manipulates the arrays).

# The major steps involved r as follows:

1. Installing the libraries
2. Extracting the pixel array (The image source is taken from (https://www.magnetomworld.siemens-healthineers.com/clinical-corner/protocols/dicom-images/pediatric-phoenix-images-for-magnetom-skyra-brain.html))
3. Rescaling the image
4. Displaying and saving the new image
