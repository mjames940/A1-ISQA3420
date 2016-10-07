#Data Flow Dictionary</br>

###External Entities/Externals-</br>

Ext 1: Developer- The create and contributer to the system</br>
Ext 2: Manager- The employee that oversees the operations of the system</br>

###Dataflows-</br>

DAF 1: Software Package- collection fo code files</br>
DAF 2: Software Package License and Vulnerability Results- The list of licenses and vulnerabilities reported by the scanner</br>
DAF 3: Software Package Name- The name fo the package discovered by the scanner</br>
DAF 4: Known Vulnerability Issues- The vulnerability issues stored in the organizations database</br>
DAF 5: Software Package Component- The stored compontent of software stored in the database</br>
DAF 6: OSS Software Components Request- The request to obtain the software component from the database</br>
DAF 7: OSS Software Components</br>
DAF 8: OSS Software Components Violations</br>
DAF 9: Software Package License</br>
DAF 10: Corporate licenses and vulnerability threshold</br>
DAF 11: Corporate licenses and vulnerability threshold request</br>
DAF 12: Confirmation??</br>
DAF 13:Corporate Policy Modification??</br>



###Data Stores-</br>

DS 1: OSS Software Components</br>
DS 2: NIST Vulnerability DB- The vulnerabilities discovered by the scanner</br>
DS 3: Corporate Policy- The policies on licenses and vulnerabilities set by the organization</br>

###Processes-</br>

PRC 1: Manage Software Package for License Scanning</br>
PRC 2: Scan for Licenses</br>
PRC 3: Retrieve OSS Software Components</br>
PRC 4: Determine Violations in Corporate Policies</br>
PRC 5: Modify Policy Documents</br>

