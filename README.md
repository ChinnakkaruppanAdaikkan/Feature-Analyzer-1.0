# Feature-Analyzer-1.0

Welcome to Feature Analyzer!
Thank you for selecting the Feature Analyzer to meet your feature extraction requirements. 
The Feature Analyzer is a robust tool for swiftly and accurately extracting features from your time series data. The user-friendly interface facilitates the selection and execution of various feature extraction algorithms. This guide will assist you in efficiently and effectively utilizing our software.


Getting Started
•	Import Data:  Begin by importing your data into the software. Click the "Import Data" option and select the data file from your system. The data must be arranged in a single column. Feature Analyzer supports .csv, .edf, .mat and .txt formats. 
•	Sampling Freq(Hz): Specify the sampling frequency of the imported data in hertz. This is a mandatory field. The default value is 0 (zero).
•	Feature Extraction: If you prefer one or a specific set of features, select the desired feature extraction algorithm to initiate the corresponding process. The software will process your data using the selected algorithm(s), generating the output for the desired features. Execute All: The "Execute All" button allows you to automatically process all 41 feature extraction algorithms simultaneously. The resulting features will be conveniently displayed in the "Results" tab for effortless access.


Results 
Once the feature extraction process is complete, navigate to the designated output area in the "Results" tab. Here, you will find a comprehensive display of the extracted features and corresponding values.
Plot Window: Here, you will see the time series representation of the imported data.
Export To Csv
Click the "Export To Csv" option to export the data from the result window into a CSV file named "FeatureExtractionResults.csv." The file is saved in the same directory (i.e., folder) as the software installation, ensuring easy access and compatibility. 
 

Typical Usage
To analyze the characteristics of a specific channel, it is necessary to individually process each channel's data through the Feature Analyzer. Begin by importing the data file associated with the channel of interest, for instance, "51.txt" which contains the single channel data. This procedure can be repeated for each electrode or channel to perform a comprehensive analysis. Users need to rename it before the next run. It is recommended that users copy the results output to another folder periodically.

