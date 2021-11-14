#### LDAP MFA Demo code
- Python Script that simulates a user login and performs authentication via a telegram bot.   
- Once the authentication is complete, the script will connect to `ldap.forumsys.com` and pull data to the terminal.

Property  | Value
----------|---------------
server    | ldap.forumsys.com
user      | read-only-admin
password  | password

### Python libraries used in this script:

Library           | Link                                          | Description
------------------|-----------------------------------------------|--------------------------------------------
pyTelegramBotAPI  | https://github.com/eternnoir/pyTelegramBotAPI | Perform the AUTH MFA to verify a user
rich              | https://github.com/willmcgugan/rich           | Rich is a Python library for rich text and beautiful formatting in the terminal.
dotenv            | https://github.com/theskumar/python-dotenv    | Python-dotenv reads key-value pairs from a `.env` file and can set them as environment variables.
ldap3             | https://github.com/cannatag/ldap3             | Perform a connection via ldap


## Usage:
[![Open in Cloud Shell](https://gstatic.com/cloudssh/images/open-btn.svg)](https://console.cloud.google.com/cloudshell/editor?cloudshell_git_repo=https://github.com/nirgeier/LdapMFA.git)
### **<kbd>CTRL</kbd> + click to open in new window**  