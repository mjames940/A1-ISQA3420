
##Use Case 1 <br />
Title: Determine License and Vulnerability Information <br />
Primary Actor: Manager <br />
Goal in Context: The manager is able to determine license and vulnerability information provided by the project information <br />
Stakeholders: <br />
  * Manager: To recieve clear and relavant projet information <br />
  * Developer: To provide the relavant software package information <br />
  
Preconditions: <br />
  * OSS Software components has relavant data <br />
  * Proper project infomormation has been provided <br />
  
Main Success Scenario: Manager recieves accurate license and vulnerability information for the requested project packages <br />
Failed End Conditions: Manager recieves inacurrate or invalid license and vulnerability information for the requested project packages <br />
Trigger: Manager identifies project information to which license and vulnerability information is requested <br />


##Use Case 2 <br />
Title: Scan Software Package for Licenses and Vulnerabilities <br />
Primary Actor: Developer <br />
Goal in Context: The software packages are scanned and the correct license information is returned <br />
Stakeholders: <br />
  * Developer: To provide the relavant software package information for the scanner and NIST database lookup <br />
  
Preconditions: <br />
  * Software packages are managed properly for licenses scanning <br />
  * Software packages are provided correctly to the scanner <br />
  * Don't forget something here about propoer connection to the NIST DB<br />
  
Main Success Scenario: Accurate license and vulneability information is provided to the developer for the given software package <br />
Failed End Conditions: Developer recives inaccurate or invalid license and vulnerability information for the provided software package <br />
Trigger: Developer provides a software package to be managed for scanning <br />


##Use Case 3 <br />
Title: Determine Violations in Corporate Policies <br />
Primary Actors: Developer, Manager <br />
Goal in Context: The software package license and vunerabilities are compared to the corporate policy and the <br />
violations are returned to the actor <br />
Stakeholders: <br />
  * Developer and Manager: To provide the relavant software package license and vulnerabilities to be compared to the corporate policy <br />
  
Preconditions: <br />
  * Software package license and vulnerabilities are scanned and stored correctly to have a correct comparison <br />
  * Software packages license and vulnerabilities are provided correctly to be compared to the database <br />
  
Main Success Scenario: Accurate license and vulnerability information is provided to be compared to the corporate policy and all violations are returned to the actor <br />

Failed End Conditions: Developer provides inaccurate or invalid license and vulnerability information to be compared and inacurate violations are returned <br />

Trigger: Developer or Manager provides the license ad vulnerability results to be compared to the corporate policy <br />
