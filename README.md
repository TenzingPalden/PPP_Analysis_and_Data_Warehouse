# PPP_Analysis_and-Data-Warehouse

 &emsp; This project cannot be fully shown in Git Hub as it requires access to Google Big Query. What can be shown is the analysis that was done on the data and the cleaning and processing part.
The Paycheck Protection Program (PPP) is a federal loan program designed to assist businesses affected by the COVID-19 pandemic. 

 &emsp; Conducting a data analysis project on PPP loans can provide valuable insights for both the government and small businesses.
For the government, a thorough analysis can help identify areas for improvement in the program and ensure that funds are being distributed effectively.
For small businesses, a data analysis project can help them understand how PPP loans are being used by other companies in their industry, and provide them with information that can help them make more informed decisions about how to use the funds they receive.


# First, The data retrieval
 &emsp;  The data we required about PPP loans were all found on the web. SBA, the USA's small business administration has all these records available to the public. 

<img width="500" alt="image" src="https://github.com/TenzingPalden/PPP_Analysis_and_Data_Warehouse/assets/85039775/ce25a2bc-73ad-45c9-b345-f24069804cbb">

I download each CSV file onto our local machine. Later the files were used to upload into Google Cloud Buckets Having Data in house made the process easier to organize and simpler to work with.

# Next, was the Data modeling for the Data warehouse.
<img width="800" alt="image" src="https://github.com/TenzingPalden/PPP_Analysis_and_Data_Warehouse/assets/85039775/6a447331-9055-43da-9323-90617fe67d62">

# Finally, I integrated the data within the cloud using Talend.

<img width="500" alt="image" src="https://github.com/TenzingPalden/PPP_Analysis_and_Data_Warehouse/assets/85039775/637089a9-d0fb-4409-b02a-6326e9e77c0a">


# The next part of the project is to use Python to analyze the data we collected. 
I had to separate the data into specific CVS because that was what was
