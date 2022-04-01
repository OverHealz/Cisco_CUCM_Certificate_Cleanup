# Certificate_Cleanup

CUCM Certificate Cleanup - Single node

### Process Overview
1. Collect all the trust certificates from CUCM using admin CLI
2. Inspect each certificate for validity
3. Delete the expired certificates using the admin CLI
4. Restart the tomcat service

### Execution
1. Install the requirements using the command "pip install -r requirements.txt"
2. Edit the .env file for CUCM admin CLI credentials
3. Open the Jupyternote CUCM_Certificate_Cleanup.ipynb and execute it cell by cell for interactive experience.
