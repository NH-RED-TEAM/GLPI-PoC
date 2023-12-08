# GLPI-PoC
GLPI PoC - Security advisory

This repository is used to host our exploitation scripts for the vulnerabilities that have been disclosed to Teclib for the GLPI project.
The vulnerabilities were patched in 10.0.10 version of GLPI.

# CVE
CVE-2023-42461 - SQL injection in ITIL actors
CVE-2023-42462 - File deletion through document upload process
CVE-2023-42802 - Unallowed PHP script execution

# Timeline
- September 19 2023 : disclosure of the critical vulnerability to the editor with immediate feedback
- September 20 2023 : CVE number request is rejected by Github for the critical vulnerability
- September 20 2023 : 2 other CVEs are disclosed to the editor : CVE-2023-42461 and CVE-2023-42462 are assigned
- September 21 2023 : Github finally assigns CVE-2023-42802 for the critical vulnerability
- September 25 2023 : GLPI 10.0.10 is released, fixing among others all three vulnerabilities
- We decided under a common agreement to wait for early november to disclose the information to the public. The CVEs will thus stay private until this date. 
- November 3 2023 : CVEs details is disclosed to the public without the POCs
- December 8 2023 : Publication of the blog post along with the technical details to reproduce the exploitation
