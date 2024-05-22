# Generating-Mock-CSS

The notebooks included in this repository provide a method to correlate galaxy model-intrinsic parameters to observables (Sersic index and effective radius). It does so using a variety of methods from the 'AGAMA' framework (https://github.com/GalacticDynamics-Oxford/Agama) along with various surface profile fitting tools. 

The main goal of this method is to accurately construct mock N-body models of compact galaxies, however it is easily convertible to any type of stellar system. The conversion is done through the fitting of a 2D bivariate B-spline plane, which then provides a 2D function which allows one to determine model-intrinsic parameters from observables. 

For example, if you observe a cE with Sersic index 3 and effective radius of 1 kpc, then one can use the functional form of the B-spline plane to compute (e.g.) a scale radius and inner powerlaw slope. The scale radius and inner slope can then be used alongside AGAMA to construct a galaxy model for that given galaxy. 

If this code/method is used for a published work, please cite (paper in progress). 
