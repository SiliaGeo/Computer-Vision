CT Images - Spatial Image Registration

Description

This project focuses on spatial image registration using CT images. The following steps are involved:

    Read .raw Files:
        Utilize information from .mhd files to read corresponding .raw files for CT images.

    Slice Selection:
        Choose slices 286 from CT1 and 372 from CT2 for registration.

    Edge Projection:
        Project the edges of slice 372 onto slice 286.

    Automatic Point Selection:
        Replace manual point selection with characteristic points using image features like SURF, SIFT, etc.

    Affine Transformation:
        Calculate the matrix of affine geometric transformation required to align the selected corresponding points.

    Apply Transformation:
        Apply the transformation to the image of CT2.

MRI Phantom - Point of Interest Localization

Description

This project involves point of interest localization techniques for a section from an MRI phantom. The objectives are as follows:

    Intersection Extraction:
        Extract the location of intersections of the black grid using point of interest localization techniques.

    Geometric Deformation:
        Propose and test ways to calculate geometric deformation based on the circular shape of the phantom and the black grid.

Faces Detection: The Eigenfaces Method

Description

This project utilizes a dataset (Olivetti.mat) containing face images for implementing the Eigenfaces method. The steps involved are:

    Dataset Division:
        Divide the dataset into training and test subsets ensuring that all 40 persons are included in both subsets.

    Principal Component Analysis (PCA):
        Apply PCA to the training set and define the required number of eigenvalues.

    Face Identification:
        Identify each face in the test set using the following steps:
            Calculate projection to each eigenface.
            Use projections as features to classify the unknown face into one of the 40 different faces.

    Confusion Matrix:
        Create a (40x40) Confusion matrix to evaluate the accuracy of face identification.
