#Data Flow Diagram Dictionary
Corporate Developer- Internal developer to the company<\n>
File- File being sent to NIST for vulnerability scan
Package- Package being sent to NIST for vulnerability scan
Code scan- The process that organize files or packages being sent to NIST to be scanned for vulnerabilities
Package Query- The request for your package to be scanned in the NIST database
CPE Information- Information being returned from NIST with the vulnerability information in it
NIST CPE Information - Database, which contains the NIST vulnerabilities data, about a CPE being sent to the risk DB
CPE File- File of CPE information being sent from NIST Vulnerability Database
Package Information- Information, which contains the NIST vulnerabilities data, about a package being sent to the risk DB 
Manage CPE Information – Process, manage CPE information every day (daily job).
CPE Request- The request for CPE information from the National Vulnerability Database
CPE Response- The response of CPE from the National Vulnerability Database
National Vulnerability Database- NIST database that contains all known vulnerabilities, where CPE information comes from
Corporate Manager- Internal, to the company, Manager which sees over a specific project  
Project Info Request- The request for project info from the Risk DB, (vulnerabilities, CPE information etc.)
Project Info Response- The response to Project Info Request that contains information on a specific 
Project (vulnerabilities, CPE information etc.)
Manage Project Information- Manages the information of a project, allows the manager to access the risk DB 
Package Info Request - Information, the request from manager for risk code information from Risk DB
Package Info Response – Information, the risk code info response from Risk DB 
Risk Database – Database, store the risk code with vulnerability returned from the NIST CPE scanner
Edit Policy- Allows the manager to set and edit the policy in Policy DB
Policy Info Response - Allows the manager get policy info from Policy DB through the set policy process
Set Policy - The process that organize managers’ edition of policies for project vulnerabilities thresholds
Policy DB- The database which houses the policies for project vulnerabilities thresholds
Request Data- The process of the corporate developer accessing the Risk Database
Request Info – The request for risk code from corporate developer
Info Response – The response of risk code to corporate developer
