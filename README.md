# Anuj Shrivastava

I sit with customer teams and help them use AI with the security tools they already have. Customers run many vendors. I keep the AI use safe, and I keep security and AI together. I leave a working setup, not a slide.

## Work you can open

### QRadar, used through AI
A security team can ask an AI about QRadar alerts, logs, and rules. I put 728 QRadar APIs behind 4 tools so the AI can use them. That cuts the extra text from about 50,000 tokens down to about 2,000.

https://github.com/IBM/qradar-mcp-server

### Guardium Data Protection, used through AI
A customer can ask an AI who used a database, what policy is on, and whether Guardium is healthy. I wrote this so they do not have to click through the Guardium screens for every question.

https://github.com/IBM/gdp-mcp-server

### Guardium Cryptography Manager, used through AI
A customer can ask an AI what keys and certificates they have, which ones are weak, and what to fix before old crypto breaks.

https://github.com/IBM/gcm-mcp-server

### IBM Verify, used through AI
A customer can ask an AI about users, apps, and login rules in IBM Verify. I put 210 Verify APIs behind 4 tools.

https://github.com/IBM/verify-mcp-server

### Threat lists from MISP into QRadar
I pull bad IPs and files from MISP and load them into QRadar, so QRadar can alert when those show up. IBM also published my write-up.

https://github.com/IBM/qradar-misp-ioc-importer  
https://github.com/anujshrivastava15/MISP-IOC-Importer-For-QRadar  
https://developer.ibm.com/articles/awb-import-iocs-from-misp-to-qradar/

### US patent 12021897
Issued US patent: endpoint and remote server protection.

https://patents.google.com/patent/US12021897B2

### SAGE
I wrote an IBM article on SAGE: agents collect audit proof for a SOC, instead of people copying screens.

https://developer.ibm.com/articles/sage-audit-evidence-collection/

## How I work

I write Python. I work with security APIs. I sit with the customer until the setup runs.
