# Email-to-CRM-Script
This is a NodeJS program that is used to automate CRM posting or website page posting.
# How it works
The user will run the script in the command line, with the relative path of the downloaded email file (.eml) to be parsed.
The script will then post the content to either SquareSpace or KVCore depending on the command line arguments.
# Private
The private.json file contains confidential information about logging into the CRM platform (KvCore).
Thus, it is not included in the git repo, and is instead on the local machine.

# Technical
Languages used: Python, JavaScript
When the script is run, the Python script will parse the .eml file and send the results to a file.
Then, the Python script will call a js script to read from said file and update the CRM (KVCore) or website(SquareSpace).
