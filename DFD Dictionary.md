#Data Flow Diagram Dictionary

##Data Flows<br>

CPE File- File of CPE information being sent from NIST Vulnerability Database <br>
CPE Request- The request for CPE information from the National Vulnerability Database <br>
CPE Response- The response of CPE from the National Vulnerability Database <br>
Package Query- The request for your package to be scanned in the NIST database <br>
CPE Info- Information being returned from NIST with the vulnerability information in it.<br>
Package- Package being sent to NIST for vulnerability scan <br> 
File- File being sent to NIST for vulnerability scan <br>
Risk info request - information, Compare risk info and policy process request risk info from risk database. <br>
Risk Info response - information, the risk info response to compare risk info and policy. <br>
Package Info Request - Information, the request from manager for risk code information from Risk DB<br> 
Package Info Response – Information, the risk code info response from Risk DB <br>
Project Info Request- The request for project info from the Risk DB, (vulnerabilities, CPE information etc.) <br>
Project Info Response- The response to Project Info Request that contains information on a specific <br>
Project Info - Allows the manager to send project Information to Create Manifest process. <br>
Project Info - Allows the manager to send project Information to Check against Policy process. <br>
Against Policy Info Response - Against policy information back to manager from Check against Policy process.<br>
Policy Info Request - information, request of policy information from check against Policy process. <br> 
Policy Info Response - Allows the manager get policy info from Policy DB through the Check against Policy process <br>
Manifest Information- information, manifest info downstream to downstream people such as customors.<br> 


##Data stores <br>
NIST CPE Information - Database, which contains the NIST vulnerabilities data, about a CPE being sent to the risk DB <br>
Risk Database – Database, store the risk code with vulnerability returned from the NIST CPE scanner <br>
Policy DB- The database which houses the policies for project vulnerabilities thresholds <br>

##Entities<br>
Corporate Developer- Internal developer to the company <br>
Corporate Manager- Internal, to the company, Manager which sees over a specific project <br>
National Vulnerability Database- NIST database that contains all known vulnerabilities, where CPE information comes from <br>
Downstream People - External, this entity recieves manifest information from internal corporate manager. <br>

##Processes
Code scan- The process that organize files or packages being sent to NIST to be scanned for vulnerabilities <br>
Request Data- The process of the corporate developer accessing the Risk Database <br>
Manage CPE Information – Process, manage CPE information every day (daily job). 
Manage Project Info- Manages the information of a project, allows the manager to access the risk DB <br>
Check against Policy- process, that get project information from manager and check against policy. <br>
Create Manifest - process, create the manifest information <br>






