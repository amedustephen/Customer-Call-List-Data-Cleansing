# **Customer-Call-List-Optimization**  

## **BACKGROUND**  
You are a data analyst for a mid-sized customer engagement firm specializing in telemarketing and customer support services. The company relies on accurate and up-to-date customer data to ensure seamless client interactions. However, the current customer call list suffers from various data quality issues, including duplicate entries, missing values, and inconsistent formatting. These issues are causing inefficiencies, such as redundant calls, wasted time, and reduced productivity for call agents.  

The management has tasked you with analyzing and cleaning the customer call list to eliminate redundancies, correct inconsistencies, and ensure the data is ready for operational use.  

---

## **PROBLEM STATEMENT**  
The customer engagement firm is facing operational inefficiencies due to poor-quality customer data. Problems such as duplicate records, missing values, and inconsistent formats are leading to:  
- Redundant and unnecessary customer calls.  
- Delays in client engagement due to incomplete contact information.  
- Low productivity and increased frustration among call agents.  

Your task is to clean, standardize, and optimize the customer call list to improve operational efficiency and provide a seamless workflow for the call agents.  

---

## **OBJECTIVES**  
The primary objectives of this project are to:  
1. **Identify and remove duplicate records** to avoid redundancy.  
2. **Handle missing values** to ensure completeness of essential fields like phone numbers and customer names.  
3. **Standardize data formatting** for consistency across key columns (e.g., phone numbers, customer names, and addresses).  
4. **Remove unnecessary columns** and rows that do not add value to the workflow.  

---

## **DATA SOURCES**  
- **Input**: Raw customer call list dataset (Excel file).  
- **Tools Used**: Python (Pandas library), Jupyter Notebook.  

---

## **KEY STAKEHOLDERS**  
- **Call Agents**: Improved data accuracy will reduce redundant calls and increase productivity.  
- **Operations Managers**: Streamlined workflows will ensure better resource allocation and operational efficiency.  

---

## **BUSINESS METRICS**  
The success of this project can be evaluated using the following metrics:  
1. **Reduction in Duplicate Records**: Number of duplicate entries removed from the dataset.  
2. **Completeness of Essential Fields**: Percentage of records with valid phone numbers and customer names after cleaning.  
3. **Operational Efficiency**: Reduction in redundant calls and increase in the number of successful customer engagements.  


## **DATA CLEANING WORKFLOW**  
The following steps were performed to achieve the project objectives:  

1. **Data Acquiisition and Profiling**  
   - Loaded and explored the dataset to identify key data quality issues.  
   - Assessed column data types, duplicate records, missing values, and inconsistent data formats.  

2. **Documentation of findings and cleaning strategy**  
   - Identified issues and created cleaning plan.   

3. **Data Cleaning**  
   - Removed duplicate record(s)
   - Removed irrelevant columns like `Not_Useful_Column`.
   - Cleaned Last Names, stripping out characters like './_'
   - Cleaned and standardized phone numbers into a consistent format.
   - Split the 'Address' column into 'Street_Address', 'State' and 'Zip_Code'.
   - Standardized "Paying Customer" and "Do_Not_Contact" columns into a consistent format.
   - Removed non useful records based on the business requirements.
   - Identified records with duplicate phone numbers

4. **Cleaned Data Export**  
   - Exported the cleaned dataset to a separate Excel (.xlsx) file.  

5. **Verification and Finalization**  
   - Reassessed the cleaned dataset to confirm all issues were resolved.  
   - Validated that the data is ready for operational use.  

---

## **KEY FINDINGS**    
- Missing values in key fields were handled effectively, ensuring data completeness.  
- Phone numbers, customer names, and addresses were standardized to improve data consistency.  
- Non-contributing columns and rows were removed to streamline the dataset.
- Several duplicate `Phone_Number` entries were identified.

---

## **RECOMMENDATIONS**  
1. **Implement Data Validation**:  
   - Establish data validation rules during data entry to minimize missing or inconsistent records.  
2. **Regular Data Audits**:  
   - Schedule periodic checks to identify and clean duplicate records and missing values.  
3. **Automate Data Cleaning**:  
   - Use scripts or tools to automate the data cleaning process for future datasets.  

---

## **CONCLUSION**  
By cleaning and standardizing the customer call list, we have provided a reliable and actionable dataset that eliminates redundancies, corrects inconsistencies, and ensures completeness. This will significantly improve call agent efficiency, reduce wasted time, and enable better customer engagement.  


---

## **CONTACT**  
For any questions or additional details, please contact:  

**Name**: Amedu Stephen  
**Role**: Data Science/AI Consultant  
**Email**: amedustephen@hotmail.com  
**LinkedIn**:https://www.linkedin.com/in/amedupaulstephen/(#)  

---
