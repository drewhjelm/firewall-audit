This is a collection of scripts to assist in auditing firewall rules.

fortigate/Parse-FortiGateRules reads a FortiGate config file and pulls out the rules for each VDOM in the file into a CSV. 

Note: the fortiDummyRule.txt is required to populate all the fields into a PS object for each of the rules being added to the CSV. 

EXAMPLE 
.\Parse-FortiGateRules.ps1 -fortiGateConfig "c:\temp\config.conf" 
Parses a FortiGate config file and places the CSV file in the same folder where the config was found. 

Other Links:
* Router and Switch Backups - [https://github.com/robvandenbrink/rtrbk](https://github.com/robvandenbrink/rtrbk)