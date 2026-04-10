Introduction:  
The project implements a facial emotion recognition system using deep learning. Its primary objective 
is to classify facial expressions from images into predefined emotion categories such as happy, sad, 
angry, surprised, neutral, disgusted, and fearful. The approach leverages convolutional neural networks 
(CNNs) to automatically extract hierarchical features from images. The dataset is structured into training 
and testing directories, each containing subfolders representing the different emotion classes. Images 
are preprocessed by resizing them to 48x48 pixels and converting them to grayscale. Grayscale 
conversion reduces computational complexity without losing essential features for emotion recognition, 
as color information is less critical for facial expression analysis. 
CV Techniques Applied:  
• Contrast Enhancement – Improves the visibility of faded areas in historical images, often 
implemented using histogram equalization.  
• Gamma Correction – Adjusts image brightness and contrast to make features more prominent.  
• Image Negative – Inverts the image colors to highlight faded or light regions.
