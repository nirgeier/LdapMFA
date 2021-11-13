# ldap3_test
Python Script that simulates a user login and performs authentication via a telegram bot. Once the authentication is complete, the script will connect to ldap.forumsys.com and pull data to the terminal.
server: ldap.forumsys.com
user: read-only-admin
password: password

Python libraries used in this script:
telebot - Perform the AUTH MFA to verify a user
rich: beautiful looking text in the terminal
dotenv: save creds in '.env' file
ldap3: Perform a connection via ldap
