# Clustering Analysis of PKB Voter Areas in Nganjuk Regency Using the KMeans Algorithm

This project focuses on clustering the PKB voter areas in Nganjuk Regency using the KMeans algorithm. The goal is to group the regions based on key variables such as voter counts, family counts, abstentions, and PKB support levels, to identify campaign zones for targeted strategies.

## Features
- Analyze data containing voter information.
- Perform KMeans clustering based on variables like total voter count, family count, abstention rate, and PKB support rate.
- Identify the characteristics of each cluster to determine campaign zones:
  - **Zone 1**: High support and potential voter participation (Priority Campaign).
  - **Zone 2**: Moderate support (Normal Campaign).
  - **Zone 3**: Low support (Non-priority Campaign).
- Display the clustering results and campaign zone recommendations.

## How to Use

### Prerequisites:
Ensure you have Python 3.7+ installed on your system. You'll also need to install the required libraries (listed below) to run the program.

### View the Results:
After the script has executed, the results will be saved in a CSV or Excel file.
You will also see the recommended campaign zones for each area, categorized into Zone 1, Zone 2, or Zone 3.
### Technologies Used:
Python (Pandas, Scikit-Learn): For data processing and machine learning.
KMeans Algorithm: For clustering the data into meaningful groups.
### Outcome:
The project provides an automated way to analyze voter areas using KMeans clustering.
Campaign zones are identified based on clustering results, enabling more targeted campaign strategies.
