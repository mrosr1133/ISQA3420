
#Data flow
**Software package:** It goes from Developer to Manage Software Package for License Scanning.

**Software package:** It goes from Manage Software Package for License Scanning to Scan for License.

**Software Package License Results:** It goes from Scan for License back to Manage Software Package for License Scanning.

**Software Package License Name Request:** It goes from Manage Software Package for License Scanning to NIST Vulnerability Database. 

**NST Vulnerability Database Results:** It goes from NIST Vulnerability Database back to Manage Software Package for License Scanning.

**Software Package License and Vulnerability Results:** It comes from Manage Software Package for License Scanning back to Developer.

**Software Package License and Vulnerability Results:** It goes from Manage Software Package for License Scanning to Project Vulnerability Database. 

**Project Vulnerability Database Results:** It goes from Project Vulnerability Database to Proceeing and Totalizing Project Database.

**Project Vulnerability Database Request:** It goes from Proceeing and Totalizing Project Database back to Project Vulnerability Database.

**Project Vulnerability Database Results:** It goes from Proceeing and Totalizing Project Database to Manager.

**Project Vulnerability Database Request:** It goes from Manager back to Proceeing and Totalizing Project Database.

**Update and Create Policy Request:** It goes from Manager to Update and Create Policy.

**Update and Create Policy Results:** It comes out of Update and Create Policy back to Manager.

**Update and Create Policy Request:** It goes from Update and Create Policy to Policy Database.

**Update and Create Policy Results:** It goes from Policy Database back to Update and Create Policy.

**Open Source Software Policy Database Request:** It goes out of Manager to Processing and Totalizing Policy Database.

**Open Source Software Policy Database Results:** It goes from Processing and Totalizing Policy Database back to Manager.

**Open Source Software Policy Database Request:** It goes from Processing and Totalizing Policy Database to Policy Database.

**Open Source Software Policy Database Results:** It comes out of Policy Database back to Processing and Totalizing Policy Database.

**Open Source Software Policy Database Request:** It goes from Developer to Processing and Totalizing Policy Database.

**Open Source Software Policy Database Results:** It goes from Processing and Totalizing Policy Database back to Developer.

**Project Vulnerability Database Request:** It comes out of Developer to Proceeing and Totalizing Project Database.

**Project Vulnerability Database Results:** It goes from Proceeing and Totalizing Project Database back to Developer.

#Entities
**Developer:** 

**Manager:** 

#Processes
**Manage Software Package for License Scanning:**

**Scan for License:**

**Processing and Totalizing Policy Database:**

**Processing and Totalizing Policy Database:**

**Upload Policy:**

#Database
**NST Vulnerability Database:**

**Project Vulnerability Database:**

**Policy Database:**
