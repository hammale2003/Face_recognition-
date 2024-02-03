#Face verification solves an easier 1:1 matching problem; face recognition addresses a harder 1:K matching problem.

#Triplet loss is an effective loss function for training a neural network to learn an encoding of a face image.

#The same encoding can be used for verification and recognition. Measuring distances between two images' encodings allows you to determine whether they are pictures of the same person
####################Ways to improve your facial recognition model:######################

#Although you won't implement these here, here are some ways to further improve the algorithm:

#Put more images of each person (under different lighting conditions, taken on different days, etc.) into the database. Then, given a new image, compare the new face to multiple pictures of the person. This would increase accuracy.

#Crop the images to contain just the face, and less of the "border" region around the face. This preprocessing removes some of the irrelevant pixels around the face, and also makes the algorithm more robust.
