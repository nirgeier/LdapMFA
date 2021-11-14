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

### HOW-TO
1. Create a telegram bot with @botfather and save the Token (https://t.me/botfather)
2. Get your user id (https://t.me/userinfobot)

paste in to '.env' file with your credentials
```bash
TOKEN = 'BOT_TOKEN'
ADMIN = USER_ID
```
### Remember '.env' file shuld not be upload with sensetive data and included in '.gitignor'


## Usage:
[![Open in Cloud Shell](https://gstatic.com/cloudssh/images/open-btn.svg)](https://console.cloud.google.com/cloudshell/editor?cloudshell_git_repo=https://github.com/nirgeier/LdapMFA.git)
### **<kbd>CTRL</kbd> + click to open in new window**  