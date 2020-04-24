### Security Issues

Security issues are typically handled differently than regular bugs to try to reduce visibility. To get a security fix into Sakai do the following.
 
1. Get access to the security list and security JIRA work group https://confluence.sakaiproject.org/display/SECWG/Security+Policy by emailing the contact on that page
2. Submit a JIRA ticket with security issue indicated (it's a dropdown box) detailing the security issue
3. When fixing the issue, either:
   1. Request access to private GitHub repo https://github.com/sakaiproject/sakai-security and submit a pull request.  
      * The pull request should only have the SAK/KNL/etc number, no additional comments about what was fixed 
   2. If you are unable to submit a pull request, add a diff against the JIRA ticket
4. Pull requests and new issues are generally reviewed and merged at the next Security WG or Core Team meeting prior to the next minor release of Sakai. 
5. For high priority issues email the security list directly
