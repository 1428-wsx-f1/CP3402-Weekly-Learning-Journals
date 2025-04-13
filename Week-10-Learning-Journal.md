# Week 10 Learning Journal

## Learning Activities And Resources
- Week 10 Lecture Recordings
- Week 10 Lecture Slides



## Estimated Hours
This week I spent 2.5 hours learning for this subject.


## Content Insights
### Overview:
Security of WordPress websites is fundamental yet often overlooked. Websites can be hacked for a number of reasons including: for fun, utilising the server for malicious purposes and to extract personal information from the database. 
Due to the popularity of WordPress it is a common target for malicious actors who typically target less secured websites. Preventing these attacks is important to ensure the website and its data protection follows the CIA triad (confidentiality, 
integrity and availability). Data must be stored in a confidential manner and only visible to authorized users. It also needs to be accurate/unaltered and available to users at all times.

### Common Types Of Attacks:
- The most common attack to target WordPress websites is a Cross-site scripting (XSS) attack. Attackers inject client-side scripts into web pages and are commonly used to bypass access controls.
- SQL injection involves the insertion of malicious SQL statements inserted into input fields. If input fields are not properly sanitized, user input can trigger the database to display its contents.
- Cross-Site Request Forgery forces end users to execute unwanted actions on a web application using their already validated authentication token. This attack targets state-changing requests.

### Solutions To Security Issues:
- Limit entry points to attackers.
- Minimise damage in the event of an attack.
- Check core WordPress files for unauthorized changes and perform regular backups. Ensure those backups execute correctly.
- Only download themes/plugins from official/trusted sources.
- Always ensure that WordPress is updated.
- Changing of database table prefixes from "wp_" (the default WordPress data table prefix) will reduce the likelihood of SQL injection attacks.
- Always ensure themes and plugins are up to date and remove unused ones
- Additional plugins (from trusted sources only) can be used to ensure plugins and themes are secure and up to standard.
- Restrict plugin access for modifying files and disable file permissions to protect against unwanted changes.
- Disable PHP error reporting. This can result in sections of code being displayed as plain text, giving attackers a view into your files.
- Limiting access to certain IP addresses. This is useful for staging servers where robust security methods won't be in place to protect data.
- Employ good password practices, this includes: changing passwords often, strong passwords (for example, Th!$iS@sTR0NgPasSwOrd34# which would take [1 octillion](https://www.security.org/how-secure-is-my-password/) years to break!), trustworthy password managers and forcing users to use strong passwords.
- Limit login attempts in order to prevent brute force attacks
- Multi-factor authentication, require uses to input an access code
- For sending files to the server, use SFTP (secure file transfer protocol)
- The websites hosting platform can also be vulnerable to security attacks.
- Generate a public + private key pair known as SSH (secure socket shell)



## Career/Employability/Learning Insights
This week I learned that it takes a lot of work and consideration to make a website and secure it. Demonstrating good security practices is mandatory in a professional work environment. The security of user data is important in ensuring that businesses are 
compliant with relevant laws, regarding protection of sensitive personal information. For example the General Data Protection (GDPR) and Privacy Act of 1988. I also learned that the website produced for our group's recent assignment is far from secure. 
The only secure aspect of our website is its strong password. However, it is stored as plaintext in a Discord server and public GitHub repository. In addition, due to hosting plan limitations only FTP could be used (CloudAccess.net free plan). In the deployment.yml and production.yml workflow 
files the security variable was set to loose (this workflow was using the FTP-Deploy-Action). This combination of poor security makes our site and its data vulnerable.



### Overall Subject Learning Insights:
Over the course of this subject, I have achieved the main goal set in my first week's learning journal. I now possess the ability to create, deploy (front-end) and manage back-end functionality via a CI/CD pipeline. I have also learnt a large array of additional skills including:
- Setting up a localhost environment (primarily using LocalWP by Flywheel)
- Competency in using the WordPress block editor
- Exposure to the Joomla content management system tool
- Exposure to WordPress child themes
- Experience in making a custom WordPress theme
- Setting up a separate staging and production website. In retrospect for the second assignment, I should have named the staging site baizonn-staging to avoid confusion. Instead of baizonnlearningcenter (staging) compared to thebaizonnlearningcenter (production).
- Utilising Project Management. This includes the use of communication tools (for example: Slack, Discord, Trello), assigning of tasks and regular stand-up meetings.
- Exposure to PHP
- Experience in setting up a self-directed learning experiment
- Exposure to SASS
