# DS_Aug
Here is the script for the augmentation of the damage site images existing in the microstructure of dual phase steel.. The images are collected using high resolution electron microscopes in IMM institute of RWTH Aachen university. 

     "Damage Analysis in Dual-Phase Steel Using Deep Learning: Transfer from Uniaxial to Biaxial Straining Conditions by Image Data Augmentation"
     Setareh Medghalchi, Carl F. Kusche, Ehsan Karimi, Ulrich Kerzel & Sandra Korte-Kerze
     https://link.springer.com/article/10.1007/s11837-020-04404-0


This script is a small package of augmenting tools which are used in the paper published in Journal of materails, in 2020. For more information about the function of each of the tools refer to the paper. 
After augmeting the images existing in each directory they are saved in a new directory with a code name addressing the type of the applied augmetation.  The augmented images can be searched with the same code name in the directory.

# Motivation 
Microstructural damage can occur during metal forming, but how and wherethis happens vary with the local microstructure and strain path. Large-scale analysis of such damage mechanisms is particularly important in advanced steels with a heterogeneous phase distribution. 

The aim of this work is to generalize the approach of classification of the damage sites approach to different stress states, e.g., biaxial instead of uniaxial tension, without manually labeling a large new ground-truth dataset of further micrographs and to thereby assess the changes in damage behavior
with respect to stress state. Data augmentation allow us to directly apply our approach to the new, biaxial loading case. A comparison between sample geometry and martensite crack orientation appearing in the sample after (a) biaxial and (b) uniaxial tensile testing.

![Git](https://user-images.githubusercontent.com/54040415/188902366-d73d4ac8-e91e-4155-a241-289e223f5953.png)


Overall, any network performance trained could be greatly improved and an analysis of changes in damage behavior, here the martensite crack angle distribution, with stress state can now be performed.


# Data Augmentation for Image Analysis by Neural Networks
Data augmentation is a general technique to improve both the generalizability and convergence of neural networks, enhancing the training and convergence of the neural networks, since it tackles the qualitative and quantitative limitations of the employed data. Data augmentation techniques can be loosely grouped into two categories: The more traditional approach is basedon methods such as image rotation, shearing, cropping, translation, color transformation, etc.,whereas generative adversarial networks(GANs) show great promise to generate ‘‘fake’’images.
Using the data generated by both methods can increase the data in terms of quantity, quality, and
variety.29 In this work, we investigate whether our method can be expanded directly by data augmentation to increase the generalizability of the auto- mated analysis with respect to different strain paths. Ideally, this would minimize any need to manually acquire and label a large amount of new ground truth data; For example, to assess the damage induced during the forming of dual-phase steels in a general manner, deformation under different straining conditions, such as uniaxial or biaxial tension, has to be included. Furthermore, augmentation of the microscopy data is expected to lead to an improved performance benchmark of damage site classification. This again reduces the need for manual interventions, aiding the opportunity to achieve statistical analysis of a large number of sites within a given microstructure deformed under variable conditions.

Some examples of applied augmented damage sites images with the explained tools is shon here:

![AugExs](https://user-images.githubusercontent.com/54040415/188905827-e18c7934-c788-47b6-8d15-28ff51bf021c.png)


#License
Publications arising from this project should include a reference to this project and an electronic copy of these publications should be sent to the following E-mails: se.medghalchi@yahoo.com
medghalchi@imm.rwth-aache.de
