# google_analytics_checker
Checks if google analytics has the anonymize ip true string in the webpage.

## Description
A simpel bash script that checks if a specific webpage contains the string "'anonymizeIP', true" to check if the webpage has the anonymize ip option turned on for google analytics. Wich will anonymize the last octet of the IP adres from the data collected.

## Usage
The script accepts one webadres as an argument
* www.google.com

### Example
check if www.google.com has the string "'anonymizeIP', true" on the webpage.
```sh
./google_analytics_checker www.google.com
```
