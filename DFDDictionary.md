#Data Flow Dictionary</br>

###External Entities/Externals:</br>

**Developer**- The creator/contributor to the software packages who also prepares the software packages for license scanning</br>
**Manager**- The employee that oversees the software packages and corporate policies</br>

###Dataflows:</br>

**Software Package**- Collection of code files</br>
**Software Package License and Vulnerability Results**- The list of licenses and vulnerabilities reported by the scanner</br>
**Software Package Name**- The name fo the package discovered by the scanner</br>
**Known Vulnerability Issues**- The vulnerability issues stored in the organizations database</br>
**Software Package License**- Software package licenses found by the scanner</br>
**OSS Software Components Request**- The request to obtain the software component from the database</br>
**OSS Software Components**- All related open source software components important to the company including software pakcages, licenses, and vulnerability information</br>
**OSS Software Components Violations**- List of OSS software components that go againt the corporate policy </br>
**Corporate licenses and vulnerability threshold request**- Request for the list of corporate licenses and vulnerabilities</br>
**Corporate licenses and vulnerability threshold**- Responce from the database including the list of corporate license and vulnerability information </br>
**Update/Write Confirmation**- Verification from the database that the changes or additions to the policy have been completed.</br>
**Corporate Policy Update/Write to**- The changes or additions to be added to the corporate policy provided by a manager.</br>



###Data Stores:</br>

**OSS Software Components**- The datastore that holds all software package, license, and vulnerability results.</br>
**NIST Vulnerability DB**- The databse that stores all vulnerabilities that can be fould in softwre packages.</br>
**Corporate Policy**- The datastore that stores policies on license and vulnerabilities for software packages set by the organization</br>

###Processes:</br>

**Manage Software Package for License Scanning**- The process used to prepare software packages provided from the developer for software scanning and proper stoage of data.</br>
**Scan for Licenses**- The process that manages the scanning for all licenses that can be found in the software package.</br>
**Retrieve OSS Software Components**-</br> The process used by both a manger and developer in order to retrieve the OSS software components from the databae.
**Determine Violations in Corporate Policies**- The process used to compare the OSS Software Components to the corporate policy database in order to find violations.</br>
**Modify Policy Documents**- The process that a manager uses in order to add new policies or make updates to current policies</br>

