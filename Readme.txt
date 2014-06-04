connect.php is the configuration file used to connect to the database. 

DB Structure.sql contains the database tables and constraints, with no data.

Import.php takes the data from the SampleKeywordReport.csv and parses the data into three tables campaign, adgroup, and keywords.

script1.php displays the campaign name, adgroup count per campaign, keywords count per campaign, total impressions per campaign, total clicks per campaign, and total cost per campaign for each day without any user input.

script2.php takes adgroupID that the user provides and displays the correlating campaign name, adgroup name, keyword count, total impressions, total clicks, total cost per day. 