# March_LexisNexis_Program-Checkpoint
Cleaned Python Programs with supporting documentation that extract information from PDFs using pdftotext.exe

Here is a list of important information that you should be familiar with before continuing this project.

Background information- What should you be familiar with before you start?
1. Python coding, specifically some specific modules that I will mention below that I tend to use
os module: https://docs.python.org/3/library/os.html
-  used to interact with the operating system and run command line codes frequently, along with importing and reading files
pandas library: https://www.w3schools.com/python/pandas/default.asp
-  used to store and collect data, along with some analysis and cleaning

2. CSV files- a lot of information is going to be stored using csv files, so get familiar with using Python to write to them and modify them
https://www.businessinsider.com/guides/tech/what-is-csv-file 
https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.to_csv.html

3. pdftotext- This is where most of the issues of these programs arose from. My pdftotext output text files do not look similiar to Professor Locks pfdtotext output file. A lot of my output files were decently messy, making this task a lot more difficult because I had to add in lines that would process multiple cases and different output file formats. Honestly, if your pdftotext works very nicely, there is a good chance that the program might run perfectly cleanly without you needing to do anything.
https://www.xpdfreader.com/pdftotext-man.html

Set Up- How to set up and run these programs?
1. Download and install pdftotext at https://www.xpdfreader.com/pdftotext-man.html
2. Download the programs and put them into a folder that contains all the Lexis Nexus reports in PDF version. 
3. Run the program using a commandline
Ex: python _____.py 

An output csv file should pop up in the folder when it is done. You can look at the output to see how well it performed. 

Current state- What is the issue with these programs/What do you need to fix?

The main issue with these programs is the uncleanliness of pdftotext. My version of pdftotext created output files that were not very similiar to the original pdf, even with the -layout option. As a result, because of all the variability, in order to get decently clean data, I had to account for not only the base case (the most common format), but also other less common variant cases (other text file formats that did not resemble the base case). However, if you are able to produce uniform output text files using pdftotext, then this task becomes exponentially easier. 


If you have any questions, feel free to reach out to me @ evan.yang@emory.edu.
