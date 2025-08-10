# Web-App-Playbook
Web Application Playbook TTPs :: Burpsuite

## Authentication
###  Enumeration  & Bruteforce
    - Identifying Valid Usernames
    - Password Policies
        - Common places to enumerate: Registration pages, Password Reset Features, Verbose Errors, Data Breach information
        NB: Verbose Errors provide insights to internal paths, database Details and user information. Verbal Errors throw more light on password policies and account lockout mechanisms.

    - Password Reset Flow Vulnerabilities
        - Email-Based Reset: This method relies on the security of the user's email account and the secrecy of the link or token sent.
        - Security Question-Based Reset: Social Engineering
        - SMS Based Reset: SIM Swapping attacks or intercept

    - Exploiting HTTP Basic Authentication

    - OSINT: 
        - https://archive.org/web/
            // git clone https://github.com/tomnomnom/waybackurls
            // cd waybackurls
            // sudo apt install golang-go -y # This command is optional
            // go build
            // ls -lah
            // ./waybackurls tryhackme.com
        - Google Dorks:
            // To find administrative panels: site:example.com inurl:admin
            // To unearth log files with passwords: filetype:log "password" site:example.com
            // To discover backup directories: intitle:"index of" "backup" site:example.com
            
        
            
    
        
    
