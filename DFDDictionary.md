#Data Flow 

**Software package-** The Developer send request to Checked for OSS Components then send to Scan for Licenses.

**Software package Licenses Results-** The Scan for Licenses send Results to Checked for OSS Components then send to Developer.

**Software Package Name-** The Checked for OSS Components send Request to NIST Vulnerability DB.

**Vulnerabilities for package-** The Checked for OSS Components received Results from NIST Vulnerability DB.

**OSS licence and vulnerability information-** The Checked for OSS Components send Request to Software Package & License Info Datastore then to Retrieve license and Vulnerability Information for requested software project also send to the Manager and Developer.

**OSS licence and vulnerability information-** The Software Package & License Info Datastore send Results to Retrieve license and Vulnerability Information for requested software project then Manager and Developer.

**SW project request-** The Manager and Developer send Request to Retrieve license and Vulnerability Information for requested software project then to The Software Package & License Info Datastore.

**Policy request -** The Manager and the Developer sends Policy request to Refer Policy then to OSS Policy Datastore.

**Policy information-** The OSS Policy Datastore send results to Refer Policy then to Manager and Developer.

**Policy doc-** The Manager send request to Read and Modify Policy then send the request to Submit Policy then to OSS Policy Datastore. 

**Policy information-** The OSS Policy Datastore send results to Submit Policy then send the results to Read and Modify Policy then to Manager.


#Entities 

**Developer-** Person responsible for all the coding the main software packages and preparing for the license scan.

**Manager-** Advisor for the software packages.

#Processes

**Checked for OSS Components-** Process that checks for open source software in the file.

**Scan for Licenses-** Process that scans for any licenses that can be found in the program.

**Retrieve license and Vulnerability Information for requested software project-** Project request process.
 
**Refer Policy-** Refer to the policies of organization set by Manager.

**Read and Modify policy-** Help in reading and modifying the existing policies.

**Submit policy-** Help in submitting the new and approved policies.

#Data store 

**NIST Vulnerability DB-** The storage called National Institute of Standards and Technology Vulnerability Database. 

**Software Package & License Info-** The storage called Software Package & License Info.

**Policy Data store-** The storage policies called Policy Data store.
 
