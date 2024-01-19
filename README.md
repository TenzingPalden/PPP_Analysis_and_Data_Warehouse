# PPP_Analysis_and-Data-Warehouse

 &emsp; This project cannot be fully shown in Git Hub as it requires access to Google Big Query. What can be shown is the analysis that was done on the data and the cleaning and processing part.
The Paycheck Protection Program (PPP) is a federal loan program designed to assist businesses affected by the COVID-19 pandemic. 

 &emsp; Conducting a data analysis project on PPP loans can provide valuable insights for both the government and small businesses.
For the government, a thorough analysis can help identify areas for improvement in the program and ensure that funds are being distributed effectively.
For small businesses, a data analysis project can help them understand how PPP loans are being used by other companies in their industry, and provide them with information that can help them make more informed decisions about how to use the funds they receive.


# First, The data retrieval
 &emsp;  The data we required about PPP loans were all found on the web. SBA, the USA's small business administration has all these records available to the public. 

<img width="500" alt="image" src="https://github.com/TenzingPalden/PPP_Analysis_and_Data_Warehouse/assets/85039775/ce25a2bc-73ad-45c9-b345-f24069804cbb">

I download each CSV file onto our local machine. Later the files were used to upload into Google Cloud Buckets Having Data in-house made the process easier to organize and simpler to work with.

# Next, was the Data modeling for the Data warehouse.
<img width="800" alt="image" src="https://github.com/TenzingPalden/PPP_Analysis_and_Data_Warehouse/assets/85039775/6a447331-9055-43da-9323-90617fe67d62">

# Finally, I integrated the data within the cloud using Talend.

<img width="500" alt="image" src="https://github.com/TenzingPalden/PPP_Analysis_and_Data_Warehouse/assets/85039775/637089a9-d0fb-4409-b02a-6326e9e77c0a">


# The next part of the project is to use Python to analyze the data we collected. 
I had to separate the data into specific CVS to format the information.
After that, I used Talend to visualize the vast amount of data to make an easy chart to understand where the money was going throughout the PPP loan period.

Below are the top 20 lenders for the states of NY and NJ, my current home state and its neighbor. 

<img width="500" alt="image" src="https://github.com/TenzingPalden/PPP_Analysis_and_Data_Warehouse/assets/85039775/cb53fe5e-bbbd-41b1-9d2c-f7cea61c3088">

<img width="500" alt="image" src="https://github.com/TenzingPalden/PPP_Analysis_and_Data_Warehouse/assets/85039775/c92c7cbd-9231-40d9-af3d-2d9c7cf7352d">

an important part of getting the aggregation done was making a states list to organize
```python
state_list = [ "AE", 'AK', 'AL', 'AR', 'AZ', 'CA', 'CO', 'CT', 'DC', 'DE', 'FL', 'GA',
           'HI', 'IA', 'ID', 'IL', 'IN', 'KS', 'KY', 'LA', 'MA', 'MD', 'ME',
           'MI', 'MN', 'MO', 'MS', 'MT', 'NC', 'ND', 'NE', 'NH', 'NJ', 'NM',
           'NV', 'NY', 'OH', 'OK', 'OR', 'PA', 'RI', 'SC', 'SD', 'TN', 'TX',
           'UT', 'VA', 'VT', 'WA', 'WI', 'WV', 'WY']

```
<img width="500" alt="image" src=" ">
