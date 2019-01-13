Parse-FortiGateRules reads a FortiGate config file and pulls out the rules for each VDOM in the file into a CSV. 

Note: the fortiDummyRule.txt is required to populate all the fields into a PS object for each of the rules being added to the CSV. 

EXAMPLE 
.\Parse-FortiGateRules.ps1 -fortiGateConfig "c:\temp\config.conf" 
Parses a FortiGate config file and places the CSV file in the same folder where the config was found. 

[Blog post](https://www.drewhjelm.com/2018/02/14/parse-fortigate-configs.html)

Other Links:
* FortiGate hardening guides: [6.0](https://docs.fortinet.com/uploaded/files/4286/hardening-60.pdf), [5.6](https://docs.fortinet.com/uploaded/files/3624/fortigate-hardening-your-fortigate-56.pdf), [5.4](https://docs.fortinet.com/uploaded/files/3585/hardening-54.pdf), [5.2](https://docs.fortinet.com/uploaded/files/2340/hardening-52.pdf)
* [fgpoliciestocsv](https://github.com/maaaaz/fgpoliciestocsv) - Parses FortiGate policies into CSV using Perl and Python