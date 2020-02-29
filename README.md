# account_user_matching
upwork job. comparing and matching accounts and user information in two excel files.
Read the job description in the following screenshot:
https://github.com/ahmetdiril76/account_user_matching/blob/master/upwork_job_desc.png
Jupyter notebook performing the described job. Source files and generated target files are also in the repository.

Description of the job from upwork posting:

We would like to have a python script and/or jupyter notebook to read in the attached SampleAccounts.xlsx file and produced two excel files:

1) MatchRecords.xlsx - records in the SampleAccounts.xlsx file that has a matching name and address in the SampleUsers.csv file.  

2) NewRecords.xlsx - records in the SampleAccounts.xlsx file that do not have a matching name and address in the SampleUsers.csv file.

Notes:
1) Ignore any "Commercial" records in the SampleAccounts.xlsx
2) A "match" is first name, last name, and complete address.  Middle name is optional
3) Both output files should have the format [FirstName, LastName, MiddleName, Address1, Address2, City, State, ZIP, County]
4) The actual files for SampleAccounts.xlsx and SampleUsers.csv both have over 500,000 records.  So please keep that in mind regarding the logic. 
