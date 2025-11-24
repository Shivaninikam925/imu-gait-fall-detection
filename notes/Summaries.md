***ADVANCED FEATURES***

>>Extracted advanced features:

&nbsp;  - RESULTANT acceleration

&nbsp;  - MEAN\_X

&nbsp;  - VAR\_X

&nbsp;  - ENTROPY\_X



>>Verified the new features were added successfully to the dataset.



>>Re-trained Random Forest (≈76.07%) after advanced feature extraction.



>>Observed minimal change in accuracy → dataset complexity is high.





***Dimensionality Reduction \& Advanced Feature Engineering***

1\. Added statistical features:

MEAN\_X, VAR\_X

MEAN\_Y, VAR\_Y

MEAN\_Z, VAR\_Z

RESULTANT (signal magnitude)



2\. Applied PCA (95% variance retained)

Reduced features from 93 → ~30 PCA components



3\. Trained PCA-based Random Forest

Accuracy: 0.7574

Almost same as RF baseline (0.7612)



4\. Interpretation

PCA compresses data effectively

Minimal accuracy loss shows underlying gait/activity patterns are strong

Reduced computational cost → ideal for wearable/real-time health screening

Helps justify using IMU signals for early neurological disorder detection





