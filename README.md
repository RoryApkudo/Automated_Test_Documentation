# Automated_Test_Documentation
This project is partly for me to learn how to program, partly to improve the process of documenting testing

Goals for this project:
  When testing, we need to collect some basic information from devices to track data and generate reports.  Currently, that data is hand-entered, and is collected haphazardly and inconsistently.  This project seeks to find ways to improve this process, so that all device data is consistently captured.
  
Solution 1:
  Device data is hand-entered into a form, which feeds a spreadsheet or database.  This database or sheet is then used to populate a report.  If successful, this will be expanded to include the creation of customized metrics that are also fed into a report.
  
  Solution 1 needs:
    A. Identify all needed data points
    B. Develop a script that asks for this information and organizes the responses
    C. Develop a script that takes the organized data and turns it into a formatted report (consider using Report Generation script but pare it down.)
    
        A. Needed data points
           DUT VID
           DUT UID
           DUT MDN
           DUT IMEI
           SIM ID
           
        B. I guess I have to learn python or something jeez.
