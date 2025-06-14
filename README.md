# Decision-Tree-Classifier-for-Redshift-estimations

This is overview blueprint python notebook for the estimation of Redshift of galaxies using a Decision Tree Regressor. The file begins with the feature extraction (in this case the color indices) from SDSS dataset containing a few galaxies and their spectroscopic redshifts calculated . The model is then simply trained to spilt the dataset , fit according to the training dataset, and then produce the estimations which are then plotted with respect to the actual redshifts (i.e. plotting of a simple linear regression). One of the color map also corresponds to the redshifts concieved in accordance with various color indices which is termed as the 'multicolor indices' plot. 

The further code scripts the accuracy of model and compares it using held out and K-fold cross validation with the results being compared and plotting of training and validation set for the determination of Maximum tree depth to prevent the overfitting of outliers.

In the second part, the model's accuracy is tested with the QSOs(Quasi-Stellar Objects) in the dataset, which usually have a larger redshift. The results have been discussed accordingly through both accuracy methods which are as discussed above. The redshift population distribution among QSOs and Galaxies has also been presented based on their 'spectral class' in the dataset. 

At the end, the regression line for the prediction of redshifts for both QSOs and Galaxies in the dataset has been graphed.
