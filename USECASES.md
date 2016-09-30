
Use Case 1
Title: Determine License and Vulnerability Information
Primary Actor: Manager
Goal in Context: The manager is able to determine license and vulnerability information provided by the project information
Stakeholders: 
  -Manager: To recieve clear and relavant projet information
  -Developer: To provide the relavant software package information
Preconditions: 
  -OSS Software components has relavant data
  -Properproject infomormation has been provided
  
Main Success Scenario: Manager recieves accurate license and vulnerability information for the requested project packages
Failed End Conditions: Manager recieves inacurrate or invalid license and vulnerability information for the requested project packages
Trigger: Manager identifies project information to which license and vulnerability information is provided

Use Case 2
Title: Scan Software Package for Licenses and Vulnerabilities
Primary Actor: Developer
Goal in Context: The software packages are scanned and the correct license information is returned
Stakeholders: 
  -Developer: To porvide the relavant software package information for the scanner
Preconditions: 
  -Software packages are managed properly for licenses scanning
  -Software packages are provided correctly to the scanner
Main Success Scenario: Accurate license and vulneability information is provided to the Developer for the given software package
Failed End Conditions: Developer recives inaccurate or invalid license and vulnerability information for the provided software package
Trigger: Developer provides a software package to be managed for scanning

Use Case 3
