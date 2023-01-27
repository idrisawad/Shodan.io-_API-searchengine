# Shodan.io-_API-searchengine
This script allows users to search for any type of query on the Shodan search engine and save the results to a CSV file for further analysis.

### Requirements ###

 - A Shodan API key (can be obtained by signing up for a free account on [Shodan.io](https://www.shodan.io/)
 - Python 3
 - The `shodan` library (can be installed using `pip install shodan`)
 - The `csv` library (included in the Python standard library)

### Usage ### 

 1. Download or clone the script to your local machine.
 2. Open the script in a text editor and replace `"YOUR_API_KEY"` with your Shodan API key.
 3. Run the script using the command `python shodan_search.py` in your command prompt or terminal.
 4. When prompted, enter your search query. The script will then search for the query on the Shodan search engine.
 5. The script will create a new CSV file named `search_results.csv` in the same directory as the script and save the results of the search to it. The CSV file will include the following columns: IP, Port, Organization, Operating System, Hostnames, and Data.
 6. The script will print the number of results found, and saved in the CSV file.

### Tips ### 

 - You can use any search query you want, the script will search for the query and will output the results in the CSV file.
 - The `org` and `os` fields in the CSV file may be blank if the information is not available.
 - The `hostnames` and `data` fields in the CSV file may be blank if the information is not available.

### Troubleshooting ### 

 - If you receive an error message, make sure that you have entered your Shodan API key correctly and that you have a valid internet connection.
 - If you receive a "Quota exceeded" error message, it means that you have reached your daily search limit. You can either wait until the next day or upgrade your Shodan account to a paid plan for more search queries.
 - If you receive an "Invalid API key" error message, it means that your Shodan API key is not valid. Make sure that you have entered your key correctly and that your Shodan account is active.

### Conclusion ### 

This script allows you to search for any type of query on the Shodan search engine and save the results to a CSV file for further analysis. It is a useful tool for security researchers, network administrators, and anyone else who needs to gather information about a specific type of device or service on the internet. The script is easy to use and can be customized to suit your specific needs.

### Legal Disclaimer: ### 

This script is intended for authorized use only. By using this script, you agree to use it in compliance with all applicable laws and regulations. The author of this script is not responsible for any actions taken or damages caused by the use of this script.

The user of this script is solely responsible for obtaining any necessary permissions or licenses required for its use. The author of this script makes no representations or warranties of any kind, express or implied, about the completeness, accuracy, reliability, suitability or availability with respect to the script or the information, products, services, or related graphics contained in the script for any purpose. Any reliance you place on such information is therefore strictly at your own risk.

In no event will the author of this script be liable for any loss or damage including without limitation, indirect or consequential loss or damage, or any loss or damage whatsoever arising from loss of data or profits arising out of, or in connection with, the use of this script.

By using this script, you understand and agree that the author of this script shall have no liability for any damages whatsoever, including but not limited to any direct, indirect, special, incidental, or consequential damages, and including, without limitation, lost revenues, lost profits, or loss of prospective economic advantage, resulting from the use or misuse of the information contained in this script.

The user of this script must not use this script for any illegal or unauthorized purpose. The user is solely responsible for any actions taken through the use of this script, and the author of this script will not be held liable for any damages or losses resulting from such actions.

By using this script, you confirm that you have read and understood this disclaimer and agree to be bound by its terms. If you do not agree with the terms of this disclaimer, you must not use this script.
