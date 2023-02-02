# Monitor critical security actions 

## Policy changes
The following repo contains detection rules for changes to your critical security policies. 
In reality security policies are often changes by administrators who want to fix a specific problem.
These changes either become forgotten, have a way bigger security impact thant the administrator might and open up a your organisations defensive measures.

## Threat explorer
With the correct permission the Threat explorer can be used to view any email in any user his mailbox. 
Its a very strong security toolt that allows you to "preview" and "download" any email that is still within the mailbox. 
In the wrong hand (insider threat), this legitemate securit could be easily abused. 

You can find these actions in the logs, but Microsoft doesn't provide alerting by default to these actions. 
You can use the following KQL rules to create your own alerting. 


### Azure Active Directory
- Conditional Access rule has been deleted :heavy_check_mark:
- Conditional Access rule has been created :heavy_check_mark:
- Conditional Access rule disabled /enabled :heavy_check_mark:
- Conditional Access rule changed :heavy_check_mark:
- Enterprise applications, admin consent settings is changed :heavy_check_mark:

### Microsft Defender for Office
- Anti-Phish policy has been changed :heavy_check_mark:
- Anti-Phish policy has been created  :heavy_check_mark:
- Anti-Phish policy has been deleted :heavy_check_mark:
- Anti-Spam Policy has been changed :heavy_check_mark:
- Anti-Spam Policy has been created :heavy_check_mark:
- Anti-Spam Policy has been deleted :heavy_check_mark:
- Anti-Malware Policy has been changed :heavy_check_mark:
- Anti-Malware Policy has been created :heavy_check_mark:
- Anti-Malware Policy has been removed :heavy_check_mark:
- Safe Attachments Policy has been changed :heavy_check_mark:
- Safe Attachments Policy has been created :heavy_check_mark:
- Safe Attachments Policy has been deleted :heavy_check_mark:
- Safe Link Policy has been changed :heavy_check_mark:
- Safe Link Policy has been created :heavy_check_mark:
- Safe Link Policy has been deleted :heavy_check_mark:
- Tenant added to block list :heavy_check_mark:
- Tenant removed from block list 🐛


## Exchange online
- Creation of a transport rule :heavy_check_mark:

## bugs🐛
- Tenant removed from block list does not contain a clear value of the domain/tenant removed from the list


## to develop
- searches performed via the threatexplorer


