#Three Use Cases <br>
##Use Case Number 1 <br>
Title: Developer commits code to be examined for vulnerabilities <br>
Primary Actor: Developer <br>
Goal in Context: Gather vulnerability information for all external source code that is used by developers <br>
Stakeholders: Developer / Manager <br>
Preconditions: Developer is able to check in external source code to vulnerability system. NIST vulnerability database is up to date. <br> 
Main Success Scenario: Developer checks in code and vulnerability information is recorded to the Risk DB. <br> 
Failed End Conditions: Developer is unable to check in code. Checked in code is not checked for vulnerabilities, failing to update Risk DB. <br>
Trigger: Code check in <br>

##Use Case Number 2
Title: Corporate manager compares policy to risk database<br>
Primary Actor: Corporate Manager <br>
Goal in Context: Compare corporate policy to vulnerability information<br>
Stakeholders: Developer / Manager <br>
Preconditions: The scan from NIST database is put in the risk database and the policy <br>
information is current<br>
Main Success Scenario: The project vulnerabilities complies with the corporate policy and the <br>
project is able to move forward<br>
Failed End Conditions: The vulnerabilities do not meet corporate policy<br>
The vulnerability scan has not been done yet<br>
Trigger: Code scan returned<br>


##Use Case Number 3
Title: Corporate developer accesses risk database<br>
Primary Actor: Corporate developer<br>
Goal in Context: Allow corporate developer to access the risk database <br> 
