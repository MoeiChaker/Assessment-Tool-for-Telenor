# Rural Healthcare Cell Reliability Assessment Tool
## Background:
Rural healthcare, particularly in regions with an ageing demographic, faces significant challenges that necessitate innovative strategies to alleviate resource pressures. One promising approach is self-health care, where individuals manage routine health checks independently. However, the efficacy of such a solution heavily relies on a robust and dependable network infrastructure.
 
In light of this need, research led to the development of a tool to assist Telenor in evaluating cell reliability. This tool is designed to analyze data focusing on crucial parameters that gauge cell reliability. An imporant feature is its capability to pinpoint the most reliable cell within a site with multiple cells. Research indicates that cells showcasing minimal standard deviation in these parameters tend to be more consistent and reliable.
 
## Features:
* Evaluation of various Key Performance Indicators (KPIs) crucial for cell network performance.
* Categorization of each KPI into 'Good', 'Moderate', or 'Bad' based on predefined research and 3GPP standards.
* Ability to analyze multiple cells and select the most reliable one within a site.
* Provides foundational statistics like mean, median, and standard deviation for each cell and KPI.
Data interpretation that autonomously stratifies network performance, enhancing the comprehensibility of complex data.
 
While the tool's initial design aimed to incorporate machine learning algorithms for gauging site connection quality, resource constraints shifted the focus towards parameter analysis. This ensures that Telenor can make informed decisions about cell reliability, particularly vital for regions requiring stable connections for healthcare technologies. Ensuring this reliable cellular performance is crucial for the effective rollout of self-care technologies, holding the potential to enhance the quality of life in such areas.
 
## How to use:
* Run the program.
* From the provided list, select the desired KPIs by entering their respective numbers separated by commas.
* For each chosen KPI, input the corresponding CSV filename.
* Specify the partial names of the cells you intend to analyze.
* The program will then output statistical data (mean, median, standard deviation) for each cell and KPI.
 
## Dependencies:
* pandas
* matplotlib
* numpy
* re
 
## KPIs and their units:
The tool has a predefined dictionary of KPIs with their associated units, which are essential metrics in appraising cell network performance. It also establishes criteria for categorizing each KPI based on set thresholds rooted in research and 3GPP standards.
 
## CSV Limitations
In the code development phase of our thesis project, we encountered a limitation concerning the availability of CSV documents for all Key Performance Indicators (KPIs). This issue arose as these documents were not accessible to us, hindering our ability to have a comprehensive dataset for analysis. Despite the lack of complete data for all KPIs, we proceeded with the available information to fulfill the objectives of our project to the best of our ability. The absence of CSV documents for certain KPIs is a notable limitation that required acknowledgment and adaptation in our approach to data analysis and interpretation within the scope of the project.
