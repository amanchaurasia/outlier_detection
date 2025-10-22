# outlier_detection
A data project to flag Outliers and anomalies in financial data using sklearn, Pandas and Numpy.

Creating an algorithm that can find outliers in this data by one column / several columns. E.g. some members have extremely high costs in the current month and your solution should be able to detect such records. Think about features and how you would explain them to business people.

Data Description
----------------

The dataset **sfr\_test.csv** contains fictional financial information about customers of the company.

Below is the description of the selected columns from this dataset:

*   **member\_unique\_id** - member's ID
    
*   **gender** - member's gender
    
*   **dob** - member's date of birth
    
*   **eligible\_year** - year
    
*   **eligible\_month** - month
    
*   **affiliation\_type** - doctor's type
    
*   **pbp\_group** - health plan group
    
*   **plan\_name** - health plan name
    
*   **npi** - doctor's ID
    
*   **line\_of\_business** - health plan type
    
*   **esrd** - True if patient is on dialysis
    
*   **hospice** - True if patient is in hospice
    

The remaining columns contain various financial indicators. **All values in these financial columns contain a $ sign.**
