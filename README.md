## Networking Survival Kit

## Scenario:
 You are a security professional that has been hired to carry out an investigation into a recent security breach of Arch industries. Upon initial scan of equipment, you have determined their system is severly outdated and contains none of the standard network cli tools and applications you normally have to perform your duties. Guess you will have to build your own!!!!!!
    
## Your Task:
 You are to use your knowledge of networking and scripting to build basic networking tools in order to complete your job. Below are your details if you choose to accept.
 
## Setup:
 - Each tool will have its own python file.
 - Tools must be coded using python 3.6.
    
## Required Tooling/Specs

**1. System Info Tool** - This tool will grab the hostname of the target machine.
  - This tool will need to use the socket module.
  - It will print the hostname to stdout in the format of: "The hostname is: NoSoupForYou"

**2. IP Mapping** - This tool will return the corresponding IP address of any domain entered.
  - This tool will make use of the socket module.
  - It will take stdin from the user and return the IP address in the format of: "The IP address of target is: 58.65.22.14"
    
**3. Port Scanner** - This tool will scan for open ports on any domain or IP and return a report when completed.
 - This tool will make use of the socket and sys modules.
 - It will be able to scan any range of ports.
 - It will generate a report in the format of: "Port 80: OPEN"
 
**4. Client Browser** - This tool will act as your client browswer to pull html from any domain.
  - This tool will make use of the urllib module.
  - It will be able to print the url, status code of request, request header info, server info, and the html.
      
**5. Mac Address Lookup** - This tool will return information on mac addressses.
  - This tool will use the urllib2, json, and codecs modules.
  - This tool will make an api call with mac address to http://macvendors.co/api
  - It will take stndin from user.
  - It will return a report in format of: "Company Name, Address".
  
### Resources
 - Python Functons https://www.learnpython.org/en/Functions
 - Python Loops & Conditionals http://www.openbookproject.net/books/bpp4awd/ch04.html
 - Importing Python Modules https://docs.python.org/2/tutorial/modules.html
 - Reading/Writing Files https://docs.python.org/2/tutorial/inputoutput.html#reading-and-writing-files
 - Python Socket Module https://docs.python.org/3/library/socket.html
 - Raw_Input https://docs.python.org/2/library/functions.html#raw_input
 - NSlookup http://www.kloth.net/services/nslookup.php
 
### Stretch Goals
  - Write a function that will keep track of how long each tool takes to complete its task. This should be an optional flag that can be toggled on or off.
  - Optimize performance/speed of port scanner.
  - Merge all individual tools into one tool that can be executed.
  - Add error handling such as keyboard interrupt.
