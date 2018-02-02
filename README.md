Support Vector Machines on Vehicle Accident Data
----------------

This project involves building Support Vector Machines (SVMs) using SAS Enterprise Miner on a dataset containing vehicular accident information.  SVM is a classification method that involves separating two or more classes of data.  To achieve perfect or near-perfect classification, the data may need to be transformed using a kernel function.  My analysis involves using several different kernel functions to see which is the most accurate.  Additionally, I will determine which method is the most effective at identifying fatal accidents in particular.

The full report can be found in the file "Support Vector Machine.pdf".  This report shows a complete breakdown of my analysis, including problem identification, motivation, data exploration, data preparation, data sampling and partitioning, predictive model development, model results and tuning, model comparison, and proposed solutions.  Tables and visualizations are included in the appendix.

The dataset "Accidents.xls" was provided by my course instructor at the University of Maryland University College.  The variable description can be found in the "Data Codes" tab of the Excel file.  First, I converted it into a .csv file using Excel.  Since it uses an older Excel version, I am also providing the .csv file.  Next, I converted it to a .sas7bdat file using SAS Enterprise Miner.  Finally, the data source can be imported into your SAS EM project.

The process flow diagram I created for this project (seen in Figure 1 of my report's appendix) is included in the file "svm diagram.xml".  The requirements are described in the file "requirements.txt".  To use this diagram, you need to import the .xml diagram into your SAS EM project.