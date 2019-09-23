# SULI Spring 2019 

## Project: Computer Vision for the Characterization of Fibers in Material Design

Abstract: 

To study the structure of materials acquired using Micro-CT, we resort to computer 
vision and machine learning techniques such as filtering, enhancement, and pattern 
classification to analyze a ceramic matrix composite (CMC) sample, reinforced by fibers. 
Our image workflow starts by transforming crops of image cross-sections (1200 “curated images”)
using normalization of pixel intensities to minimize spurious photometric variations.
We tested two classification approaches: a supervised (LeNet) and an unsupervised 
(hierarchical clustering) one. With the LeNet neural network, we perform classification of curated 
images into fibers and non-fibers. Next, we cluster the curated images with hierarchical clustering
for the characterization of fibers, which provide insights with regards to taxonomy. Our results 
show that we can classify fibers with an accuracy for the samples for training and 27% for testing. 
The clustering analysis points out to two main types of fibers: thin-coated at the center o
f the specimen and thick-coated fibers at the outer parts. The merging of these computational 
processes helped to understand the false positives and false negatives, which are mostly due to the 
agglutination of fibers or very thin-coating. Future work includes exploring advanced feature 
extraction methods, and tracking of 3D fiber structures in the entire image sequence.
