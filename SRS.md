# Software Requirement Specification 

## 1. Introduction
### 1.1 Purpose :
this document serves for a Logs Managment System . This system will Extract , Transform , Filter and Visulize logs .

### 1.2 Scope :
The system should be able to :
- Extract CSE log data from Genetec 
- Expose Restful API endpoints using FastAPI to access and filter data 
- integrate gas readings captured by BOS
- Expose PowerBI for frontend access of data visulization


## 2. Description :
This System composed of :
- Fast API Backend for processing and filtering logs 
- PowerBI dashboard for data visualization

 
 ## 3. Opreating environments :
-Python +3.10 ,FastAPI 
-PowerBI 
-Genetec

## 4. Functional Requirements :
- FR1 : The system shall be able to extract , transform and load CSE logs
- FR2: The system shall be able to provide API points through FastAPI for retrieving and filtering logs
- FR3: The system shall be able to generate virtual reports in PowerBI based on data (logs) 




