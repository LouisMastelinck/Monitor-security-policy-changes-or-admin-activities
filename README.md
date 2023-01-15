# Monitor critical security policy changes 

The following repo contains detection rules for changes to your critical security policies. 
In reality security policies are often changes by administrators who want to fix a specific problem.
These changes either become forgotten, have a way bigger security impact thant the administrator might and open up a your organisations defensive measures.


## Azure Active Directory
- Conditional access rule disabled 
- Conditional access rule changed :heavy_check_mark:

## Microsft Defender for Office
- Anti-phish policy has been changed :heavy_check_mark:
- Anti-phish policy has been created :x:
- Anti-spam Policy has been changed :x:
- Anti-Spam Policy has been created :heavy_check_mark:
- Anti-malware Policy has been changed :x:
- Anti-mawlare Policy has been created :x:
- Safe attachments Policy has been changed :x:
- Safe attachments Policy has been created :x:
- Safe links Policy has been changed :x:
- Safe link Policy has been created :x:
- Tenant added to block list :x:
- Tenant removed from block :x:
