Hypothesis
Using machine learning to predict cybersecurity vulnerabilities and identify systems with the highest security risks can help organizations reduce the likelihood of cyberattacks. Instead of treating every vulnerability as equally important, an organization can use historical vulnerability data, severity scores, and system information to estimate which weaknesses are most likely to be exploited.

Data
The primary data source is the National Vulnerability Database (NVD), maintained by the National Institute of Standards and Technology (NIST). The database provides publicly available information about known software and hardware vulnerabilities. The dataset includes Common Vulnerabilities and Exposures (CVE) identifiers, vulnerability descriptions, publication dates, affected products, and Common Vulnerability Scoring System (CVSS) severity scores. Additional information about exploited vulnerabilities can come from the Cybersecurity and Infrastructure Security Agency's (CISA) Known Exploited Vulnerabilities (KEV) catalog.

Decision affected by the model
An organization's IT security team must decide which software vulnerabilities should be addressed first when maintaining its computer systems and networks. Security teams often manage many vulnerabilities but have limited time and resources to fix them all immediately. If critical vulnerabilities are not addressed quickly, attackers may exploit them to gain unauthorized access, steal information, or disrupt business operations. The machine learning model will estimate the risk associated with each vulnerability using factors such as severity scores, exploitation history, and affected systems.

